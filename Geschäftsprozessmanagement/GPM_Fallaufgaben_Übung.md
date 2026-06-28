# GPM – Übungsset: Einzel-Fallaufgaben (M4–M6)

*Format wie angekündigt: keine Gesamt-Fallstudie, sondern viele kurze Aufgaben mit je eigenem Geschäftsprozess.*
*Empfehlung: Erst alle Aufgaben ohne Lösung bearbeiten (ca. 50 Min), dann mit Teil 2 vergleichen.*

**Punkte gesamt: 100** · Verteilung: M4 = 50 · M5 = 30 · M6 = 20

---
---

# TEIL 1 – AUFGABEN

## 🟦 M4 – Analyse (50 Pkt)

---

**A1 – Online-Versandhändler (Retoure).** *(4 Pkt)*
Im Retourenprozess druckt ein Mitarbeiter für jede Rücksendung ein Etikett aus, läuft damit zum Drucker im Nachbarraum, holt es und kehrt zurück.
Welche **Verschwendungsart** liegt vor? **Begründen** Sie.

---

**A2 – Arztpraxis.** *(4 Pkt)*
Patientendaten werden bei der Anmeldung handschriftlich auf einem Formular erfasst und später von der Sprechstundenhilfe erneut in die Praxissoftware eingetippt.
**Verschwendungsart + Begründung?**

---

**A3 – Bauamt.** *(4 Pkt)*
Im Posteingang des Bauamts liegen 180 unbearbeitete Bauanträge; täglich kommen mehr dazu, als bearbeitet werden.
**Verschwendungsart + Begründung?** Wie nennt man diese Menge unbearbeiteter Vorgänge in Little's Law?

---

**A4 – Reisebüro (Begriffe).** *(6 Pkt)*
Ordnen Sie die drei Aussagen den Begriffen **Auswirkung / Problem / Ursache** zu und erklären Sie in einem Satz, **warum** man diese drei trennt.
- (a) „Kund:innen beschweren sich über zu späte Reiseunterlagen."
- (b) „Der Versand der Unterlagen dauert regelmäßig über 10 Tage."
- (c) „Es gibt keinen festen Verantwortlichen für den Versand."

---

**A5 – Kfz-Werkstatt (5-Why).** *(6 Pkt)*
Beobachtung: „Ein Kundenauto wurde nicht rechtzeitig fertig."
Bauen Sie eine **plausible 5-Why-Kette** auf und benennen Sie die **Wurzelursache**.

---

**A6 – Hochschul-Prüfungsamt (Rechnen).** *(8 Pkt)*
Ein Antrag auf Anerkennung von Leistungen hat eine **Durchlaufzeit von 20 Arbeitstagen**, davon **1 AT** reine Bearbeitung.
a) Berechnen Sie die **Durchlaufzeiteffizienz**.
b) Deuten Sie das Ergebnis in einem Satz.
c) Wo sollte man laut Ergebnis zuerst ansetzen – Bearbeitung oder Wartezeit? Warum?

---

**A7 – Bank, Kreditantrag (Rechnen, BPMN).** *(8 Pkt)*
Aktivität A (Vorprüfung, 2 Tage) führt zu einem **AND-Gateway** mit zwei **parallelen** Zweigen: B (Bonitätsprüfung, 5 Tage) und C (Objektbewertung, 3 Tage); danach werden beide zusammengeführt.
Berechnen Sie die **Durchlaufzeit** und **begründen** Sie die Rechenregel.
*Zusatz (1 von 8 Pkt): Wie änderte sich das Ergebnis, wenn B und C **sequenziell** liefen?*

---

**A8 – Bürgerbüro (Little's Law).** *(6 Pkt)*
In ein Bürgerbüro gehen **3.600 Anträge pro Jahr** ein; die durchschnittliche Durchlaufzeit beträgt **2 Wochen** (rechnen Sie mit 36 Wochen Betriebszeit/Jahr… *Korrektur:* rechnen Sie mit **45 Arbeitswochen/Jahr**).
Berechnen Sie mit **Little's Law** die durchschnittliche Zahl gleichzeitig laufender Vorgänge (WIP). Geben Sie den Rechenweg an.

---

**A9 – Versicherung, Schadenprüfung (Engpass).** *(6 Pkt)*
In der Schadenbearbeitung müssen alle Fälle durch **eine** zentrale Prüfstelle (Auslastung dauerhaft ~98 %). Davor stauen sich die Vorgänge; die nachgelagerte Auszahlung ist nur zu 55 % ausgelastet.
a) Wo ist der **Engpass**? Woran erkennt man ihn?
b) Erklären Sie mit der **Theory of Constraints**, warum es nichts bringt, die Auszahlung zu beschleunigen.

---

**A10 – Logistikzentrum (Simulation).** *(8 Pkt)*
Vor Einführung eines neuen Sortierprozesses will der Betrieb die erwartete Durchlaufzeit und Kosten abschätzen – Echtdaten gibt es noch nicht.
a) Nennen Sie den **Hauptvorteil** der Prozesssimulation.
b) Warum spielen **Ressourcen** (Anzahl Sortierer, Verfügbarkeit) eine **entscheidende** Rolle für ein realistisches Ergebnis?
c) Welcher Simulationstyp berücksichtigt Ressourcenkonkurrenz – **Monte-Carlo** oder **DES**?

---

## 🟩 M5 – Redesign (30 Pkt)

---

**A11 – IT-Helpdesk (Abgrenzung).** *(5 Pkt)*
Erklären Sie am Beispiel eines Helpdesk-Prozesses den Unterschied zwischen **Analyse** und **Redesign**. Ordnen Sie zu: „misst, dass 40 % der Tickets länger als 3 Tage offen sind" und „führt einen Self-Service-Pfad für Standardfragen ein".

---

**A12 – Personalabteilung, Onboarding (Heuristik wählen).** *(6 Pkt)*
Befund: Beim Onboarding läuft die IT-Einrichtung **erst nach** abgeschlossener Vertragsprüfung, obwohl beide voneinander unabhängig sind. Neue Mitarbeitende können dadurch spät starten.
a) Welche **Heuristik** passt am besten?
b) **Wie** verbessert sie den Prozess, und welche **Devil's-Quadrangle-Dimension** gewinnt?

---

**A13 – Möbelhaus, Kulanz (Heuristik wählen).** *(6 Pkt)*
Befund: Jede Kulanz-Erstattung – auch 15 € – muss vom Abteilungsleiter freigegeben werden. Das dauert und erzeugt einen Stau.
a) Welche **Heuristik** passt am besten?
b) Begründen Sie die Wirkung.

---

**A14 – Steuerkanzlei (Devil's Quadrangle anwenden).** *(8 Pkt)*
Eine Kanzlei erwägt, die Erfassung von Mandantenbelegen per **automatischer Texterkennung (OCR)** statt manueller Eingabe umzustellen.
Bewerten Sie diese Variante gegenüber dem Ist-Zustand über **alle vier Dimensionen** des Devil's Quadrangle und benennen Sie den **zentralen Trade-off**.

---

**A15 – Service-Hotline (Auslastung & Durchlaufzeit).** *(5 Pkt)*
Eine Hotline mit einer Person erhält ø **6 Anrufe/Stunde**, ein Anruf dauert ø **8 Minuten**.
a) Berechnen Sie die **Auslastung**.
b) Erklären Sie, was mit der durchschnittlichen Wartezeit passiert, wenn die Auslastung weiter Richtung 95 % steigt – und **warum**.

---

## 🟨 M6 – Implementation (20 Pkt)

---

**A16 – Krankenhaus, neues Dokusystem (zwei Stränge).** *(5 Pkt)*
Ordnen Sie die folgenden vier Maßnahmen jeweils dem Strang **„Organisatorische Umsetzung"** oder **„Systemimplementierung"** zu:
(1) Schulung der Pflegekräfte · (2) Migration der Altpatientendaten · (3) Kommunikation der Vision durch die Klinikleitung · (4) Anbindung an das Laborsystem.
*Was bedeutet der Merksatz „Technik ohne Akzeptanz scheitert"?*

---

**A17 – Behörde, 4 Standorte (Rollout).** *(5 Pkt)*
Eine Behörde stellt an 4 Standorten auf ein neues Workflow-System um. Die Belegschaft ist **veränderungsmüde**, der Prozess ist **kritisch**, Go-live liegt **8 Wochen vor der Hauptsaison**.
Welche **Rollout-Strategie** empfehlen Sie? **Begründen** Sie anhand von Risiko, Lerneffekt und Aufwand.

---

**A18 – Software-Rollout, Tests (Zuordnung).** *(5 Pkt)*
Ordnen Sie jeden Befund der richtigen **Teststufe** zu (Komponententest / Integrationstest / UAT / Pilot):
- (a) Eine einzelne Berechnungsfunktion liefert ein falsches Ergebnis.
- (b) Die Schnittstelle zum Zahlungssystem bricht ab.
- (c) Key-User stellen fest, dass ein wichtiger Sonderfall im Alltag nicht abgebildet ist.
- (d) Im Probebetrieb unter Realbedingungen treten unerwartete Lastspitzen auf.

---

**A19 – Online-Antrag, UAT (Verständnis).** *(5 Pkt)*
a) Was wird im **User Acceptance Test (UAT)** geprüft – und durch **wen**?
b) Warum müssen Akzeptanzkriterien auch **Sonderfälle** abdecken (nicht nur den Normalfall)?
c) Nennen Sie **einen** Erfolgsfaktor und **einen** Stolperstein der Einführung.

---
---
---

# TEIL 2 – MUSTERLÖSUNGEN & BEWERTUNG

## 🟦 M4

**A1 – Online-Versandhändler** *(4)*
- **Art: Bewegung** *(2)* – unnötiges Laufen/Suchen des Mitarbeiters (Mensch bewegt sich), ohne dass Wert entsteht *(2 Begründung)*.
- *Hinweis:* nicht „Transport" (das wäre Bewegung von Info/Material von A nach B). Hier bewegt sich die **Person**.

**A2 – Arztpraxis** *(4)*
- **Art: Mehraufwand** (Doppelarbeit; auch akzeptabel: Hinweis auf **Medienbruch**) *(2)* – dieselben Daten werden **zweimal** erfasst, ohne zusätzlichen Wert *(2)*.

**A3 – Bauamt** *(4)*
- **Art: Bestände** *(2)* – unbearbeitete Vorgänge stauen sich an; mehr Zugang als Abfluss *(1)*.
- In Little's Law heißt diese Menge **L (WIP / Work in Progress)** *(1)*.

**A4 – Reisebüro** *(6)*
- (a) **Auswirkung** (sichtbares Symptom) *(1,5)* · (b) **Problem** (Grundphänomen) *(1,5)* · (c) **Ursache** (Wurzel) *(1,5)*.
- **Warum trennen:** Um an der **Ursache** anzusetzen statt am Symptom – sonst nur Symptombekämpfung, das Problem kehrt zurück *(1,5)*.

**A5 – Kfz-Werkstatt** *(6)* – *Musterkette (andere plausible Ketten zählen voll):*
- Auto nicht fertig → *Warum?* Ersatzteil fehlte → *Warum?* nicht rechtzeitig bestellt → *Warum?* Bedarf zu spät erkannt → *Warum?* keine Prüfung der Teileverfügbarkeit bei Auftragsannahme → *Warum?* Prozess sieht diesen Check nicht vor.
- **Wurzelursache:** fehlende Teileverfügbarkeitsprüfung bei Auftragsannahme.
- **Bewertung:** Kette mit ≥4 sinnvollen Warum-Schritten *(4)* + klar benannte Wurzelursache *(2)*. Nur Symptome wiederholen ohne Tiefe = max. 2.

**A6 – Prüfungsamt** *(8)*
- a) Effizienz = **BZ/DLZ = 1/20 = 0,05 = 5 %** *(Formel 2 + Ergebnis 3; nur Ergebnis ohne Weg = 2)*.
- b) Nur 5 % der Zeit ist echte Bearbeitung, **95 % Wartezeit** *(2)*.
- c) Bei der **Wartezeit** ansetzen – dort liegt das Potenzial *(1)*.

**A7 – Bank, Kreditantrag** *(8)*
- **Parallel (AND) → A + Maximum** der Zweige: 2 + max(5, 3) = **7 Tage** *(Regel/Begründung 3 + Rechnung 4)*.
- **Begründung:** Beide Zweige laufen gleichzeitig; die Zusammenführung wartet auf den **längeren** → es zählt das Maximum, nicht die Summe.
- Zusatz: sequenziell wären es 2 + 5 + 3 = **10 Tage** *(1)*.

**A8 – Bürgerbüro (Little's Law)** *(6)*
- λ = 3.600 / 45 Wochen = **80 Anträge/Woche** *(2)*.
- W = **2 Wochen** *(1)*.
- L = λ·W = 80 · 2 = **160 laufende Vorgänge** *(3)*.
- *Bewertung:* Einheiten korrekt angeglichen (Jahr→Woche) ist der Knackpunkt. Falsche/fehlende Umrechnung → max. 3.

**A9 – Versicherung** *(6)*
- a) **Engpass = zentrale Prüfstelle** *(2)*; erkennbar an **Stau davor (hohes WIP)** und **~100 % Auslastung** *(1)*.
- b) **TOC:** Der Gesamtdurchsatz wird allein vom Engpass begrenzt. Die Auszahlung ist kein Engpass (55 %) → schneller auszuzahlen erhöht nur die Wartemenge **vor** der Prüfstelle, nicht den Durchsatz *(3)*.

**A10 – Logistikzentrum** *(8)*
- a) **Hauptvorteil:** Wirkung (Zeit, Kosten, Auslastung, Durchsatz) **ex ante, ohne Live-Betrieb** abschätzen – auch ohne Echtdaten; Ergebnis sind Verteilungen mit Konfidenz *(3)*.
- b) **Ressourcen:** Wartezeiten und Engpässe entstehen genau dort, wo Fälle auf **belegte Ressourcen** warten; ohne Ressourcenmodell unterschätzt man Staus (Mittelwerte täuschen, Wartezeit explodiert nahe 100 %) → unrealistisch optimistisch *(3)*.
- c) **DES** (Discrete-Event-Simulation) berücksichtigt Ressourcenkonkurrenz/Warteschlangen *(2)*.

---

## 🟩 M5

**A11 – IT-Helpdesk** *(5)*
- **Analyse = Diagnose** (versteht/quantifiziert Schwachstellen) · **Redesign = Therapie** (entwirft Lösung, schätzt Wirkung) *(3)*.
- „misst, dass 40 % … offen sind" → **Analyse** *(1)*; „führt Self-Service-Pfad ein" → **Redesign** *(1)*.

**A12 – Onboarding** *(6)*
- a) **Parallelism** *(3)*.
- b) Unabhängige Aufgaben (IT-Einrichtung, Vertragsprüfung) **gleichzeitig** statt nacheinander → die Person startet früher; gewonnene Dimension: **Zeit** (Durchlaufzeit ↓) *(3)*.

**A13 – Möbelhaus, Kulanz** *(6)*
- a) **Empower** *(3)*.
- b) Mitarbeitende dürfen Kleinbeträge selbst freigeben → **Genehmigungsschleife/Engpass entfällt**, Durchlaufzeit ↓, Stau ↓ *(3)*. *(Akzeptabel ergänzend: Knock-out, wenn als Schwellenwert-Regel argumentiert.)*

**A14 – Steuerkanzlei (Devil's Quadrangle)** *(8)*
- **Zeit:** besser – OCR ist schneller als manuelles Tippen *(2)*.
- **Kosten:** geringer – weniger manueller Aufwand, weniger Nacharbeit *(2)*.
- **Qualität:** gemischt – weniger Tippfehler, *aber* OCR kann bei schlechten Scans Erkennungsfehler erzeugen (Stichprobe/Prüfung sinnvoll) *(2)*.
- **Flexibilität:** eher geringer – standardisierte Erkennung schwächer bei unüblichen Belegformaten *(1)*.
- **Trade-off:** **Zeit + Kosten gewonnen, Flexibilität (ggf. Qualität bei Sonderbelegen) leicht verloren** *(1)*.
- *Bewertung:* alle 4 Dimensionen + Trade-off = 8; nur Vorteile genannt → max. 5.

**A15 – Service-Hotline (Auslastung)** *(5)*
- a) Auslastung = 6/h × 8 Min = **48 Min/Stunde → 80 %** (ρ = λ/μ) *(2)*.
- b) Steigt die Auslastung Richtung **95 %**, **explodiert die Wartezeit überproportional** (nichtlinear): bei 80 % ø ~32 Min, bei 95 % > 2 h. **Warum:** kaum Puffer für Schwankungen → Vorgänge stauen sich, kleine Auslastungserhöhung = große Wartezeit-Wirkung *(3)*.

---

## 🟨 M6

**A16 – Krankenhaus (zwei Stränge)** *(5)*
- **Organisatorisch:** (1) Schulung, (3) Kommunikation der Vision *(2)*.
- **System:** (2) Datenmigration, (4) Laborsystem-Anbindung *(2)*.
- **Merksatz:** Selbst ein technisch perfektes System scheitert, wenn die Menschen es nicht annehmen/leben – beide Stränge müssen zusammenwirken *(1)*.

**A17 – Behörde, Rollout** *(5)*
- Empfehlung: **Pilot / phasenweise** (nicht Big-Bang) *(2)*.
- **Begründung:** kritischer Prozess + veränderungsmüde Belegschaft → **Risiko** eines Big-Bang zu hoch; **Lerneffekt** am ersten Standort senkt Risiko für die übrigen; vor der Hauptsaison kein riskanter Komplettumstieg. **Parallelbetrieb** wäre sicher, aber bei 4 Standorten zu teuer/aufwändig *(3)*.
- *(Gut begründeter Parallelbetrieb kann ebenfalls Punkte geben; Big-Bang hier schwer zu rechtfertigen.)*

**A18 – Tests (Zuordnung)** *(5; je ~1,25)*
- (a) → **Komponententest** (einzelne Funktion)
- (b) → **Integrationstest** (Schnittstelle/Datenfluss)
- (c) → **UAT** (fachlicher Sonderfall aus Nutzersicht)
- (d) → **Pilot / Probebetrieb** (reale Bedingungen/Last)

**A19 – UAT** *(5)*
- a) Im UAT prüfen die **künftigen Nutzer/Key-User** anhand **realistischer Fälle**, ob der **Prozess die fachlichen Anforderungen** erfüllt; Sign-off = Voraussetzung für Go-live *(2)*.
- b) **Sonderfälle**, weil der Normalfall meist funktioniert – **Fehler und Risiken stecken in den Ausnahmen** (z. B. unvollständige Eingaben, Sonderanträge); nur so wird der Prozess wirklich abgesichert *(2)*.
- c) Je 1 Beispiel: **Erfolgsfaktor** z. B. frühe ehrliche Kommunikation / Schulung nah am Go-live / Beteiligung; **Stolperstein** z. B. Fokus nur auf Technik / Schulung zu früh / Widerstand ignorieren / Go-live ohne Test *(1)*.

---

# 📊 Auswertung & nächste Schritte

| Bereich | Punkte | Fokus |
|---|---|---|
| M4 (Analyse) | 50 | Verschwendung zuordnen+begründen, Rechnen (Effizienz/DLZ/Little), Engpass, Simulation |
| M5 (Redesign) | 30 | Analyse vs. Redesign, Heuristik wählen, Devil's Quadrangle, Auslastung |
| M6 (Implementation) | 20 | zwei Stränge, Rollout, Teststufen, UAT/Sonderfälle |

**Selbstcheck:**
- ≥ 85: Schwerpunkte sitzen.
- 65–84: gezielt die Verlierer-Aufgaben + zugehöriges Kapitel in der Schwerpunkt-Lernhilfe nachlesen.
- < 65: Rechenregeln (DLZ-Operatoren, Little's-Einheiten) und Verschwendungs-/Heuristik-Zuordnung intensiv üben.

**Häufigste Fehler in diesem Set:**
1. AND-Gateway summiert statt **max** (A7).
2. Little's Law ohne **Einheitenumrechnung** (A8).
3. Verschwendung „Bewegung" vs. „Mehraufwand" vs. „Transport" verwechselt (A1/A2).
4. Devil's Quadrangle: nur Vorteile, **Trade-off** vergessen (A14).
5. Bei Rollout/Tests **ohne Begründung** geantwortet (Begründung = halbe Punkte).
