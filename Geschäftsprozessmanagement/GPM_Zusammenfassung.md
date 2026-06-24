# Geschäftsprozessmanagement (GPM) – Klausur-Zusammenfassung

*Hochschule Trier · FB Wirtschaft · SS26 · Prof. Dr. Andrea Walkenhorst*
*Themen: Prozessanalyse, Ursachenanalyse, Durchlaufzeiten & Engpässe, Priorisierung, Phase 4 (Redesign), Phase 5 (Implementation)*

---

## 📑 Inhaltsverzeichnis

**TEIL A – PROZESSANALYSE (Diagnose)**
1. [Prozessanalyse: Diagnose vor Therapie](#1) · *Orig. S. 2–3*
2. [Wertschöpfungsanalyse (WSA)](#2) · *Orig. S. 4–6*
3. [Verschwendungsanalyse – 7 Arten der Verschwendung](#3) · *Orig. S. 7–10*

**TEIL B – PROBLEME & URSACHEN (Sitzung 2)**
4. [Auswirkung → Problem → Ursache](#4) · *Orig. S. 12–14*
5. [Interessengruppenanalyse (Stakeholder)](#5) · *Orig. S. 15–16*
6. [Ishikawa-Diagramm (Fischgräten)](#6) · *Orig. S. 17–19*
7. [5-Why-Methode](#7) · *Orig. S. 20–22*

**TEIL C – DURCHLAUFZEITEN & ENGPÄSSE**
8. [Devil's Quadrangle (Trade-offs)](#8) · *Orig. S. 24*
9. [Durchlaufzeitanalyse & Grundbegriffe](#9) · *Orig. S. 25–31*
10. [Engpassanalyse & Theory of Constraints](#10) · *Orig. S. 32–35*
11. [Little's Law](#11) · *Orig. S. 34*
12. [Warteschlangen & Simulation (Ausblick)](#12) · *Orig. S. 36–38*

**TEIL D – PRIORISIEREN & PROBLEMREGISTER**
13. [Impact-Effort-Matrix (PICK)](#13) · *Orig. S. 40*
14. [Pareto-Prinzip (80/20)](#14) · *Orig. S. 41*
15. [Problemregister & Qualitätssicherung der Analyse](#15) · *Orig. S. 42–44*

**TEIL E – PHASE 4: PROCESS REDESIGN**
16. [Einordnung, Begriff & Lernziele](#16) · *Orig. S. 45–48*
17. [Inkrementell vs. Radikal](#17) · *Orig. S. 49*
18. [Methode 1: Redesign-Heuristiken (Reijers & Mansar)](#18) · *Orig. S. 50–59*
19. [Methode 2: Devil's Quadrangle operationalisiert](#19) · *Orig. S. 60–63*
20. [Methode 3: Geschäftsprozess-Simulation](#20) · *Orig. S. 64–70*
21. [Redesign-Vorgehen & QS](#21) · *Orig. S. 71–75*
22. [Fallstudie Regio Versicherung AG](#22) · *Orig. S. 51, 59, 63, 70, 72–73*

**TEIL F – PHASE 5: PROCESS IMPLEMENTATION**
23. [Begriff & zwei Stränge](#23) · *Orig. S. 76–80*
24. [Vom Modell zum ausführbaren Prozess](#24) · *Orig. S. 81*
25. [Rollout-Strategien](#25) · *Orig. S. 82–83*
26. [Test & Abnahme / UAT](#26) · *Orig. S. 84–86*
27. [Change-Management: Lewin, Kotter, ADKAR](#27) · *Orig. S. 87–93*
28. [Widerstände, Kommunikation & Erfolgsfaktoren](#28) · *Orig. S. 94–99*

**ZUSATZ**
- [⭐ Top-10-Konzepte für Schnelllerner](#top10)
- [📝 Typische Klausurfragen](#klausur)
- [🔗 Häufig geprüfte Zusammenhänge](#zusammenhaenge)
- [🧠 Merkregeln & Eselsbrücken](#merkregeln)
- [✅ Selbstcheck-Checkliste](#checkliste)

---
---

# TEIL A – PROZESSANALYSE

<a id="1"></a>
## 1. Prozessanalyse: Diagnose vor Therapie

**Leitprinzip des GPM:** Erst diagnostizieren, dann therapieren.

- **Ziel:** Probleme und Verbesserungspotenziale **systematisch sichtbar machen**.
- **Voraussetzung jeder sinnvollen Optimierung** – ohne Diagnose nur **Symptombekämpfung**.
- **Zwei sich ergänzende Sichtweisen:** qualitativ + quantitativ.
- **Faustregel:** erst breit **qualitativ** schauen → dann **quantitativ** vertiefen.

### Qualitativ vs. quantitativ

| | **Qualitative Analyse** | **Quantitative Analyse** |
|---|---|---|
| **Leitfrage** | Was läuft *inhaltlich* schlecht? | Wie schnell, wie teuer, wie viele? |
| **Werkzeuge** | WSA, Verschwendungsanalyse, Ishikawa, 5-Why | Durchlaufzeit, Auslastung, Simulation |
| **Stärke** | Tiefe, Perspektivenvielfalt | vergleichbar, faktenbasiert |
| **Grenze** | subjektiv, schwer vergleichbar | braucht Daten (nicht immer vorhanden) |

> **Faustregel:** Erst qualitativ die **Hot Spots** finden, dann quantitativ **priorisieren**.

🔗 *Siehe auch: Kap. 9 (quantitativ), Kap. 13–15 (Priorisierung).*

---

<a id="2"></a>
## 2. Wertschöpfungsanalyse (WSA)

Klassifikation aus dem **Lean Management** – jeder Prozessschritt wird einer von **drei Kategorien** zugeordnet:

| Kürzel | Kategorie | Bedeutung | Beispiel |
|---|---|---|---|
| **WS** | **Wertschöpfend** | Schafft Wert für den Kunden; Kunde würde dafür bezahlen | Beratung / Leistung am Kunden |
| **GWS** | **Geschäfts­wertschöpfend** | Für das Unternehmen notwendig (Compliance, Kontrolle, gesetzliche Pflicht) | Gesetzlich vorgeschriebene Dokumentation |
| **NWS** | **Nicht-wertschöpfend** | Weder für Kunde noch Unternehmen wertvoll (Doppelarbeit, Warten, Korrekturen) | Doppelte Dateneingabe wegen Medienbruch |

> **Ziel:** **NWS minimieren · GWS kritisch hinterfragen · WS schützen.**

### Drei Leitfragen (Quick-Check je Schritt)
1. Würde der Kunde bereit sein, **für diesen Schritt zu bezahlen**? *(→ ja = WS)*
2. Wenn wir den Schritt **weglassen**, würde der Kunde es **merken**?
3. Trägt der Schritt zur **Risikoabsicherung / gesetzlichen Pflicht** bei? *(→ ja = GWS)*

> **Praxis-Tipp:** Im Zweifel ist es eher **NWS oder GWS – nicht WS**.

### ⚠️ Grenzen der WSA (warum man zur Verschwendungsanalyse wechselt)
- Abgrenzung **WS vs. GWS** oft **strittig** → kostet Zeit, ohne tiefer zu führen.
- **Subjektivität:** Wer entscheidet, was der Kunde wertschätzt? Antworten je Perspektive verschieden.
- Bei **wissensintensiven Prozessen** (Beratung, Forschung) sind „Schritte" **unscharf** definiert.
- **Ansatz des Skripts:** WSA als **Denkbrille** nutzen, *nicht* als Hauptwerkzeug. → konkretes Werkzeug = **7 Arten der Verschwendung**.

🔗 *Siehe auch: Kap. 3 (Verschwendung).*

---

<a id="3"></a>
## 3. Verschwendungsanalyse – 7 Arten der Verschwendung

### Lean-Hintergrund
- **Ursprung:** Toyota Production System (**Taiichi Ohno**) – ursprünglich Fertigung.
- Übertragbar auf **Verwaltungs-, Service- und Wissensprozesse**.
- **Kernidee:** Verschwendung (jap. **muda**) = alles, was **Ressourcen verbraucht, ohne Wert zu schaffen**.
- Sieben Kategorien = klares **Suchraster**.

### Die 7 Arten (Büro-/Verwaltungskontext)

| # | Art | Bürobeispiel |
|---|---|---|
| 1 | **Transport** | Unnötige Wege von Informationen oder Papier |
| 2 | **Bewegung** | Suchaufwand, manuelles Übertragen von Daten |
| 3 | **Bestände** | Offene Anfragen, unbearbeitete Formulare |
| 4 | **Wartezeit** | Verzögerung durch Unterschriften / Rückläufe |
| 5 | **Fehler** | Unvollständige Anträge, fehlerhafte Dokumente, Rücksendungen |
| 6 | **Mehraufwand** | Doppelte Prüfungen, unnötige manuelle Korrekturen |
| 7 | **Überproduktion** | Unnötig früh/mehrfach erstellte Dokumente |

### Typische Ursachen für Verschwendung
> **Merksatz: Verschwendung ist meist Ergebnis, nicht Ursache.**
- Schlechte **Prozessgestaltung** (zu viele Übergaben, unklare Verantwortungen)
- **Systemmedienbrüche** (manuelles Übertragen zwischen Systemen)
- **Schwache Standards** (jede:r macht es anders)
- **Fehlende Kennzahlen** (nicht gemessen → nicht behoben)
- **Kulturelle Faktoren** („Beschäftigtsein" mit Wertschöpfung verwechselt)

🧠 **Eselsbrücke 7 Arten:** **„TBB-WF-MÜ"** = **T**ransport, **B**ewegung, **B**estände, **W**artezeit, **F**ehler, **M**ehraufwand, **Ü**berproduktion.
*(Vgl. klassisches Lean-„TIMWOOD" – hier auf das Büro übersetzt.)*

⚠️ **Verwechslungsgefahr:** *Bewegung* (Person/Daten bewegen sich, z. B. Suchen) ≠ *Transport* (Material/Info wird von A nach B befördert).

---
---

# TEIL B – PROBLEME & URSACHEN

> **Motivation:** Verschwendungen sind **identifiziert** – aber kennt man die **Ursachen**?
> **Verschwendung ohne Ursachenkenntnis = Symptombekämpfung.**
> Wichtig: **Mehrere Perspektiven** einsammeln, *bevor* interpretiert wird.

<a id="4"></a>
## 4. Auswirkung → Problem → Ursache

Drei Begriffe, die oft **vermischt** werden. Reihenfolge der „Tiefe":

| Begriff | Definition | Beispiel (Hochschule) |
|---|---|---|
| **Auswirkung** | Was sichtbar wird (Symptom) | „Studierende beschweren sich über lange Wartezeiten" |
| **Problem** | Das Grundphänomen | „Themenabstimmung dauert oft mehrere Wochen" |
| **Ursache** | Die Wurzel | „Keine zentrale Themen-Datenbank, keine Kapazitätsanzeige" |

⚠️ **Klausurfalle:** Eine *Auswirkung* (Beschwerde) ist **kein** Problem und schon gar keine Ursache. Man therapiert die **Ursache**, nicht das Symptom.

---

<a id="5"></a>
## 5. Interessengruppenanalyse (Stakeholder-Analyse)

**Eine der wichtigsten Methoden für die Akzeptanz späterer Lösungen.**

### Idee
- **Ziel:** Probleme aus Sicht **verschiedener Beteiligter** sammeln.
- Verschiedene Stakeholder **erleben denselben Prozess unterschiedlich**.
- Was für das Sekretariat effizient ist, kann für Studierende frustrierend sein.
- Ohne diese Vielfalt droht Optimierung **„aus der Brille einer Abteilung"**.

### 5-Schritte-Schema
1. **Stakeholder identifizieren** – wer ist beteiligt, betroffen, einflussreich?
2. Je Stakeholder **kurze Interviews/Workshops** (15–30 Min reichen oft).
3. Probleme/Beobachtungen **je Sichtweise dokumentieren** – *ohne Interpretation*.
4. **Sichtweisen gegenüberstellen** – Widersprüche *und* Übereinstimmungen sind beide wertvoll.
5. **Synthese** – welche Probleme erscheinen **mehrfach**?

🔗 *Siehe auch: Kap. 15 (Belege „I-" = Interessengruppen-/Interviewanalyse im Problemregister).*

---

<a id="6"></a>
## 6. Ishikawa-Diagramm (Fischgräten- / Ursache-Wirkungs-Diagramm)

- **Visuelles Werkzeug** zur **systematischen Aufdeckung der wesentlichen Ursachen** eines Problems.
- Entwickelt von **Kaoru Ishikawa**, **1960er** (Qualitätsmanagement).
- **Aufbau:** Problem als **„Fischkopf" rechts**, **Hauptkategorien als Gräten**, Ursachen als **Verästelungen**.
- **Stärke:** zwingt zu **Vollständigkeit über alle Kategorien** → verhindert **Tunnelblick**.

### Die 6 M (Hauptkategorien)
**Mensch · Maschine · Methode · Messung · Material · Mitwelt**

🧠 **Eselsbrücke:** **„6 M"** – alle fangen mit M an. (Mitwelt = Umwelt/Umgebung.)

⚠️ **Stärke = breit, nicht tief:** Ishikawa sammelt **viele** mögliche Ursachen, geht aber **nicht** in die Tiefe einer einzelnen Spur (dafür 5-Why).

---

<a id="7"></a>
## 7. 5-Why-Methode

- **Prinzip:** Fünfmal (sinngemäß) **„Warum?"** fragen.
- **Zweck:** **Präzisierung**, um die **wirklich zugrunde liegende Ursache** (Wurzelursache) herauszufinden.
- **tief**, verfolgt **eine Spur**.

### Ishikawa vs. 5-Why – wann was? (häufig geprüft!)

| | **Ishikawa** | **5-Why** |
|---|---|---|
| Charakter | **breit**, viele Ursachen | **tief**, eine Spur |
| Eignung | Workshops, **zu Beginn** | ausgewählte **Hauptursachen** |
| Praxis | erst Ishikawa … | … dann pro Hauptast 5-Why |

> **Beide brauchen Daten und Beobachtungen – nicht nur Bauchgefühl.**
> **Praxis-Kombination:** Erst Ishikawa (alle Kategorien), dann pro Hauptast 5-Why.

🧠 **Merke:** *Ishikawa = Landkarte (Breite), 5-Why = Bohrkern (Tiefe).*

---
---

# TEIL C – DURCHLAUFZEITEN & ENGPÄSSE

<a id="8"></a>
## 8. Devil's Quadrangle – die Trade-offs

**Vier Dimensionen**, die sich **nicht gleichzeitig maximieren** lassen (nach **Brand & van der Kolk**):

| Dimension | Leitfrage |
|---|---|
| **Zeit** | Wie schnell? |
| **Kosten** | Wie teuer? |
| **Qualität** | Wie fehlerfrei? |
| **Flexibilität** | Wie anpassbar? |

> **Jede Optimierung ist eine bewusste Schwerpunktsetzung.** Die Verbesserung einer Dimension verschlechtert oft eine andere („teuflischer" Trade-off).
> **Beispiele:** Automatisierung senkt Zeit + Kosten, kann aber **Flexibilität** verringern; mehr Kontrollen erhöhen **Qualität**, kosten aber **Zeit**.

🔗 *Wird in Phase 4 (Kap. 19) als Bewertungsrahmen operationalisiert.*

🧠 **Eselsbrücke:** **„ZKQF"** – **Z**eit, **K**osten, **Q**ualität, **F**lexibilität.

---

<a id="9"></a>
## 9. Durchlaufzeitanalyse & Grundbegriffe

### Grundbegriffe (Vokabeln!)

| Begriff | Definition |
|---|---|
| **Bearbeitungszeit (BZ)** | Reine Arbeitszeit an einer Aktivität |
| **Wartezeit (WZ)** | Liegezeit zwischen Aktivitäten oder vor Bearbeitung |
| **Durchlaufzeit (DLZ)** | Gesamtzeit Prozessstart → -ende = **BZ + WZ** |
| **Zykluszeit** | Zeit zwischen zwei aufeinanderfolgenden **fertigen Outputs** |
| **Durchlaufzeit­effizienz** | **= BZ / DLZ** – Anteil „wertschöpfender" Zeit |

> **Schlüsselbefund:** In **Verwaltungsprozessen dominiert die Wartezeit** – typische Effizienz **< 15 %**.
> **Beispiel:** 4 h tatsächliche Bearbeitung verteilt auf ca. 3 Wochen (≈ 120 h) → Durchlaufzeiteffizienz **≈ 3 %**.
> (Veranschaulichung: BZ ≈ 10 %, WZ ≈ 90 % der DLZ.)

### DLZ-Berechnung in BPMN-Strukturen (das Standard-Werkzeug!)

Aktivitätsangabe in Klammern = Bearbeitungs-/Aktivitätszeit. Vier Grundmuster:

**a) Sequenz** (nacheinander): **DLZ = Summe**
> A(10) → B(20) → **DLZ = 10 + 20 = 30**

**b) Alternative Pfade (XOR-Gateway):** **DLZ = A + gewichteter Mittelwert der Zweige**
> A(10) → XOR → B(20) / C(10) → XOR
> - **Gleichverteilt (50/50):** 10 + (20 + 10) / 2 = **25**
> - **Mit Wahrscheinlichkeiten (10 % B, 90 % C):** 10 + 0,1·20 + 0,9·10 = **21**

**c) Parallele Pfade (AND-Gateway):** **DLZ = A + MAXIMUM der parallelen Zweige** *(nicht Summe!)*
> A(10) → AND → B(20) ∥ C(10) → AND
> **DLZ = 10 + max(20, 10) = 10 + 20 = 30**

**d) Schleife (Rework-Loop):** **DLZ = A + (Schleifenkörper / Erfolgswahrscheinlichkeit p)**
> A(10) → B(20), B wird mit Wahrscheinlichkeit (1−p) wiederholt:
> - p = 100 % (kein Rework): 10 + 20 = **30**
> - p = 1 % (Erfolgswahrscheinlichkeit 0,01): 10 + 20 / 0,01 = **2010**
> - p = 80 % (Erfolgswahrscheinlichkeit 0,8): 10 + 20 / 0,8 = **35**

⚠️ **Häufigster Fehler:** Bei **parallelen** Pfaden das **Maximum** nehmen (nicht summieren); bei **alternativen** Pfaden den **gewichteten Durchschnitt**; bei **Schleifen** durch die **Erfolgswahrscheinlichkeit teilen** (kleine p → DLZ explodiert).

🧠 **Merke die Operatoren:** **Sequenz = +**, **Parallel (AND) = max**, **Alternativ (XOR) = gewichtetes Ø**, **Schleife = ÷ p**.

---

<a id="10"></a>
## 10. Engpassanalyse & Theory of Constraints

### Engpass (Bottleneck) – das Konzept
**Definition:** Die **Ressource, die den Gesamtdurchsatz limitiert** (z. B. Kapazität der Prüfstelle).

> **Theory of Constraints (TOC):** Optimierung eines **Nicht-Engpasses bringt nichts** – der Engpass bleibt.
> **Vorgehen (Zyklus):** Engpass **finden → erweitern → neuer Engpass entsteht → wiederholen.**

### Engpass-Indikatoren in der Praxis
- Wo **stauen** sich Vorgänge? (= **hohes WIP**) → meist **vor** dem Engpass.
- Wo ist die **Auslastung dauerhaft nahe 100 %**?
- Wo gibt es regelmäßige **Überstunden, Eskalationen**?
- Welche Stelle taucht in **Beschwerden** am häufigsten auf?
- Häufig: **zentrale Prüf- oder Genehmigungsstellen** mit begrenzter Kapazität.

🔗 *Engpässe sind die wirksamsten Optimierungsziele (Wrap-up).*

---

<a id="11"></a>
## 11. Little's Law

**John D. C. Little, 1961** – die Brücke zwischen WIP, Durchsatz und DLZ.

> ## **L = λ · W**

| Symbol | Bedeutung |
|---|---|
| **L** | Durchschnittliche Anzahl Vorgänge im System (**Work in Progress, WIP**) |
| **λ (Lambda)** | **Ankunftsrate** (Vorgänge pro Zeit) |
| **W** | Durchschnittliche **Verweilzeit** (= DLZ) |

**Beispiel:** 1.200 Anträge/Jahr, Ø 1 Monat DLZ
→ λ·W = (1200 / 12) · 1 = **100 laufende Vorgänge** (L).

> **Kernaussage:** WIP, Durchsatz und Durchlaufzeit **hängen direkt zusammen** – ändert man eines, ändern sich die anderen.

⚠️ **Einheitenfalle:** λ und W müssen **dieselbe Zeiteinheit** verwenden (im Beispiel: pro Monat → 1200/12 = 100 Anträge/Monat).

---

<a id="12"></a>
## 12. Warteschlangen & Simulation (Ausblick)

### Warteschlangentheorie (nur Konzept – Mathematik *nicht* klausurrelevant)
- Mathematische Modelle für **Ankunfts-/Bearbeitungsverteilungen**.
- Bekanntestes Modell: **M/M/1** – Poisson-Ankünfte, exponentielle Bedienzeiten, **ein** Server.
- **Auslastung ρ = λ / μ** (μ = Bedienrate).
- **Faustregel:** Bei **ρ > 0,8 explodieren die Wartezeiten**.
- **Wichtige Erkenntnis:** Kleine Auslastungserhöhung → **große** Wartezeit-Effekte (nichtlinear).

### Prozesssimulation – wann sinnvoll?
- Wenn **analytische Modelle zu komplex** werden.
- **Werkzeuge:** Camunda Process Simulator, Signavio, BIMP, Bizagi Modeler.
- **Inputs:** BPMN-Modell + Zeiten + Wahrscheinlichkeiten + Ressourcenkapazitäten.
- **Outputs:** erwartete **DLZ-Verteilung**, Auslastung, Engpass-Identifikation, **Was-wäre-wenn-Szenarien**.
- **Stärke:** macht **Trade-offs (Devil's Quadrangle) quantitativ vergleichbar**.

🔗 *Vertieft in Phase 4, Kap. 20.*

---
---

# TEIL D – PRIORISIEREN & PROBLEMREGISTER

<a id="13"></a>
## 13. Impact-Effort-Matrix (PICK)

**Frage:** Welches Problem zuerst betrachten? Achsen: **Wirkung (Impact)** ↑ vs. **Aufwand (Effort)** →.

| | **Niedriger Aufwand** | **Hoher Aufwand** |
|---|---|---|
| **Hohe Wirkung** | **IMPLEMENT** – Quick Wins, *zuerst* | **CHALLENGE** – strategisch, größeres Projekt |
| **Niedrige Wirkung** | **POSSIBLE** – bei Gelegenheit | **KILL** – verwerfen / zurückstellen |

> **PICK = P**ossible · **I**mplement · **C**hallenge · **K**ill.
> **Regel:** Zuerst **hohe Wirkung bei vertretbarem Aufwand** (Quick Wins).

🧠 **Eselsbrücke:** *„PICK" wie auswählen* – die vier Quadranten.

---

<a id="14"></a>
## 14. Pareto-Prinzip (80/20)

- **„Wenige Probleme, große Wirkung."**
- Vom **80/20-Prinzip** zur **Priorisierung der eigenen Befunde**: ca. **20 %** der Ursachen verantworten ca. **80 %** der Wirkung.
- Anwendung: Auf die **wenigen wirkungsstarken** Schwachstellen fokussieren.

---

<a id="15"></a>
## 15. Problemregister & Qualitätssicherung der Analyse

### Problemregister (konsolidiert) – das **zentrale Artefakt der Analysephase**

Struktur: **Cluster → Ursache → Wirkung → Priorität**

| Nr. | Schwachstelle (Cluster) | Hauptursache (Ishikawa / 5-Why) | Quantifizierte Wirkung | Priorität |
|---|---|---|---|---|
| P1 … P5 | … | … | … | … |

**Beleg-/Methodenkette (wichtig für „nachvollziehbar"):**
- **Belege:** Statement-IDs aus **Verschwendungs- (V-)** und **Interessengruppen-/Interview­analyse (I-)**.
- **Cluster** via **Affinitätsdiagramm (KJ-Methode)**.
- **Kodierung** im Anschluss an die **Mayring-Kategorien** (Phase 1).
- **Ursachen** aus **Ishikawa / 5-Why**.

### Qualitätssicherung der Analyse (vor dem Übergang zur Therapie)
- **Member Checking:** Cluster & Ursachen mit **Fachexpert:innen** (Sekretariat, Prüfungsamt, Betreuer:innen) rückkoppeln/bestätigen.
- **Konsistenzprüfung:** Befundlage (IDs), Clusterbildung, Priorisierung müssen **widerspruchsfrei** zusammenpassen.
- **Rückbindung ans IST-Modell:** jede Schwachstelle stützt sich auf **BPMN-Belegstellen** + Erhebungsdaten → keine freischwebenden Behauptungen.
- **Vollständigkeit:** keine priorisierte Schwachstelle **ohne zugeordnete Ursache**.
- **Ergebnis:** ein **abgesichertes Problemregister** als belastbarer Input für die **Redesign-Phase**.

🔗 *Output dieser Phase = „Issue-Register", Input für Phase 4.*

---
---

# TEIL E – PHASE 4: PROCESS REDESIGN

<a id="16"></a>
## 16. Einordnung, Begriff & Lernziele

### Einordnung im BPM-Lebenszyklus
**Identification → Discovery → Analysis → ★Redesign★ → Implementation → Monitoring**
- **Ausgangspunkt:** Identification/Discovery/Analysis liefern ein **priorisiertes, quantifiziertes Bild** der Schwachstellen (**Issue-Register**).
- **Aufgabe des Redesigns:** Aus den Befunden ein begründetes **To-be-Modell** ableiten und seine **erwartete Wirkung ex ante** abschätzen, **bevor** implementiert wird.

### Was ist Process Redesign?
**Begriff:** Systematische **(Um-)Gestaltung** eines Prozesses vom **Ist (As-is)** zum **Soll (To-be)**. Ziel: Verbesserung entlang **Zeit, Kosten, Qualität, Flexibilität** bei **tragbaren Trade-offs**.

| | Definition |
|---|---|
| **Analyse** | versteht & quantifiziert Schwachstellen (**Diagnose**) |
| **Redesign** | entwirft die **Lösung** (Therapie) und schätzt deren **Wirkung** |

> **Häufiges Leitprinzip:** standardisierbare, **transaktionale** Prozessteile **straffen/automatisieren**; **wissensintensive** Teile **gestaltungsoffen** lassen.

### Lernziele Phase 4
1. Übergang Analyse → Redesign erklären; **Analyse vs. Redesign** abgrenzen.
2. **Devil's Quadrangle** als Bewertungsrahmen anwenden, je Dimension **messbar operationalisieren**.
3. Redesign-Ansätze einordnen (inkrementell vs. radikal; analytisch vs. kreativ – **Redesign Orbit**).
4. **Heuristik-Katalog (Reijers & Mansar)** kennen und **gezielt** auswählen.
5. Erwartete Wirkung **ex ante per Simulation** abschätzen und das Verfahren erklären.
6. Methoden selbstständig anwenden.

### Methoden dieser Phase (Überblick)
1. **Redesign-Heuristiken / Best Practices** (Reijers & Mansar) – begründete Gestaltungsregeln.
2. **Devil's Quadrangle (operationalisiert)** – Varianten anhand messbarer Kennzahlen vergleichen.
3. **Geschäftsprozess-Simulation** – erwartete Wirkung **ex ante** abschätzen (ohne Live-Betrieb).

---

<a id="17"></a>
## 17. Zwei Grundhaltungen: inkrementell vs. radikal

| | **Inkrementell / kontinuierlich** | **Radikal (BPR)** |
|---|---|---|
| **Ansätze** | Kaizen, Lean, **Six Sigma (DMAIC)** – viele kleine, risikoarme Verbesserungen am bestehenden Prozess | **Business Process Reengineering** – fundamentales **Neudenken** |
| **Quellen** | – | Hammer 1990; Hammer & Champy 1993; Davenport 1993 |
| **+ Vorteile** | geringes Risiko, hohe Akzeptanz, schnell wirksam | große **Wirkungssprünge** möglich |
| **− Nachteile** | begrenzte Sprunghöhe; löst **strukturelle** Probleme oft nicht | hohes Umsetzungs-/Change-Risiko, ressourcenintensiv |

> **Redesign Orbit:** verortet Ansätze von **inkrementell-analytisch** bis **radikal-kreativ**.

🧠 **Merke:** *Inkrementell = viele kleine Schritte (sicher, flach). Radikal = ein großer Sprung (riskant, hoch).*

---

<a id="18"></a>
## 18. Methode 1: Redesign-Heuristiken / Best Practices

### Methoden-Steckbrief
- **Zweck:** Strukturierte, **erfahrungs- und literaturbasierte** Gestaltungsregeln statt Einzelideen – jede Maßnahme **begründbar**.
- **Vorgehen:** Passende Best Practices **je Schwachstelle** auswählen → Wirkung im **Devil's Quadrangle** bewerten → an Kennzahlen (**PPI**) koppeln.
- **Umfang:** **~29 Best Practices in 7 Kategorien** (Reijers & Mansar): **Kunden, Operation, Verhalten, Organisation, Information, Technologie, Umwelt**.
- **Grenzen:** erfahrungsgeleitete Auswahl; **keine Garantie** tatsächlicher Verbesserung → Wirkung muss **abgeschätzt** werden.
- **Quelle:** Reijers & Mansar (2005), *Omega* 33(4); Dumas et al. (2018), Kap. 8.

🧠 **Eselsbrücke 7 Kategorien:** **„K-O-V-O-I-T-U"** = **K**unden, **O**peration, **V**erhalten, **O**rganisation, **I**nformation, **T**echnologie, **U**mwelt.

### Wichtigste Heuristiken mit Beispielen

| Heuristik | Kategorie | Inhalt | Beispiel |
|---|---|---|---|
| **Task elimination** | OPERATION | Überflüssige, nicht-wertschöpfende Aufgaben (oft Kontrollen) **ersatzlos streichen** | Zweite Unterschrift, die nie zu Ablehnung führte, abschaffen |
| **Knock-out (+ Resequencing)** | VERHALTEN | Prüfungen nach **Aufwand & Ablehnwahrscheinlichkeit** ordnen – billige, häufig ablehnende Checks **zuerst** | Erst schnelle Berechtigungsprüfung, dann aufwändige Detailbewertung |
| **Parallelism** | VERHALTEN | Unabhängige Aufgaben **gleichzeitig** statt nacheinander | Onboarding: IT-Einrichtung & Vertragsprüfung parallel |
| **Triage / Case types** | OPERATION | Fälle **nach Typ trennen**, je Typ passender Weg | Helpdesk: Standard → Self-Service, komplex → Spezialist:innen |
| **Task automation / Integral technology** | TECHNOLOGIE | Aufgaben automatisieren, **Medienbrüche beseitigen** | Rechnungen per Texterkennung auslesen statt abtippen |
| **Integration / Contact reduction** | KUNDEN | Kund:innen/Partner einbinden, Kontaktzahl senken | Adressänderung selbst im Portal |
| **Control addition / relocation** | INFORMATION & KUNDEN | Prüfungen **ergänzen oder an die Quelle verlagern** | Pflichtfelder mit Plausibilitätsprüfung bei Online-Eingabe |
| **Buffering** | INFORMATION | Information **einmal vorhalten** statt je Vorgang neu anfragen | Lieferanten-Stammdaten einmal speichern, wiederverwenden |
| **Empower** | ORGANISATION | Entscheidungsbefugnis erweitern, **Genehmigungsschleifen** reduzieren | Kulanz-Erstattung bis 100 € selbst freigeben |
| **Case manager / Numerical involvement** | ORGANISATION | **Eine verantwortliche Person je Fall**, weniger Übergaben | Ein:e Sachbearbeiter:in begleitet Antrag von Anfang bis Ende |

### Weitere Heuristiken (kompakt)
- **Task composition** (OPERATION) – Aufgaben zusammenfassen / große aufteilen.
- **Case-based work** (OPERATION) – Batch/Periodizität entfernen, **fallweise** statt gebündelt.
- **Exception** (VERHALTEN) – Ausnahmen **separat** behandeln, Hauptpfad nicht überladen.
- **Case assignment** (ORGANISATION) – eine Bearbeiter:in möglichst viele Schritte eines Falls.
- **Customer teams** (ORGANISATION) – feste, **abteilungsübergreifende** Teams für Fallarten.
- **Flexible assignment / Centralization** (ORGANISATION) – Ressourcen flexibel bzw. zentral zuordnen.
- **Split responsibilities** (ORGANISATION) – **geteilte** Zuständigkeiten vermeiden.
- **Extra resources / Specialist-generalist** (ORGANISATION) – Kapazität erhöhen bzw. spezialisieren/generalisieren.
- **Trusted party / Outsourcing / Interfacing** (UMWELT) – Dritten vertrauen, auslagern, Standardschnittstellen.

⚠️ **Verwechslungsgefahr:** *Knock-out* (Reihenfolge der Prüfungen optimieren) ≠ *Task elimination* (Aufgabe komplett streichen). *Empower* (mehr Befugnis, weniger Schleifen) ≠ *Case manager* (eine Person je Fall).

---

<a id="19"></a>
## 19. Methode 2: Devil's Quadrangle operationalisieren

> **Statt Bauchgefühl (+/−):** Je Dimension **eine messbare Kennzahl** definieren und pro Variante **berechnen/schätzen**.

| Dimension | Messbare Kennzahl | Schätzung aus |
|---|---|---|
| **Zeit** | Durchlaufzeit/Wartezeit, % fristgerecht | Durchlaufzeitanalyse, Simulation, **Little's Law** |
| **Kosten** | Kosten/Fall = **Σ(Zeit × Kostensatz) + Nacharbeit** | Aktivitätskostenrechnung, Simulation |
| **Qualität** | Fehler-/Rücklaufquote, **First-Pass-Yield** | Prozessdaten, Stichprobe |
| **Flexibilität** | # unterstützte Varianten, Anpassungszeit (Proxy) | Modellanalyse, Experten (dokumentiert) |

**Gegen Subjektivität:** Kennwerte aus **Analyse/Simulation** statt Meinung. Falls bewertet wird → **gewichtetes Scoring (MCDA)** mit definierten **Skalen-Ankern**, **mehreren Bewertenden (Inter-Rater)** und **Sensitivitätsanalyse** der Gewichte.

### Durchgerechnetes Beispiel – Bestellfreigabe (Beschaffung)
*Variante: Bestellungen < 1.000 € automatisch freigeben (Regel) + Stichprobenkontrolle statt zwei manueller Freigaben.*

| Dimension | Kennzahl | Ist | Variante |
|---|---|---|---|
| Zeit | Durchlaufzeit | 3 Tage | **0,5 Tage** |
| Kosten | je Vorgang | 18 € | **8 €** |
| Qualität | Fehlerquote freigegeben | 2 % | 3 % |
| Flexibilität | Sonderfälle abbildbar | hoch | mittel |

> **Trade-off:** **Tempo & Kosten gewonnen**, **Qualität & Flexibilität leicht verloren** – der typische Vierfach-Konflikt.
> *Darstellung als Netzdiagramm, Skala 0–10, „außen = besser".*

🔗 *Siehe auch: Kap. 8 (Konzept), Kap. 22 (Fallstudie A vs. B).*

---

<a id="20"></a>
## 20. Methode 3: Geschäftsprozess-Simulation (Ex-ante-Wirkung)

### Methoden-Steckbrief
- **Zweck:** Wirkung des To-be **ohne Live-Betrieb** abschätzen – wenn **keine Nachher-Daten** vorliegen.
- **Ergebnis:** **Verteilungen statt Einzelwerte** (Durchlaufzeit, Wartezeit, Auslastung, Kosten, Durchsatz) – **mit Konfidenz**.
- **Voraussetzung:** Prozessmodell + geschätzte **Eingangsverteilungen** (Ankunft, Bearbeitungszeiten, Verzweigungen, Ressourcen).
- **Grenzen:** **Ergebnis nur so gut wie die Annahmen**; reale Feldwirkung bleibt zu **validieren (Future Work)**.
- **Quelle:** van der Aalst (2015); Law (2015); Dumas et al. (2018), Kap. 8.

### Warum simulieren? Der Stau-Effekt
> **Mittelwerte täuschen** – Wartezeiten wachsen **nahe 100 % Auslastung überproportional**.

**Mini-Beispiel:** 1 Person, Tickets ø 6/h, ø 8 Min/Ticket.
- Auslastung = 6 × 8 Min = 48 Min/h → **80 %**.
- **Überraschung:** schon bei 80 % wartet ein Ticket ø **~32 Min** – obwohl scheinbar „noch Luft". Bei **95 %** sind es **> 2 Stunden**.
- **Warum?** Wartezeit wächst **nicht linear**, sondern **explodiert** nahe 100 % (Warteschlangen-Effekt).

### Output: Verteilungen statt Einzelwerte
- Nicht nur Mittelwert zählt, sondern die **ganze Verteilung** – inkl. **langer Schwanz** (lange Fälle).
- Beispiel: As-is ø ~6 h, aber ~25 % der Fälle > 8 h. To-be ø ~3 h, 90 % unter 5 h, kaum Ausreißer.
- Simulation liefert **Verteilung + Konfidenzintervall** → auch das **Risiko langer Fälle**.

### Wie funktioniert sie? (Discrete-Event-Simulation, DES)
**Modellbausteine (Eingaben):**
- **Ankunftsprozess** – Zwischenankunftszeiten der Fälle.
- **Bearbeitungszeiten** je Aktivität als **Verteilung**.
- **Verzweigungen** mit Wahrscheinlichkeiten an Gateways.
- **Ressourcen** (Rollen, Anzahl, Verfügbarkeit) + Warteschlangen.

**Mechanismus & Ergebnis:**
- Viele Fälle fließen über eine **simulierte Uhr**; **Ereignisse** (Ankunft, Start/Ende) treiben die Zeit voran.
- Fälle **warten** auf belegte Ressourcen → hier entstehen **Wartezeiten & Engpässe**.
- Zeiten aus Verteilungen **gezogen**; **viele Replikationen** → Mittelwerte **mit Konfidenzintervall**.
- **Ausgaben:** Durchlaufzeit, Wartezeit, Auslastung, Kosten, Durchsatz.

### Vorgehen (5 Schritte)
1. **Modell ableiten** (aus To-be-Modell)
2. **Eingaben schätzen** (Verteilungen aus Daten/Experten)
3. **Verifizieren** (Logik korrekt abgebildet?)
4. **Validieren/Kalibrieren** (gegen **Ist-Kennzahlen** abgleichen)
5. **Experimente** (As-is vs. To-be, Replikationen, Sensitivität)

### Monte-Carlo vs. DES (oft geprüfter Unterschied!)

| | **Monte-Carlo** | **Volle DES** |
|---|---|---|
| Summiert | Segment-Verteilungen (viele Ziehungen) | + Warteschlangen & Kapazitäten |
| Ressourcen­konkurrenz | **ohne** | **mit** |
| Eignung | schnell, **reine Durchlaufzeit** | zeigt **Engpässe unter Last** |

### Werkzeuge
- **BPM-Tools mit Simulation:** **SAP Signavio Process Manager** (BPMN-2.0, Modi: Step-by-step, One-case, Multiple-case; Inputs: Fallzahl/Ankunft, Bearbeitungszeiten, Ressourcen + Kosten, Verzweigungs-W.; Output: Zeit, Kosten, Engpässe). Weitere: **Bizagi Modeler, Camunda, ARIS** (token-/Monte-Carlo-basiert).
- **Spezialisierte DES-Tools:** **Arena, AnyLogic, SimPy (Python)** – feinkörnige Warteschlangen, Ressourcenkonkurrenz, komplexe Regeln (mehr Aufwand, mehr Tiefe).
- **Einordnung:** BPM-Tools genügen für **Lehre & die meisten Redesign-Vergleiche**; spezialisierte DES-Tools lohnen bei **hoher Last-/Ressourcendynamik**.

🧠 **Merke:** *Monte-Carlo = würfeln & addieren (ohne Stau). DES = simulierte Uhr mit Warteschlangen (mit Stau).*

---

<a id="21"></a>
## 21. Redesign-Vorgehen & Qualitätssicherung

### Vorgehen Schritt für Schritt
1. **Verbesserungspotenziale** – aus dem priorisierten **Issue-Register**.
2. **Varianten generieren** – mit **Heuristiken**, **mehrere** Optionen.
3. **Bewerten** – **Devil's Quadrangle + Simulation**.
4. **Auswählen** – kriterienbasiert, unter **Restriktionen**.
5. **Dokumentieren** – **Befund → Heuristik → Entscheidung**.

### Qualitätssicherung im Redesign
- **Ableitung nachvollziehbar:** je Designentscheidung **Befund + Heuristik** dokumentieren.
- To-be auf **Soundness & Compliance** prüfen (keine **Deadlocks**; rechtliche Vorgaben einhalten).
- **Mehrere Varianten** kriterienbasiert vergleichen (nicht die erstbeste Idee umsetzen).
- Wirkung **ex ante mit Unsicherheit** berichten; Feldwirkung als **Future Work** kennzeichnen.
- **Stakeholder-Review** der To-be-Varianten.

### Zusammenfassung Phase 4
- Redesign überführt diagnostizierte Schwachstellen in ein **begründetes To-be-Modell**.
- **Devil's Quadrangle** macht Trade-offs sichtbar – **operationalisiert** über messbare Kennzahlen.
- **Redesign Orbit** verortet Ansätze (inkrementell-analytisch ↔ radikal-kreativ).
- **Heuristik-Katalog (Reijers & Mansar)** = systematisches Repertoire – **gezielt, nicht beliebig**.
- **Simulation** schätzt Wirkung **ex ante** (z. B. SAP Signavio).

---

<a id="22"></a>
## 22. Fallstudie: Regio Versicherung AG (Schadensregulierung)

**Ausgangslage:** Kfz-Kleinschäden (< 2.500 €). Kund:innen klagen über lange Bearbeitung. Management-Ziel: **DLZ < 5 Arbeitstage – ohne Mehrkosten**. Identification/Discovery/Analysis sind abgeschlossen; Aufgabe = **Phase 4 Redesign**.

**Ist-Kennzahlen:**

| Kennzahl | Wert |
|---|---|
| Durchlaufzeit Ø | **12 AT** (Ziel < 5) |
| fristgerecht (< 5 AT) | **18 %** |
| Kosten je Fall | **95 €** |
| Fallvolumen | **200/Woche** |

### Befunde → passende Heuristik (Schritt 1)
| Befund | Heuristik |
|---|---|
| **B1:** ~40 % der Meldungen **unvollständig** → ständige Rückfragen | **Control addition** (Pflichtfelder/Validierung an der Quelle) |
| **B5:** Deckungsprüfung (lehnt 12 % ab) läuft **erst NACH** der aufwändigen Schadenbewertung | **Knock-out / Resequencing** (billige, ablehnende Prüfung zuerst) |
| **B3:** Auch Kleinstschäden < 500 € brauchen **Teamleitungs-Freigabe** → Engpass | **Empower** (Freigabe-Befugnis erweitern) |

### Zwei To-be-Varianten (Schritt 2)
**Variante A – inkrementell**
- Validierte Online-Schadenmeldung (Pflichtfelder)
- Kleinstschäden < 500 € **ohne** Teamleitungs-Freigabe
- Deckungsprüfung **VOR** der Schadenbewertung

**Variante B – weitergehend** (= alles aus A, plus)
- **Dunkelverarbeitung < 500 €** (automatische Auszahlung)
- **Statusportal** für Kund:innen
- **Parallele** Deckungs- und Schadenprüfung

### Simulationsergebnis (Schritt 3, 5.000 Fälle, 10 Replikationen)

| Kennzahl | As-is | Variante A | Variante B |
|---|---|---|---|
| Durchlaufzeit Ø (AT) | 12,0 | 6,5 | **2,8** |
| Wartezeit Ø (AT) | 8,5 | 3,8 | **1,2** |
| Auslastung Sachbearb. | 92 % | 78 % | **61 %** |
| Kosten je Fall (€) | 95 | 68 | **47** |
| Anteil < 5 AT | 18 % | 64 % | **89 %** |

→ **Nur Variante B erreicht das Ziel < 5 AT** (89 % fristgerecht) **und senkt zugleich die Kosten**.

### Empfehlung unter Restriktionen (Schritt 4)
**Restriktionen:** begrenztes IT-Budget · Umsetzung in 6 Monaten möglich · **veränderungsmüde Belegschaft**.
→ Abwägung B (beste Kennzahlen, aber IT-/Change-Aufwand) vs. A vs. **Hybrid**.

⚠️ **Q11 – Welche wichtige Dimension bildet das Devil's Quadrangle NICHT ab?**
**Antwort:** z. B. **Mitarbeiter-Akzeptanz / Change-Aufwand / Risiko / strategischer Fit** – das Quadrangle deckt nur **Zeit, Kosten, Qualität, Flexibilität** ab, nicht die **menschlich-organisatorische** Dimension. *(Brücke zu Phase 5!)*

---
---

# TEIL F – PHASE 5: PROCESS IMPLEMENTATION

<a id="23"></a>
## 23. Begriff & die zwei Stränge

### Einordnung
**… → Redesign → ★Implementation★ → Monitoring**
- **Ausgangspunkt:** Redesign hat ein begründetes To-be-Modell + Ex-ante-Wirkung geliefert.
- **Aufgabe:** den entworfenen Prozess in die **organisatorische und technische Realität** überführen – so, dass er **tatsächlich gelebt** wird.

### Begriff
**Process Implementation** = Überführung des To-be-Prozesses in den **produktiven Betrieb**.
> **Erfolgreich erst, wenn der neue Prozess tatsächlich und dauerhaft gelebt wird – NICHT schon, wenn das System läuft.**

### Die zwei untrennbaren Stränge (nach Dumas et al.)

| **Mensch & Organisation** | **System & Technik** |
|---|---|
| Stakeholder einbinden | Konfiguration / Entwicklung |
| Kommunikation & Vision | Datenmigration |
| Schulung / Training | Integration in IT-Landschaft |
| Change-Management | Test & Abnahme (**UAT**) |
| neue Rollen & Verantwortung | Rollout / Go-live |

> **Beide Stränge greifen ineinander – Technik ohne Akzeptanz scheitert.**

### Lernziele Phase 5
1. Zwei Stränge (Organisation + System) abgrenzen.
2. **Rollout-Strategien** (Big-Bang, Pilot/phasenweise, Parallelbetrieb) kennen & situativ wählen.
3. Rolle von **Test & Abnahme (UAT)** erklären.
4. **Change-Management-Modelle** (Lewin, Kotter, ADKAR) anwenden.
5. **Widerstände** erkennen & begegnen.

---

<a id="24"></a>
## 24. Vom Modell zum ausführbaren Prozess (Strang System & Technik)

> Das **fachliche** To-be-Modell ist **noch nicht ausführbar**. Für die Automatisierung in einem **BPMS** muss es technisch **angereichert** werden.

1. **Prozessmodell verfeinern** – Granularität erhöhen, technische Schritte + **Ausnahme-/Fehlerpfade** ergänzen.
2. **Daten & Formulare** – Datenobjekte, Variablen, Eingabemasken je Aktivität festlegen.
3. **Aufgaben zuordnen** – **User-Tasks (Mensch)** von **Service-Tasks (System)** trennen; Rollen & Arbeitslisten.
4. **Services anbinden** – Skripte, APIs, Systemaufrufe für automatisierte Schritte.

> **Ergebnis:** ein in der **Process-Engine (BPMS)** ausführbares Prozessmodell. *(Quelle: Dumas et al. 2018, Process Automation.)*

⚠️ **Begriff:** **User-Task** = vom Menschen ausgeführt; **Service-Task** = vom System automatisiert.

---

<a id="25"></a>
## 25. Rollout-Strategien

| Strategie | Vorgehen | Stärken | Risiken / Aufwand |
|---|---|---|---|
| **Big-Bang** | Umstellung aller Beteiligten zu **einem Stichtag** | schnell, klarer Schnitt, **kein Doppelbetrieb** | **hohes Risiko**, Rückfall schwer |
| **Pilot / phasenweise** | Start mit **Teilbereich**, dann ausrollen | **Lernen am kleinen Fall**, Risiko begrenzt | länger, Übergangszustände managen |
| **Parallelbetrieb** | alt + neu laufen **eine Zeit lang parallel** | **sicher**, direkter Vergleich möglich | **doppelte Last, teuer** |

> **Auswahl hängt ab von:** Risikotoleranz · Prozesskritikalität · Ressourcen · **Reversibilität**.

**Abwägungsdimensionen (Mini-Szenario):** **Risiko** (was geht schief?) · **Kosten/Aufwand** · **Lerneffekt** (vorher am kleinen Fall lernen?).

🧠 **Merke:** *Big-Bang = schnell & riskant · Pilot = lernend & langsam · Parallel = sicher & teuer.*

---

<a id="26"></a>
## 26. Test & Abnahme / UAT

### Teststufen (bauen aufeinander auf)
1. **Komponententest** – Einzelne Schritte/Funktionen korrekt?
2. **Integrationstest** – Schnittstellen & Datenfluss korrekt?
3. **User Acceptance Test (UAT)** – fachlich abgenommen durch **Nutzer**?
4. **Pilot / Probebetrieb** – funktioniert es unter **realen Bedingungen**?

### Fokus: User Acceptance Test (UAT)
**Definition:** Die fachliche Abnahme vor dem Go-live – **künftige Nutzer** prüfen anhand **realistischer Fälle**, ob der Prozess ihre Anforderungen erfüllt. **Abnahme = Voraussetzung für Go-live** und schafft zugleich **Akzeptanz**.

**Ablauf:** Testfälle ableiten → Umgebung & Daten → Nutzer testen → Fehler beheben → **Abnahme / Sign-off**.

**Akzeptanzkriterien:**
- **vorab festgelegt, messbar, fachlich** – aus **Nutzersicht**.
- decken **Normal- UND wichtige Sonderfälle** ab.
- erfüllt = **formale Freigabe (Sign-off)** für den Go-live.

**Abgrenzung & Rollen:**
- **Technische Tests (IT):** *funktioniert das System?*
- **UAT (Fachbereich / Key-User):** *erfüllt der Prozess die Anforderungen?*
- **Prozessverantwortliche** geben formal frei.

> **Brücke zum Change-Management:** Wer **früh testet, beteiligt sich** – das schafft **Akzeptanz und Befähigung schon vor dem Go-live**.

**Zuordnungsübungen (häufiger Klausurtyp):**
- *„Schnittstelle bricht im Test wiederholt ab"* → **Integrationstest**.
- *„Nutzer laden falsche Dokumente hoch"* → **UAT** (fachlicher Befund aus Nutzersicht).

---

<a id="27"></a>
## 27. Change-Management: Lewin, Kotter, ADKAR

### Warum es entscheidet
- **Problem:** Prozessänderungen ändern **Gewohnheiten, Rollen, Macht** → Menschen reagieren mit **Unsicherheit & Widerstand** – selbst auf objektiv bessere Prozesse.
- **Folge:** ein technisch perfekter Prozess wird **umgangen, nur halb genutzt oder unterlaufen**.
- **Antwort:** Change-Management steuert den Übergang **systematisch**: beteiligen · Sinn vermitteln · befähigen · Erfolge sichtbar machen · verankern.

### Modell 1 – Lewin: 3 Phasen (Grundlogik, 1947)

| Phase | Deutsch | Inhalt |
|---|---|---|
| **Unfreeze** | Auftauen | Veränderungsbereitschaft schaffen – Dringlichkeit & Sinn vermitteln, Sicherheit geben |
| **Change** | Verändern | Neue Prozesse, Rollen, Verhaltensweisen einführen, begleiten, einüben |
| **Refreeze** | Einfrieren | Das Neue **stabilisieren & verankern** → kein Rückfall |

⚠️ **Klassische Diagnose:** „Ab Montag arbeiten alle mit dem neuen System" – ohne Erklärung/Einbindung → **Unfreeze übersprungen** → Folge: Widerstand, fehlende Bereitschaft, Umgehung.

### Modell 2 – Kotter: 8-Stufen-Modell (1996, *Leading Change*)
„Wandel als Treppe", **3 Phasen**:

**Phase 1 – Klima für Wandel schaffen:** 1) Dringlichkeit erzeugen · 2) Führungskoalition · 3) Vision & Strategie · 4) Vision vermitteln
**Phase 2 – Organisation befähigen:** 5) Hindernisse beseitigen · 6) Schnelle Erfolge (Quick Wins)
**Phase 3 – Wandel verankern:** 7) Erfolge ausbauen · 8) Kultur verankern

⚠️ **Diagnose:** „Zwei Wochen nach Einführung Rückfall auf alte Routinen, Begeisterung verflogen" → **Stufen 7–8 vernachlässigt** (Erfolge ausbauen & **in der Kultur verankern**); ggf. fehlende **Quick Wins (6)**.

### Modell 3 – ADKAR (Hiatt 2006, Prosci) – individuelle Ebene (bottom-up)
Fünf **aufeinander aufbauende** Bausteine:

| | Baustein | Bedeutung |
|---|---|---|
| **A** | **Awareness** | Bewusstsein für die **Notwendigkeit** der Veränderung |
| **D** | **Desire** | Wille & Bereitschaft, **mitzutragen** |
| **K** | **Knowledge** | **Wissen, wie** verändert wird (Schulung, Information) |
| **A** | **Ability** | **Fähigkeit**, das Neue tatsächlich anzuwenden |
| **R** | **Reinforcement** | **Verstärkung**, damit es nicht zurückfällt |

⚠️ **Diagnose (Klausurtyp):**
- *„Das bringt nichts – wir haben es immer anders gemacht"* → fehlt **Awareness/Desire** (Sinn vermitteln, beteiligen).
- *„Ich kann die neue Software einfach nicht bedienen"* → fehlt **Ability** (Schulung, Übung am echten System, Begleitung).

🧠 **Eselsbrücke ADKAR:** **A-D-K-A-R** = *Erst wissen WARUM (Awareness), dann WOLLEN (Desire), dann WISSEN WIE (Knowledge), dann KÖNNEN (Ability), dann DRANBLEIBEN (Reinforcement).*

### Modell-Vergleich (oft geprüft)
| Modell | Ebene / Fokus | Stärke |
|---|---|---|
| **Lewin** | grobe **Grundlogik** | einfaches 3-Phasen-Gerüst |
| **Kotter** | **Führung / Organisation** | konkrete 8-Schritte-Roadmap |
| **ADKAR** | **Individuum** (bottom-up) | Diagnose, *wo beim Einzelnen* es hakt |

---

<a id="28"></a>
## 28. Widerstände, Kommunikation & Erfolgsfaktoren

### Widerstände erkennen und begegnen

| Ursache / Symptom | Mögliche Maßnahme |
|---|---|
| Angst vor Verlust (Status, Kompetenz) | frühzeitig einbinden, Perspektiven aufzeigen |
| Unklarheit über Sinn / Nutzen | Vision klar & **wiederholt** kommunizieren |
| Fehlende Fähigkeiten / Unsicherheit | Schulung, Begleitung, Anlaufstelle |
| Kein sichtbarer Fortschritt | **kurzfristige Erfolge** sichtbar machen |
| Gefühl der Fremdbestimmung | **Beteiligung, Mitgestaltung** ermöglichen |

> **Merksatz: Widerstand ist Information** – er zeigt, wo **Sinn, Befähigung oder Beteiligung** fehlen.

### Kommunikation & Befähigung
- **Kommunikation:** frühzeitig, ehrlich, **wiederholt**, zielgruppengerecht. **Das Warum vor dem Was.** **Zweiweg-Kommunikation** (zuhören, Betroffene zu Beteiligten machen).
- **Schulung & Befähigung:** **rollenbezogen** und **nah am Go-live** (nicht zu früh!). Mischung aus Anleitung, **Übung am echten System** und Begleitung danach (Key-User, Support, Materialien).
- **Ziel:** **Ability** im Sinne von ADKAR – Menschen können das Neue **wirklich anwenden**.

### Einführung – Vorgehen Schritt für Schritt
1. **Planen** – Rollout-Strategie, Zeitplan, Verantwortliche
2. **Vorbereiten** – System konfigurieren, Daten migrieren
3. **Testen & Abnehmen** – Integration, UAT, Pilot
4. **Befähigen** – kommunizieren, schulen, begleiten
5. **Go-live** – umstellen, stabilisieren, verankern

> **Parallel über alle Schritte:** Change-Management – **Kommunikation & Beteiligung beginnen ab Schritt 1**, nicht erst beim Go-live.

### Erfolgsfaktoren ✓ vs. Stolpersteine ✗

| ✓ **Erfolgsfaktoren** | ✗ **Stolpersteine** |
|---|---|
| sichtbare Unterstützung der Leitung | Fokus nur auf Technik, nicht auf Menschen |
| frühe & ehrliche Kommunikation | zu späte oder einseitige Kommunikation |
| Beteiligung der Betroffenen | Schulung zu früh oder zu knapp |
| rechtzeitige, praxisnahe Schulung | Widerstand ignorieren statt nutzen |
| kurzfristige Erfolge sichtbar machen | kein Verankern → Rückfall ins Alte |
| Test/UAT vor dem Go-live | Go-live ohne ausreichenden Test |

### Zusammenfassung Phase 5
- Implementation hat **zwei untrennbare Stränge:** System + Mensch.
- **Rollout-Strategien** unterscheiden sich in **Risiko & Aufwand** – situativ wählen.
- **Test & Abnahme (UAT)** sichern Go-live fachlich + technisch ab.
- **Change-Management entscheidet:** Lewin (Grundlogik), Kotter (Führung), ADKAR (Individuum).
- **Widerstand ist Information** – Kommunikation, Beteiligung, Befähigung sind die Hebel.

---
---

<a id="top10"></a>
# ⭐ Top-10-Konzepte für Schnelllerner

1. **Diagnose vor Therapie** – erst qualitativ (WSA, Verschwendung, Ishikawa, 5-Why) Hot Spots finden, dann quantitativ priorisieren.
2. **WSA-Dreiteilung WS/GWS/NWS** – Ziel: NWS minimieren, GWS hinterfragen, WS schützen. Drei Leitfragen.
3. **7 Arten der Verschwendung** (Transport, Bewegung, Bestände, Wartezeit, Fehler, Mehraufwand, Überproduktion). „Verschwendung ist Ergebnis, nicht Ursache."
4. **Auswirkung → Problem → Ursache** + **Ishikawa (breit, 6 M) vs. 5-Why (tief)** – kombinieren.
5. **DLZ-Berechnung in BPMN:** Sequenz = +, Parallel(AND) = **max**, Alternativ(XOR) = gewichtetes Ø, Schleife = **÷ Erfolgs-W.**
6. **Little's Law: L = λ · W** (WIP = Ankunftsrate × Verweilzeit).
7. **Engpass / Theory of Constraints** – nur der Engpass limitiert den Durchsatz; finden → erweitern → wiederholen.
8. **Devil's Quadrangle (Zeit, Kosten, Qualität, Flexibilität)** – Trade-offs; **operationalisieren** mit messbaren Kennzahlen.
9. **Reijers & Mansar Heuristiken** (~29 in 7 Kategorien) + **Simulation** (DES vs. Monte-Carlo) zur Ex-ante-Bewertung.
10. **Change-Management (Lewin / Kotter / ADKAR)** + **UAT** + **Rollout-Strategien** – Technik ohne Akzeptanz scheitert.

---

<a id="klausur"></a>
# 📝 Typische Klausurfragen (ableitbar)

**Berechnungen**
1. Berechne die DLZ für eine gegebene BPMN-Struktur mit Sequenz / XOR (mit %) / AND / Schleife. *(Achte: AND = max, Schleife = ÷ p.)*
2. Wende **Little's Law** an: gegeben λ und W → berechne L (Einheiten angleichen!).
3. Berechne **Durchlaufzeiteffizienz = BZ/DLZ** und interpretiere (typisch < 15 % in Verwaltung).
4. **Auslastung** ρ = λ/μ berechnen und erklären, warum ab ρ > 0,8 Wartezeiten explodieren.

**Zuordnung / Klassifikation**
5. Ordne Prozessschritte **WS / GWS / NWS** zu (mit Begründung über die 3 Leitfragen).
6. Ordne Phänomene den **7 Verschwendungsarten** zu.
7. Ordne Befunde passenden **Reijers-&-Mansar-Heuristiken** zu (vgl. Fallstudie B1/B3/B5).
8. Ordne Testbefunde der richtigen **Teststufe** zu (Komponenten/Integration/UAT/Pilot).
9. Diagnostiziere fehlenden **ADKAR-Baustein** bzw. übersprungene **Lewin-Phase** / vernachlässigte **Kotter-Stufe**.

**Erklären / Abgrenzen**
10. **Ishikawa vs. 5-Why** – wann was, wie kombinieren?
11. **Analyse vs. Redesign** abgrenzen (Diagnose vs. Therapie).
12. **Inkrementell vs. radikal (BPR)** – Vor-/Nachteile.
13. **Monte-Carlo vs. DES** – Unterschied erklären.
14. **Devil's Quadrangle** an einer Variante anwenden + Trade-off benennen; *welche Dimension bildet es NICHT ab?*
15. **Rollout-Strategien** situativ wählen + begründen (Risiko/Kosten/Lerneffekt).
16. Warum ist Implementation erst bei **gelebtem** Prozess erfolgreich (nicht beim laufenden System)?

**Konzeptbeschreibung**
17. **Interessengruppenanalyse** – Idee + 5 Schritte.
18. **Problemregister** – Aufbau (Cluster→Ursache→Wirkung→Priorität) + Methodenkette (KJ/Mayring/V-/I-).
19. **Impact-Effort-Matrix (PICK)** + **Pareto** – Priorisierung erklären.
20. **UAT** – Zweck, Akzeptanzkriterien, Rollenabgrenzung IT vs. Fachbereich.

---

<a id="zusammenhaenge"></a>
# 🔗 Häufig geprüfte Zusammenhänge

- **WSA ↔ Verschwendung:** WSA = Denkbrille; 7 Arten = konkretes Werkzeug (NWS sichtbar machen).
- **Ishikawa ↔ 5-Why:** erst breit (alle 6 M), dann tief pro Hauptast.
- **Little's Law ↔ Engpass ↔ WIP:** hohes WIP staut sich **vor** dem Engpass; L = λ·W verbindet WIP, Durchsatz, DLZ.
- **Devil's Quadrangle ↔ Simulation ↔ Heuristiken:** Heuristik erzeugt Variante → Simulation/Kennzahlen füllen Quadrangle → Vergleich der Varianten.
- **Analyse-Phase ↔ Redesign:** Problemregister/Issue-Register ist der **Input** für Redesign.
- **UAT ↔ Change-Management:** frühes Testen = Beteiligung = Akzeptanz (Brücke).
- **ADKAR-Ability ↔ Schulung:** Schulung „nah am Go-live" zielt auf **Ability**.
- **Devil's Quadrangle-Lücke ↔ Phase 5:** Quadrangle ignoriert Akzeptanz/Change/Risiko → genau das adressiert Implementation.

---

<a id="merkregeln"></a>
# 🧠 Merkregeln & Eselsbrücken (Sammlung)

- **7 Verschwendungsarten:** **T**ransport · **B**ewegung · **B**estände · **W**artezeit · **F**ehler · **M**ehraufwand · **Ü**berproduktion.
- **Ishikawa 6 M:** Mensch · Maschine · Methode · Messung · Material · Mitwelt.
- **DLZ-Operatoren:** Sequenz **+** · Parallel(AND) **max** · Alternativ(XOR) **gewichtetes Ø** · Schleife **÷ p**.
- **Little:** **L** wie *Lager/Lastvolumen* = λ·W.
- **Devil's Quadrangle:** **Z**eit-**K**osten-**Q**ualität-**F**lexibilität → „ZKQF".
- **7 Heuristik-Kategorien:** Kunden · Operation · Verhalten · Organisation · Information · Technologie · Umwelt.
- **PICK-Matrix:** **P**ossible · **I**mplement · **C**hallenge · **K**ill.
- **Lewin:** *Eiswürfel-Logik* – **Auftauen → Verändern → Einfrieren.**
- **ADKAR:** *Warum → Wollen → Wissen-wie → Können → Dranbleiben.*
- **Rollout:** Big-Bang = schnell+riskant · Pilot = lernend+langsam · Parallel = sicher+teuer.
- **Stau-Effekt:** über 80 % Auslastung → Wartezeit **explodiert** (nicht linear).
- **Verschwendung ist Ergebnis, nicht Ursache.** · **Widerstand ist Information.**

---

<a id="checkliste"></a>
# ✅ Selbstcheck: „Kann ich folgende Punkte erklären?"

**Analyse**
- [ ] Warum „Diagnose vor Therapie"? Qualitativ vs. quantitativ abgrenzen.
- [ ] WS/GWS/NWS zuordnen + 3 Leitfragen + Grenzen der WSA.
- [ ] Alle 7 Verschwendungsarten mit Bürobeispiel; typische Ursachen.

**Ursachen**
- [ ] Auswirkung/Problem/Ursache unterscheiden.
- [ ] Interessengruppenanalyse: Idee + 5 Schritte.
- [ ] Ishikawa (6 M, Aufbau) vs. 5-Why; Kombination.

**Quantitativ**
- [ ] BZ/WZ/DLZ/Zykluszeit/DLZ-Effizienz definieren.
- [ ] DLZ für Sequenz, Alternativ (mit %), Parallel, Schleife berechnen.
- [ ] Little's Law anwenden (Einheiten!).
- [ ] Engpass/Theory of Constraints + Indikatoren.
- [ ] Warteschlangen-Stau-Effekt (ρ > 0,8) erklären.

**Priorisierung**
- [ ] PICK-Matrix + Pareto anwenden.
- [ ] Aufbau Problemregister + QS-Kriterien der Analyse.

**Redesign (Phase 4)**
- [ ] Analyse vs. Redesign; inkrementell vs. radikal (BPR).
- [ ] Mind. 8 Heuristiken mit Kategorie + Beispiel nennen.
- [ ] Devil's Quadrangle operationalisieren (Kennzahl je Dimension).
- [ ] Simulation: Zweck, DES-Bausteine, 5-Schritte-Vorgehen, Monte-Carlo vs. DES, Tools.
- [ ] Fallstudie: Befund→Heuristik, A vs. B, Ergebnis lesen, vergessene Dimension.

**Implementation (Phase 5)**
- [ ] Zwei Stränge; „erfolgreich = gelebt".
- [ ] Vom Modell zum ausführbaren Prozess (4 Schritte; User- vs. Service-Task).
- [ ] Rollout-Strategien situativ wählen.
- [ ] Teststufen + UAT (Kriterien, Rollen).
- [ ] Lewin / Kotter (8 Stufen) / ADKAR anwenden & diagnostizieren.
- [ ] Widerstände → Maßnahmen; Erfolgsfaktoren vs. Stolpersteine.

---

# 📊 Abdeckungs-Statistik

- **Original:** 99 Folien (inkl. ca. 13 reine Titel-/Trennfolien ohne Lerninhalt).
- **Abgedeckt:** **100 % aller inhaltstragenden Folien** – sämtliche Definitionen, Modelle (Lewin, Kotter, ADKAR, Devil's Quadrangle, Little's Law, TOC, Ishikawa, 5-Why, Reijers & Mansar), alle Formeln, Rechenbeispiele (DLZ-Muster, Little, Stau-Effekt), Tabellen (Heuristiken, Simulationsergebnisse, Rollout, Widerstände) und die komplette Fallstudie Regio Versicherung.
- **Umfang:** ca. **25–28 % der Original-Folienmenge** als verdichteter Fließtext/Tabellen – bei voller inhaltlicher Vollständigkeit.
- **Nicht übernommen:** rein dekorative Trennfolien, Logos und doppelte Bild-/Textfassungen identischer Folien (kein Informationsverlust).
