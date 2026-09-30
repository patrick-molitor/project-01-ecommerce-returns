# Business Findings

## 1. Retourengründe

### Beobachtung

Der häufigste Retourengrund im untersuchten Datensatz ist „Größe passt nicht“ mit 39 von insgesamt 180 Retouren (21,67 %).

| Retourengrund      | Retouren |  Anteil |
| ------------------ | -------: | ------: |
| Größe passt nicht  |       39 | 21,67 % |
| Artikel beschädigt |       37 | 20,56 % |
| Gefällt nicht      |       36 | 20,00 % |
| Falsch geliefert   |       36 | 20,00 % |
| Qualitätsmangel    |       32 | 17,78 % |

### Interpretation

Größenbezogene Probleme stellen im untersuchten Datensatz den häufigsten einzelnen Retourengrund dar.

### Hypothese / weiterer Analysebedarf

Es sollte untersucht werden, ob Verbesserungen bei Größeninformationen, Größentabellen oder der Größenberatung dazu beitragen könnten, Retouren zu reduzieren.

Die vorhandenen Daten belegen jedoch nicht, dass fehlende oder unzureichende Größeninformationen die Ursache sind.

---

## 2. Retourenquote nach Produktkategorie

### Beobachtung

Die Retourenquoten der untersuchten Produktkategorien liegen relativ nah beieinander.

| Kategorie   | Bestellungen | Retouren | Retourenquote |
| ----------- | -----------: | -------: | ------------: |
| Schuhe      |          320 |       59 |       18,44 % |
| Bekleidung  |          280 |       51 |       18,21 % |
| Sport       |          160 |       29 |       18,13 % |
| Accessoires |          240 |       41 |       17,08 % |

### Interpretation

Die Produktkategorie allein zeigt in diesem Datensatz nur geringe Unterschiede bei der Retourenquote.

Daher erscheint es sinnvoll, weitere Merkmale wie Retourengrund oder Kundensegment in die Analyse einzubeziehen.

### Hypothese / weiterer Analysebedarf

Weitere Analysen könnten untersuchen, ob bestimmte Retourengründe innerhalb einzelner Kategorien besonders häufig auftreten und ob daraus gezielte Optimierungsmaßnahmen abgeleitet werden können.

---

## 3. Unterschiedliche Retourengründe je Produktkategorie

### Beobachtung

Der häufigste Retourengrund unterscheidet sich je Produktkategorie:

| Kategorie   | Häufigster Retourengrund | Anzahl |
| ----------- | ------------------------ | -----: |
| Accessoires | Größe passt nicht        |     12 |
| Bekleidung  | Größe passt nicht        |     12 |
| Schuhe      | Gefällt nicht            |     16 |
| Sport       | Artikel beschädigt       |      7 |

### Interpretation

Die Analyse zeigt unterschiedliche Muster zwischen den Produktkategorien.

Eine einheitliche Optimierungsmaßnahme für alle Kategorien könnte daher weniger zielgerichtet sein als kategorienbezogene Maßnahmen.

### Hypothese / weiterer Analysebedarf

Für jede Kategorie sollten die jeweils dominierenden Retourengründe hinsichtlich ihrer möglichen Ursachen untersucht werden.

Beispielsweise könnten für Bekleidung und Accessoires Größeninformationen untersucht werden, während bei Sportartikeln der Prozess rund um beschädigte Artikel näher betrachtet werden könnte.

Diese Zusammenhänge stellen Hypothesen dar und müssen durch weitere Prozess- oder Produktdaten validiert werden.

---

## 4. Retourenquote nach Kundensegment

### Beobachtung

Das Standard-Kundensegment weist im untersuchten Datensatz eine höhere Retourenquote auf als das Premium-Segment.

| Kundensegment | Bestellungen | Retouren | Retourenquote |
| ------------- | -----------: | -------: | ------------: |
| Premium       |          502 |       82 |       16,33 % |
| Standard      |          498 |       98 |       19,68 % |

Die Differenz beträgt 3,35 Prozentpunkte.

### Interpretation

Das Kundensegment kann als relevantes Merkmal für eine weiterführende Retourenanalyse betrachtet werden.

### Hypothese / weiterer Analysebedarf

Es sollte untersucht werden, ob sich die Retourengründe zwischen den Kundensegmenten unterscheiden.

Aus den vorliegenden Daten kann jedoch nicht abgeleitet werden, dass das Kundensegment selbst die Ursache für die unterschiedliche Retourenquote ist.

---

## 5. Bearbeitungszeit nach Retourengrund

### Beobachtung

Retouren aufgrund von Falschlieferungen weisen mit durchschnittlich 22,41 Minuten die höchste aktive Bearbeitungszeit auf.

| Retourengrund      | Retouren | Ø Bearbeitungszeit |
| ------------------ | -------: | -----------------: |
| Falsch geliefert   |       36 |          22,41 min |
| Qualitätsmangel    |       32 |          21,68 min |
| Größe passt nicht  |       39 |          20,90 min |
| Gefällt nicht      |       36 |          20,71 min |
| Artikel beschädigt |       37 |          19,26 min |

### Interpretation

Im untersuchten Datensatz unterscheiden sich die durchschnittlichen aktiven Bearbeitungszeiten je Retourengrund.

Falschlieferungen weisen dabei den höchsten durchschnittlichen Bearbeitungsaufwand auf.

### Hypothese / weiterer Analysebedarf

Der Prozess für Falschlieferungen sollte genauer untersucht werden, um mögliche zusätzliche Bearbeitungsschritte oder Übergaben zu identifizieren.

Die Analyse zeigt eine Korrelation zwischen Retourengrund und Bearbeitungszeit, belegt jedoch keine konkrete Ursache.

---

## 6. Aktive Bearbeitungszeit vs. Rückerstattungsdauer

### Beobachtung

Die durchschnittliche aktive Bearbeitungszeit einer Retoure beträgt 20,97 Minuten.

Zwischen Wareneingang und Rückerstattung vergehen dagegen durchschnittlich 3,32 Tage.

### Interpretation

Damit besteht ein deutlicher Unterschied zwischen der tatsächlich gemessenen aktiven Bearbeitungszeit und der gesamten Dauer bis zur Rückerstattung.

Dies deutet darauf hin, dass neben der eigentlichen Bearbeitung weitere Zeitanteile im Prozess relevant sein können.

### Hypothese / weiterer Analysebedarf

Der Zeitraum zwischen Wareneingang und Rückerstattung sollte in einzelne Prozessabschnitte zerlegt werden.

Dabei könnten beispielsweise folgende Aspekte untersucht werden:

* Wartezeit bis zur Prüfung
* Dauer der Prüfung
* Wartezeit bis zur Entscheidung
* Übergaben zwischen Abteilungen
* Zeitpunkt der Rückerstattung
* mögliche manuelle Prozessschritte

Die vorhandenen Daten erlauben keine eindeutige Aussage darüber, welcher dieser Faktoren für die Verzögerung verantwortlich ist.

---

# Zusammenfassung der wichtigsten Findings

Die Analyse des synthetischen Retourendatensatzes zeigt mehrere potenzielle Ansatzpunkte für eine weitere Prozessanalyse:

1. „Größe passt nicht“ ist der häufigste einzelne Retourengrund.
2. Die Retourenquoten der Produktkategorien unterscheiden sich nur moderat.
3. Die dominierenden Retourengründe unterscheiden sich zwischen den Kategorien.
4. Das Standard-Kundensegment weist eine höhere Retourenquote als das Premium-Segment auf.
5. Falschlieferungen weisen die höchste durchschnittliche aktive Bearbeitungszeit auf.
6. Die durchschnittliche aktive Bearbeitungszeit von 20,97 Minuten steht einer durchschnittlichen Dauer von 3,32 Tagen bis zur Rückerstattung gegenüber.

Die Findings dienen als Grundlage für die anschließende Prozessanalyse und die Visualisierung der wichtigsten Kennzahlen in Power BI.
