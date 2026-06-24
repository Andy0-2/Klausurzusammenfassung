# GPM – Spickzettel (Formeln & Modelle)

*Hochschule Trier · Geschäftsprozessmanagement · Kompaktblatt für die Klausur*

---

## ⏱️ FORMELN

| Größe | Formel |
|---|---|
| **Durchlaufzeit** | DLZ = **BZ + WZ** (Bearbeitungs- + Wartezeit) |
| **Durchlaufzeit­effizienz** | **BZ / DLZ** (Verwaltung typ. < 15 %) |
| **Little's Law** | **L = λ · W** (WIP = Ankunftsrate × Verweilzeit) → *Einheiten angleichen!* |
| **Auslastung (Queue)** | **ρ = λ / μ** (μ = Bedienrate); ab **ρ > 0,8 explodieren Wartezeiten** |

### DLZ in BPMN-Strukturen (Aktivitätszeit in Klammern)

| Struktur | Regel | Beispiel |
|---|---|---|
| **Sequenz** | **Summe** | A(10)→B(20) = **30** |
| **Alternativ (XOR)** | A + **gewichtetes Ø** der Zweige | 10 + 0,1·20 + 0,9·10 = **21** (bzw. 50/50: 10+(20+10)/2 = **25**) |
| **Parallel (AND)** | A + **MAX** der Zweige | 10 + max(20,10) = **30** |
| **Schleife** | A + **Schleifenkörper / p** (p = Erfolgs-/Austritts-W.) | 10 + 20/0,8 = **35** · bei p=0,01: **2010** |

> **Merke:** Sequenz **+** · Parallel **max** · Alternativ **gew. Ø** · Schleife **÷ p**

**Little-Rechenbeispiel:** 1200 Anträge/Jahr, Ø 1 Monat DLZ → λ·W = (1200/12)·1 = **100 laufende Vorgänge**

---

## 🔍 ANALYSE-WERKZEUGE

**WSA – drei Kategorien** (Ziel: NWS↓, GWS hinterfragen, WS schützen)
- **WS** = Wert für Kunden (Kunde zahlt) · **GWS** = für Unternehmen nötig (Compliance/Pflicht) · **NWS** = wertlos (Doppelarbeit, Warten, Korrektur)
- 3 Leitfragen: *Würde Kunde zahlen? · Merkt er das Weglassen? · Risiko-/Pflichtbeitrag?* → im Zweifel **NWS/GWS, nicht WS**

**7 Arten der Verschwendung (muda):**
**T**ransport · **B**ewegung · **B**estände · **W**artezeit · **F**ehler · **M**ehraufwand · **Ü**berproduktion
> *„Verschwendung ist Ergebnis, nicht Ursache."*

**Auswirkung → Problem → Ursache** (Symptom → Grundphänomen → Wurzel)

**Ishikawa (6 M):** Mensch · Maschine · Methode · Messung · Material · Mitwelt → **breit**, viele Ursachen, zu Beginn
**5-Why:** **tief**, eine Spur, Wurzelursache → *erst Ishikawa, dann pro Hauptast 5-Why*

**Interessengruppenanalyse (5 Schritte):** Stakeholder identifizieren → Interviews → je Sicht dokumentieren (ohne Interpretation) → gegenüberstellen → Synthese (mehrfach genannt?)

---

## 🚦 ENGPASS & PRIORISIERUNG

**Engpass (Bottleneck):** Ressource, die den **Gesamtdurchsatz limitiert**.
**Theory of Constraints:** Nicht-Engpass optimieren bringt nichts → **finden → erweitern → neuer Engpass → wiederholen**.
**Indikatoren:** hohes WIP (Stau **vor** Engpass), Auslastung ~100 %, Überstunden/Eskalationen, häufig in Beschwerden.

**Impact-Effort (PICK):** **P**ossible (niedrig/hoch-Aufwand) · **I**mplement (hoch/niedrig = **Quick Wins zuerst**) · **C**hallenge (hoch/hoch) · **K**ill (niedrig/hoch)
**Pareto 80/20:** ~20 % Ursachen → ~80 % Wirkung.

**Problemregister:** Cluster → Ursache → Wirkung → Priorität. Belege V- (Verschwendung) & I- (Interview); Cluster via KJ-Methode/Affinitätsdiagramm; Kodierung n. Mayring.

---

## 🎯 PHASE 4 – REDESIGN

**Analyse = Diagnose · Redesign = Therapie** (As-is → To-be)
**Inkrementell** (Kaizen/Lean/Six Sigma DMAIC – sicher, flach) vs. **Radikal/BPR** (Hammer/Champy/Davenport – Sprung, riskant)

**Devil's Quadrangle:** **Z**eit · **K**osten · **Q**ualität · **F**lexibilität → selten gleichzeitig verbesserbar.
*Operationalisieren:* Zeit=DLZ/%fristgerecht · Kosten=Σ(Zeit×Satz)+Nacharbeit · Qualität=Fehler-/Rücklaufquote, First-Pass-Yield · Flexibilität=#Varianten/Anpassungszeit. *(Lücke: bildet Akzeptanz/Change/Risiko NICHT ab!)*

**Reijers & Mansar Heuristiken** (~29 in **7 Kategorien**: Kunden·Operation·Verhalten·Organisation·Information·Technologie·Umwelt):
- **Task elimination** (OP) – Aufgabe streichen · **Knock-out/Resequencing** (V) – billige/ablehnende Checks zuerst
- **Parallelism** (V) – unabhängige Aufgaben parallel · **Triage** (OP) – Fälle nach Typ trennen
- **Task automation** (T) – Medienbruch beseitigen · **Integration/Contact reduction** (K) – Kunde einbinden
- **Control addition/relocation** (I) – Prüfung an die Quelle · **Buffering** (I) – Info einmal vorhalten
- **Empower** (O) – Befugnis ↑, Schleifen ↓ · **Case manager** (O) – 1 Person je Fall

**Simulation (ex ante):** Verteilungen statt Einzelwerte (DLZ, WZ, Auslastung, Kosten, Durchsatz) + Konfidenz.
*Vorgehen:* Modell ableiten → Eingaben schätzen → verifizieren → **validieren/kalibrieren (vs. Ist)** → Experimente.
**Monte-Carlo** = summiert Verteilungen, **ohne** Ressourcenkonkurrenz (schnell). **DES** = + Warteschlangen/Kapazitäten, zeigt **Engpässe unter Last**.
*Tools:* SAP Signavio, Bizagi, Camunda, ARIS (BPM) · Arena, AnyLogic, SimPy (DES).
*Stau-Effekt:* bei 80 % Auslastung wartet 1 Ticket ø ~32 Min, bei 95 % > 2 h (nichtlinear!).

**Redesign-Vorgehen:** Potenziale → Varianten (Heuristik) → Bewerten (Quadrangle+Sim) → Auswählen → **Dokumentieren (Befund→Heuristik→Entscheidung)**

---

## 🚀 PHASE 5 – IMPLEMENTATION

**Erfolg = Prozess wird gelebt** (nicht: System läuft). **Zwei Stränge:** Mensch&Organisation + System&Technik (Technik ohne Akzeptanz scheitert).

**Vom Modell zum ausführbaren Prozess:** verfeinern (Fehlerpfade) → Daten/Formulare → **User-Task (Mensch) vs. Service-Task (System)** → Services anbinden → BPMS-ausführbar.

**Rollout-Strategien:**
- **Big-Bang** – ein Stichtag · schnell, kein Doppelbetrieb · **hohes Risiko**
- **Pilot/phasenweise** – Teilbereich zuerst · lernen, Risiko begrenzt · länger
- **Parallelbetrieb** – alt+neu parallel · sicher, vergleichbar · **doppelte Last, teuer**

**Teststufen:** Komponente → Integration → **UAT** → Pilot.
**UAT:** Nutzer prüfen realistische Fälle; Kriterien **vorab/messbar/fachlich**, Normal+Sonderfälle, **Sign-off = Go-live-Voraussetzung**. IT testet *funktioniert System?*, Fachbereich/Key-User *erfüllt Prozess Anforderungen?*

**Change-Management-Modelle:**
- **Lewin (3):** **Unfreeze** (auftauen) → **Change** (verändern) → **Refreeze** (einfrieren/verankern)
- **Kotter (8):** Dringlichkeit · Koalition · Vision · Vision vermitteln · Hindernisse weg · **Quick Wins** · Erfolge ausbauen · **Kultur verankern**
- **ADKAR (Individuum):** **A**wareness → **D**esire → **K**nowledge → **A**bility → **R**einforcement *(Warum→Wollen→Wissen-wie→Können→Dranbleiben)*

**Widerstand ist Information** → zeigt fehlenden Sinn / Befähigung / Beteiligung.
*Hebel:* Leitungssupport · frühe ehrliche Kommunikation (**Warum vor Was**, Zweiweg) · Beteiligung · Schulung **nah am Go-live** · Quick Wins · UAT.

---

### ⚠️ TOP-FEHLERQUELLEN
1. Parallel (AND) **summieren** statt **max** nehmen.
2. Schleife: vergessen, **durch p zu teilen**.
3. Little: **Einheiten** nicht angleichen.
4. *Auswirkung* mit *Problem/Ursache* verwechseln.
5. Ishikawa (breit) ↔ 5-Why (tief) vertauschen.
6. Monte-Carlo ↔ DES verwechseln (DES = mit Warteschlangen).
7. Devil's-Quadrangle-Lücke vergessen (Akzeptanz/Change).
8. Schulung „zu früh" als Erfolgsfaktor nennen (→ falsch: **nah am Go-live**).
