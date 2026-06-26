# LÖSUNGSSCHLÜSSEL & AUSWERTUNG – Probeklausur GPM

*Zur Selbstkorrektur. Erst die Klausur unter Zeitdruck (60 Min) bearbeiten, dann hier vergleichen.*

---

## TEIL A: Multiple Choice (20 Pkt) – Lösungen

**1 → C** *(2 Pkt)*
- **Begründung:** „Diagnose vor Therapie" ist das Leitprinzip; ohne Diagnose nur Symptombekämpfung.
- **Häufiger Fehler:** B (Reihenfolge vertauscht – richtig ist *erst qualitativ, dann quantitativ*).
- **Prüft:** Kap. 1.

**2 → C** *(2 Pkt)*
- **Begründung:** Gesetzliche Pflicht = für das Unternehmen notwendig = **GWS**.
- **Häufiger Fehler:** A (Doku schafft keinen Kundenwert → nicht WS) oder B (sie ist *notwendig*, also nicht reines NWS).
- **Prüft:** Kap. 2 (WSA).

**3 → B** *(3 Pkt)*
- **Begründung:** Ishikawa = breit (6 M), 5-Why = tief (eine Spur); Kombination: erst Ishikawa, dann pro Hauptast 5-Why.
- **Häufiger Fehler:** A (breit/tief vertauscht); D (beide brauchen *Daten*, nicht Bauchgefühl).
- **Prüft:** Kap. 6–7.

**4 → C** *(3 Pkt)*
- **Begründung:** Parallele Pfade (AND) → **A + Maximum** der Zweige = 10 + max(20,10) = **30**.
- **Häufiger Fehler:** A (summiert die Parallelzweige – falsch); B (gewichtetes Ø gilt für XOR, nicht AND); D (Schleifenformel).
- **Prüft:** Kap. 9 (DLZ-Strukturen). **Klassische Falle!**

**5 → B** *(2 Pkt)*
- **Begründung:** TOC: nur der Engpass limitiert den Durchsatz; Nicht-Engpass-Optimierung bringt nichts.
- **Häufiger Fehler:** D (Engpass *verschiebt* sich nach Erweiterung → neuer Engpass).
- **Prüft:** Kap. 10.

**6 → C** *(3 Pkt)*
- **Begründung:** L = λ·W; Einheiten angleichen: λ = 2400/12 = 200 Anträge/Monat, W = 2 Monate → L = 200·2 = **400**.
- **Häufiger Fehler:** A (W = 1 Monat angenommen); B (Einheiten nicht umgerechnet, 2400/12·1); D (λ·W ohne /12).
- **Prüft:** Kap. 11. **Einheitenfalle!**

**7 → C** *(3 Pkt)*
- **Begründung:** Genau die Definition von Knock-out/Resequencing.
- **Häufiger Fehler:** A (Task elimination = Aufgabe *streichen*, nicht *ordnen*).
- **Prüft:** Kap. 18.

**8 → C** *(2 Pkt)*
- **Begründung:** „Kann nicht bedienen" = fehlende **Ability** → Schulung/Übung/Begleitung.
- **Häufiger Fehler:** A/B (Awareness/Desire betreffen *Wollen/Sinn*, nicht *Können*).
- **Prüft:** Kap. 27 (ADKAR).

> **Punkte Teil A:** 2+2+3+3+2+3+3+2 = **20**.

---

## TEIL B: Kurz-Antworten (25 Pkt) – Modell-Antworten & Raster

### Aufgabe 9 (6 Pkt) – WSA-Kategorien + Ziel
**Modell-Antwort:**
- **WS** (wertschöpfend): schafft Wert für den Kunden, Kunde würde zahlen. *(1,5 Pkt)*
- **GWS** (geschäftswertschöpfend): für das Unternehmen notwendig (Compliance, Kontrolle, gesetzliche Pflicht). *(1,5 Pkt)*
- **NWS** (nicht-wertschöpfend): weder für Kunde noch Unternehmen wertvoll (Doppelarbeit, Warten, Korrekturen). *(1,5 Pkt)*
- **Ziel:** NWS minimieren, GWS kritisch hinterfragen, WS schützen. *(1,5 Pkt)*

**Raster:** 6 = alle 3 Kürzel korrekt erklärt + Ziel präzise · 4–5 = kleine Unschärfen · 2–3 = nur Kürzel ohne Erklärung oder Ziel fehlt · 0–1 = überwiegend falsch.

### Aufgabe 10 (6 Pkt) – DLZ / BZ / Effizienz
**Modell-Antwort:**
- **DLZ** = Gesamtzeit von Prozessstart bis -ende = **BZ + WZ**. *(1,5 Pkt)*
- **BZ** = reine Arbeitszeit an einer Aktivität. *(1,5 Pkt)*
- **Durchlaufzeiteffizienz = BZ / DLZ** (Anteil wertschöpfender Zeit). *(1,5 Pkt)*
- **Begründung < 15 %:** In Verwaltungsprozessen **dominiert die Wartezeit** (Liegezeiten, Unterschriften, Rückläufe); die reine Bearbeitung ist nur ein Bruchteil der Gesamtzeit. *(1,5 Pkt)*

**Raster:** 6 = drei Definitionen + Begründung korrekt · 4–5 = eine Definition schwach oder Begründung dünn · 2–3 = Begriffe vermischt · 0–1 = unbrauchbar.
**Häufiger Fehler:** Zykluszeit mit DLZ verwechseln.

### Aufgabe 11 (6 Pkt) – Monte-Carlo vs. DES
**Modell-Antwort:**
- **Monte-Carlo:** summiert Segment-/Aktivitäts-Verteilungen über viele Ziehungen, **ohne** Ressourcenkonkurrenz/Warteschlangen → schnell, gut für **reine Durchlaufzeit**. *(2,5 Pkt)*
- **DES (Discrete-Event):** modelliert zusätzlich **Warteschlangen, Kapazitäten und Ressourcenkonkurrenz** über eine simulierte Uhr → zeigt **Engpässe unter Last**. *(2,5 Pkt)*
- **Wann was:** MC bei reiner DLZ-Abschätzung/geringem Aufwand; DES bei hoher Last-/Ressourcendynamik. *(1 Pkt)*

**Raster:** 6 = beide korrekt charakterisiert + Einsatzempfehlung · 4–5 = ein Verfahren schwach · 2–3 = nur Schlagworte · 0–1 = verwechselt.
**Häufiger Fehler:** DES als „nur schneller" beschreiben – der Kernunterschied ist die **Ressourcenkonkurrenz**.

### Aufgabe 12 (7 Pkt) – Rollout-Strategien
**Modell-Antwort:**
- **Big-Bang:** Umstellung aller zu einem Stichtag. + schnell, kein Doppelbetrieb / − hohes Risiko, Rückfall schwer. *(2,5 Pkt)*
- **Pilot / phasenweise:** Start mit Teilbereich, dann ausrollen. + Lernen am kleinen Fall, Risiko begrenzt / − länger, Übergänge managen. *(2,5 Pkt)*
- **Parallelbetrieb:** alt + neu laufen parallel. + sicher, direkter Vergleich / − doppelte Last, teuer. *(2 Pkt)*

**Raster:** 7 = drei Strategien + je Vor-/Nachteil · 5–6 = ein Nachteil/Vorteil fehlt · 3–4 = nur Namen + grobe Idee · 0–2 = unvollständig.

---

## TEIL C: Fallstudie „Bürgeramt" (45 Pkt) – Modell-Antworten & Raster

### Teil a) Durchlaufzeiteffizienz (8 Pkt)
**Modell-Antwort:**
- Formel: **Effizienz = BZ / DLZ**. *(2 Pkt)*
- Einsetzen: 0,5 AT / 15 AT = **0,0333… ≈ 3,3 %**. *(4 Pkt; nur Ergebnis ohne Rechenweg = 2 Pkt)*
- Interpretation: Nur ~3 % der Durchlaufzeit ist echte Bearbeitung; **97 % ist Wartezeit** – riesiges Optimierungspotenzial liegt in der Wartezeit, nicht in der Bearbeitung. *(2 Pkt)*

**Häufiger Fehler:** DLZ und BZ vertauschen (15/0,5); Interpretation vergessen.

### Teil b) Befunde → Verschwendung + Heuristik (12 Pkt; je Befund 4 Pkt)
**Modell-Antwort (akzeptable Alternativen in Klammern):**

| Befund | Verschwendungsart | Heuristik | Begründung |
|---|---|---|---|
| **B1** (unvollständige Anträge) | **Fehler** (auch: Mehraufwand durch Rückfragen) | **Control addition / relocation** (Pflichtfelder/Validierung an der Quelle) | Fehler an der Quelle verhindern statt später teuer nachfragen |
| **B2** (Freigabe nur durch Amtsleitung, Engpass) | **Wartezeit** (Stau vor Engpass) | **Empower** (Befugnis erweitern, Genehmigungsschleife reduzieren) | Einfache Fälle ohne Leitungs-Freigabe → Engpass entlasten |
| **B3** (handschriftlich + erneut abtippen) | **Mehraufwand** (Doppelarbeit; auch: Medienbruch) | **Task automation / Integral technology** (durchgängig digital, Medienbruch beseitigen) | Doppelte Erfassung entfällt bei digitaler Durchgängigkeit |

**Punktevergabe je Befund:** richtige Verschwendungsart 1,5 · passende Heuristik 1,5 · stimmige Begründung 1.
**Häufiger Fehler:** B3 als „Bewegung" statt „Mehraufwand/Doppelarbeit"; Heuristik nur nennen ohne Bezug zum Befund (zählt halb).

### Teil c) Theory of Constraints (8 Pkt)
**Modell-Antwort:**
- **Kernargument:** Der Gesamtdurchsatz wird allein vom **Engpass (Amtsleitung, ~100 % ausgelastet)** begrenzt. Die Sachbearbeitung ist **kein** Engpass (60 % Auslastung) → ihre Beschleunigung erhöht nur das WIP **vor** dem Engpass, nicht den Durchsatz. *(4 Pkt)*
- **TOC-Vorgehen:** Engpass **finden → erweitern/entlasten → neuer Engpass entsteht → wiederholen** (iterativ). *(4 Pkt)*

**Raster:** 8 = Kernargument + vollständiger Zyklus · 5–6 = Argument korrekt, Zyklus unvollständig · 3–4 = nur Grundidee · 0–2 = falsch.
**Häufiger Fehler:** Behaupten, schnellere Sachbearbeitung helfe „ein bisschen" – nein, der Engpass bleibt limitierend.

### Teil d) Devil's Quadrangle (10 Pkt)
**Modell-Antwort (Bewertung To-be vs. Ist):**
- **Zeit:** stark verbessert – Pflichtfelder + Auto-Freigabe senken Wartezeit, DLZ fällt deutlich (Ziel < 5 AT erreichbar). *(2,5 Pkt)*
- **Kosten:** gesenkt – weniger Rückfragen, keine Doppelerfassung, weniger manuelle Freigaben. *(2,5 Pkt)*
- **Qualität:** Validierung an der Quelle senkt Fehlerquote; *aber* Auto-Freigabe einfacher Fälle kann Kontrolltiefe leicht reduzieren (Stichprobe empfehlenswert). *(2,5 Pkt)*
- **Flexibilität:** tendenziell **geringer** – automatisierte/standardisierte Pfade sind weniger anpassbar für Sonderfälle. *(1,5 Pkt)*
- **Zentraler Trade-off:** **Zeit + Kosten gewonnen, Flexibilität (und ggf. Kontrolltiefe) leicht verloren** – der typische Vierfach-Konflikt. *(1 Pkt)*

**Raster:** 10 = alle 4 Dimensionen plausibel + Trade-off benannt · 7–9 = eine Dimension schwach · 4–6 = nur 2–3 Dimensionen · 0–3 = Trade-off-Gedanke fehlt.
**Häufiger Fehler:** Nur Vorteile nennen; Automatisierung steigert **nicht** automatisch die Flexibilität (eher umgekehrt).

### Teil e) Lewin + Change-Maßnahmen (7 Pkt)
**Modell-Antwort:**
- **Übersprungene Phase:** **Unfreeze** (Auftauen) – es fehlt das Schaffen von Veränderungsbereitschaft. *(2 Pkt)*
- **Folge:** Unsicherheit/Widerstand, fehlende Akzeptanz; der Prozess wird umgangen, unterlaufen oder nur halb genutzt. *(2 Pkt)*
- **Zwei Maßnahmen (je 1,5 Pkt), z. B.:** frühe, ehrliche Kommunikation (das **Warum vor dem Was**, Zweiweg); **Beteiligung** der Betroffenen (z. B. Key-User in UAT einbinden); rechtzeitige **Schulung nah am Go-live**; **Quick Wins** sichtbar machen. *(3 Pkt)*

**Raster:** 7 = Phase + Folge + zwei passende Maßnahmen · 5–6 = eine Maßnahme schwach · 3–4 = nur Phase korrekt · 0–2 = falsche Phase.
**Häufiger Fehler:** „Change" oder „Refreeze" als übersprungene Phase nennen – übersprungen wird der **Anfang (Unfreeze)**.

---

## TEIL D: Zuordnung (10 Pkt) – Lösungen

### Aufgabe 13 (5 Pkt; je 1 Pkt)
1 → **B** (Refreeze = stabilisieren/verankern)
2 → **D** (Kotter Stufe 6 = schnelle Erfolge / Quick Wins)
3 → **A** (ADKAR Knowledge = Wissen, wie verändert wird)
4 → **C** (ADKAR gesamt = individuelle Ebene, bottom-up)
5 → **E** (Kotter gesamt = 8-Stufen-„Treppe")

### Aufgabe 14 (5 Pkt; 4× Zuordnung je 1 Pkt + 1 Pkt für PICK-Akronym)
1 → **C** (hohe Wirkung/niedriger Aufwand = Implement, Quick Wins)
2 → **A** (hohe Wirkung/hoher Aufwand = Challenge)
3 → **D** (niedrige Wirkung/niedriger Aufwand = Possible)
4 → **B** (niedrige Wirkung/hoher Aufwand = Kill)
**PICK** = **P**ossible · **I**mplement · **C**hallenge · **K**ill. *(1 Pkt)*

---
---

# 💡 ZEITMANAGEMENT (60 Minuten)

| Phase | Zeit | Hinweis |
|---|---|---|
| Überblick: alle Aufgaben lesen | **3 Min** | Punkte = Zeitbudget; Fallstudie-Kennzahlen markieren |
| Teil A (MC) | **8 Min** | Schnelle Punkte zum Aufwärmen; bei Rechen-MC (4, 6) kurz rechnen |
| Teil B (Kurz-Antworten) | **15 Min** | ~3,5 Min/Frage; Stichworte statt Fließtext |
| Teil C (Fallstudie) | **28 Min** | 1× intensiv lesen, antworten skizzieren, dann sauber schreiben |
| Teil D (Zuordnung) | **4 Min** | Reine Erinnerung – schnell |
| Kontrolle | **2 Min** | Rechenwege & Einheiten prüfen |

**Strategie:**
- Mit **Teil A** starten (Motivation, sichere Punkte).
- In **Teil B** zuerst die Frage beantworten, die du am sichersten kannst.
- **Fallstudie:** Teil a) ist eine schnelle Rechnung – sofort sichern. Teil b)-Tabelle gibt viele Punkte bei wenig Schreibaufwand.
- **Rechenwege immer hinschreiben** (Teilpunkte!).

**Häufige Anfängerfehler:**
- **Parallel ≠ Summe** → bei AND das **Maximum** nehmen (MC 4).
- **Little's Law: Einheiten angleichen** (Jahr → Monat) bevor du multiplizierst (MC 6, Fallstudie).
- **Interpretation vergessen** bei Rechenaufgaben (Teil a) verlangt einen Satz Deutung).
- **Heuristik ohne Fallbezug** zählt nur halb (Teil b).

---

# 📊 BEWERTUNGSRASTER (Selbstcheck)

| Punkte | Note | Bedeutung |
|---|---|---|
| 90–100 | 1,0–1,3 | Sehr gut – Stoff sitzt |
| 80–89 | 1,7–2,0 | Gut – sicher bestanden |
| 70–79 | 2,3–2,7 | Befriedigend |
| 60–69 | 3,0–3,3 | Ausreichend – bestanden, aber Lücken |
| 50–59 | 3,7–4,0 | Gerade bestanden – nacharbeiten |
| < 50 | 5,0 | Nicht bestanden – Grundlagen wiederholen |

**Selbstanalyse nach der Korrektur:**
- Welche **Aufgabentypen** kosten dich Punkte (Rechnen? Heuristik-Zuordnung? Change-Modelle?)
- Welche **Konzepte** sind lückenhaft? → gezielt im Spickzettel/Karteikarten nachlernen.
- War dein **Zeitmanagement** realistisch – oder bei der Fallstudie verlaufen?

---

# 📈 KLAUSUR-STATISTIK & ABDECKUNG

**Punkte- und Schwierigkeitsverteilung:**

| Teil | Punkte | Anteil | Schwierigkeit |
|---|---|---|---|
| A – MC | 20 | 20 % | 5 leicht / 3 mittel-schwer |
| B – Kurz | 25 | 25 % | überw. mittel |
| C – Fallstudie | 45 | 45 % | mittel bis schwer |
| D – Zuordnung | 10 | 10 % | leicht |

**Schwierigkeit gesamt (Ziel 40/40/20):**
- **Leicht (~40 %):** MC 1, 2, 5, 8 · B9 · D13, D14 · C-a, C-e (Teile)
- **Mittel (~40 %):** MC 3, 7 · B10, B11, B12 · C-b, C-c
- **Schwer (~20 %):** MC 4, 6 (Rechen-Fallen) · C-c (TOC-Synthese) · C-d (Quadrangle-Analyse)

**Inhaltliche Abdeckung der Zusammenfassung:**
- **Abgefragte Kapitel:** 1 (Diagnose), 2 (WSA), 3 (Verschwendung), 6–7 (Ishikawa/5-Why), 9 (DLZ-Rechnung), 10 (TOC/Engpass), 11 (Little's Law), 12/20 (Simulation/MC vs. DES), 13 (PICK), 18 (Heuristiken), 19 (Devil's Quadrangle), 25 (Rollout), 27 (Lewin/Kotter/ADKAR).
- **Abdeckung:** **~80 % der inhaltstragenden Kapitel**. Die Fallstudie integriert **6 Kapitel** (Verschwendung, DLZ, TOC, Heuristiken, Devil's Quadrangle, Change-Management).
- **Nicht direkt geprüft (selbst wiederholen):** Interessengruppenanalyse (Kap. 5), Problemregister/QS (Kap. 15), UAT-Detailschritte (Kap. 26) – sind aber klausurrelevant und sollten gelernt bleiben.

**Durchschnittliche Bearbeitungszeit pro Punkt:** ~0,55 Min/Pkt → realistisch für 60 Minuten.

**Wichtigste Konzepte (Schwerpunkt der echten Prüfung – Erfahrungswert):**
1. **DLZ-Berechnung in BPMN** (Sequenz/XOR/AND/Schleife) – fast immer Rechenaufgabe.
2. **Little's Law** – beliebte Einheiten-Falle.
3. **Reijers-&-Mansar-Heuristiken** – Befund→Heuristik-Zuordnung.
4. **Devil's Quadrangle** – Varianten bewerten + Trade-off.
5. **Change-Management (Lewin/Kotter/ADKAR)** – Diagnose welcher Baustein/Phase fehlt.

---

## ✅ Erstellungs-Checkliste (erfüllt)
- [x] Summe genau **100 Punkte**
- [x] **4 Aufgabentypen** (MC, Kurz, Fallstudie, Zuordnung)
- [x] Schwierigkeit **~40 / 40 / 20**
- [x] Nur Inhalte aus der Zusammenfassung
- [x] Lösungen vollständig + nachvollziehbar, mit Bewertungsleitfäden
- [x] Realistisch in 60 Minuten lösbar
- [x] Fallstudie integriert **≥ 3 Kapitel** (hier 6)
