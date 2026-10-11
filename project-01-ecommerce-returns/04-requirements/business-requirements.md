# Business Requirements – Retourenmanagement

## 1. Ziel

Ziel des Projekts ist die Optimierung des Retourenprozesses der ShopNow GmbH. Durch die Analyse des bestehenden Prozesses und die Entwicklung eines optimierten Soll-Prozesses sollen der manuelle Bearbeitungsaufwand reduziert, die aktive Bearbeitungszeit verkürzt und die Erstattungsdauer verringert werden.

Zusätzlich sollen Kunden bei der Auswahl einer passenden Artikelgröße besser unterstützt werden, um Retouren aufgrund nicht passender Größen zu reduzieren.

Die Business Requirements beschreiben die geschäftlichen Ziele und den erwarteten Nutzen der Prozessoptimierung. Sie bilden die Grundlage für die anschließende Spezifizierung der Functional Requirements und der zugehörigen Akzeptanzkriterien.

---

## 2. BR-01 – Manuellen Bearbeitungsaufwand reduzieren

**Anforderung**

Der manuelle Bearbeitungsaufwand im Retourenprozess soll reduziert werden.

**Begründung**

Die Analyse des bestehenden Retourenprozesses soll aufzeigen, an welchen Stellen manuelle Tätigkeiten, wiederkehrende Bearbeitungsschritte und manuelle Statusanfragen entstehen.

Durch die Optimierung und mögliche Automatisierung geeigneter Prozessschritte sollen der operative Aufwand reduziert und die Mitarbeitenden entlastet werden.

**Erfolgsmessung**

Die Entwicklung des manuellen Bearbeitungsaufwands soll anhand folgender Kennzahlen bewertet werden:

- Anteil der Retouren mit mindestens einem relevanten manuellen Prozessschritt
- Anteil der Erstattungen, die manuell durch Finance bearbeitet werden
- Anzahl der Kundenservice-Anfragen zum Status einer Retoure im Verhältnis zur Anzahl der bearbeiteten Retouren

Die Kennzahlen sollen mit einer vor der Umsetzung ermittelten Baseline verglichen werden.

**Zielwert**

Ein konkreter Zielwert für die Reduktion ist noch festzulegen.

---

## 3. BR-02 – Aktive Bearbeitungszeit reduzieren

**Anforderung**

Die durchschnittliche aktive Bearbeitungszeit einer Retoure soll auf maximal 15 Minuten reduziert werden.

**Begründung**

Die aktive Bearbeitung einer Retoure umfasst manuelle Tätigkeiten im internen Retourenprozess. Eine Reduktion der benötigten Arbeitszeit soll die operative Effizienz verbessern und den Bearbeitungsaufwand pro Retoure verringern.

**Erfolgsmessung**

Die aktive Bearbeitungszeit wird vom Wareneingang der Retoure bis zum Abschluss der Prüfung und der Entscheidung über die weitere Behandlung des Artikels betrachtet.

Als Abschluss der Prüfung gilt die Entscheidung, ob der Artikel:
- als verkaufsfähig eingelagert wird,
- zur Aufbereitung vorgesehen ist oder
- entsorgt wird.

Die Messung soll sich auf vollständig bearbeitete Retouren beziehen. Die durchschnittliche aktive Bearbeitungszeit wird für den definierten Auswertungszeitraum ermittelt.

**Zielwert**

Maximal 15 Minuten durchschnittliche aktive Bearbeitungszeit pro vollständig bearbeiteter Retoure.

---

## 4. BR-03 – Unterstützung bei der Größenauswahl verbessern

**Anforderung**

Kunden sollen bei der Auswahl eines passenden Artikels und einer passenden Größe besser unterstützt werden.

**Begründung**

Die Analyse der Retourengründe zeigt, dass nicht passende Größen einen wesentlichen Anteil der Retouren ausmachen.

Durch zusätzliche Größeninformationen und eine auf Artikelmaßen basierende Größenempfehlung sollen Kunden besser bei der Auswahl einer passenden Größe unterstützt werden.

**Ausgangsbasis**

In der analysierten Stichprobe entfielen 60 von 180 Retouren auf den Rückgabegrund „Größe passt nicht“. Dies entspricht einem Anteil von 33,33 % aller erfassten Retouren.

Dieser Wert dient als projektbezogene Baseline für die weitere Analyse. Er ist kein allgemeiner Branchenbenchmark.

**Erfolgsmessung**

Der Anteil der Retouren mit dem Rückgabegrund „Größe passt nicht“ soll nach Einführung der vorgesehenen Unterstützungsmaßnahmen gegenüber der Baseline reduziert werden.

Die Auswertung soll über einen vergleichbaren Zeitraum vor und nach der Umsetzung erfolgen.

**Zielwert**

Ein konkreter Zielwert für die Reduktion ist noch festzulegen.

**Hinweis zur Interpretation**

Der Anteil von 33,33 % beschreibt den Anteil größenbedingter Retouren an allen Retouren der analysierten Stichprobe. Er entspricht nicht der größenbedingten Retourenquote bezogen auf alle verkauften Artikel.

---

## 5. BR-04 – Erstattungsdauer reduzieren

**Anforderung**

Die durchschnittliche Erstattungsdauer einer Retoure soll auf maximal 2,25 Kalendertage reduziert werden.

**Begründung**

Eine kürzere Erstattungsdauer soll die Abwicklung von Retouren verbessern und dazu beitragen, dass Kunden ihre Erstattung schneller erhalten.

Die Analyse der bestehenden Daten dient dazu, die aktuelle Erstattungsdauer zu bestimmen und Ansatzpunkte für die Prozessoptimierung zu identifizieren.

**Messdefinition**

Die Erstattungsdauer beginnt mit dem Wareneingang der Retoure bei ShopNow und endet mit der erfolgreichen Erstattung.

Der Zeitraum zwischen Retourenanmeldung und Wareneingang wird nicht in diese Kennzahl einbezogen, da er außerhalb des unmittelbaren Einflussbereichs der internen Retourenbearbeitung liegt.

Die Dauer manueller Bearbeitung, insbesondere durch Finance, wird zusätzlich separat erfasst und ausgewertet. Sie wird nicht von der gesamten Erstattungsdauer abgezogen.

**Ausgangsbasis**

Die bisherige Datenanalyse ergab eine durchschnittliche Erstattungsdauer von 4,69 Kalendertagen für 110 erstattete Retouren.

Die Baseline basiert auf dem Zeitraum zwischen Wareneingang und erfolgreicher Erstattung in den analysierten Projektdaten.

**Zielwert**

Maximal 2,25 Kalendertage durchschnittliche Erstattungsdauer.

Dieser Wert ist ein internes Projektziel und kein nachgewiesener Branchenbenchmark.

---

## 6. Zusammenfassung der Business Requirements

| ID | Business Requirement | Kennzahl | Ausgangsbasis | Zielwert |
|---|---|---|---|---|
| BR-01 | Manuellen Bearbeitungsaufwand reduzieren | Manuelle Prozessschritte, manuelle Finance-Bearbeitung und Statusanfragen | Noch festzulegen | Noch festzulegen |
| BR-02 | Aktive Bearbeitungszeit reduzieren | Durchschnittliche aktive Bearbeitungszeit pro Retoure | 20,17 Minuten laut bisheriger Datenanalyse; Messdefinition noch abzugleichen | Maximal 15 Minuten |
| BR-03 | Unterstützung bei der Größenauswahl verbessern | Anteil der Retouren mit Grund „Größe passt nicht“ | 33,33 % der analysierten Retouren | Noch festzulegen |
| BR-04 | Erstattungsdauer reduzieren | Durchschnittliche Dauer vom Wareneingang bis zur erfolgreichen Erstattung | 4,69 Kalendertage für 110 erstattete Retouren | Maximal 2,25 Kalendertage |

---

## 7. Offene Entscheidungen

Vor der abschließenden Freigabe der Business Requirements sind folgende Punkte zu klären:

- **BR-01:** Welche konkrete Reduktion des manuellen Bearbeitungsaufwands soll erreicht werden?
- **BR-02:** Entspricht die im Datensatz erfasste Bearbeitungszeit tatsächlich der definierten aktiven Bearbeitungszeit?
- **BR-03:** Welcher Zielwert für die Reduktion größenbedingter Retouren ist fachlich begründet und realistisch?
- **BR-04:** Ist die Messdefinition für alle relevanten Stakeholder nachvollziehbar und abgestimmt?

Die offenen Entscheidungen sollen dokumentiert und vor einer tatsächlichen Umsetzung mit den relevanten Stakeholdern abgestimmt werden.