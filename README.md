# Optimierung des E-Commerce-Retourenprozesses

**Portfolio-Projekt | Business Analysis · Requirements Engineering · BPMN · SQL · Power BI**

## Projektüberblick

In diesem Projekt analysiere ich den Retourenprozess des fiktiven Onlinehändlers ShopNow GmbH. Ziel ist es, Schwachstellen im bestehenden Prozess zu identifizieren, Geschäftsdaten auszuwerten und ein fachliches Lösungskonzept zur Prozessoptimierung zu entwickeln.

Das Projekt bildet einen durchgängigen Business-Analysis- und Requirements-Engineering-Prozess ab – von der Problemdefinition über die Prozess- und Datenanalyse bis zur Anforderungsdokumentation und zum Lösungsvorschlag.

## Ausgangssituation

Im zugrunde liegenden Geschäftsszenario haben sich die Retourenquote, die durchschnittlichen Retourenkosten und die manuelle Bearbeitungszeit erhöht.

| Kennzahl                         |    2025 |    2026 |
| -------------------------------- | ------: | ------: |
| Retourenquote                    |    12 % |    18 % |
| Durchschnittliche Retourenkosten |  7,80 € |  9,20 € |
| Manuelle Bearbeitungszeit        | 11 Min. | 15 Min. |

**Projektziele:**

* Manuellen Bearbeitungsaufwand reduzieren
* Erstattungsdauer verkürzen
* Kunden bei der Auswahl passender Artikel und Größen besser unterstützen
* Transparenz über den Retourenstatus verbessern

## Vorgehen und Methoden

1. **Business Analysis:** Geschäftsproblem, Projektumfang und Stakeholder analysieren
2. **Prozessmodellierung:** Bestehenden Prozess (As-Is) mit BPMN modellieren
3. **Datenanalyse:** Retourendaten mit SQL/SQLite untersuchen und relevante Kennzahlen ableiten
4. **Requirements Engineering:** Business Requirements, Functional Requirements, Acceptance Criteria und Business Rules definieren
5. **Traceability:** Anforderungen und Akzeptanzkriterien in einer Requirements Traceability Matrix verknüpfen
6. **Soll-Konzept:** Optimierten Prozess (To-Be) modellieren und Lösungsvorschläge dokumentieren
7. **Reporting:** Zentrale Kennzahlen in einem Power-BI-Dashboard visualisieren

## Wichtigste Analyseergebnisse

Die SQL-Analyse der synthetischen Daten ergab:

* **Retourenquote:** 18 % bei 180 Retouren aus 1.000 Bestellungen
* **Häufigster Retourengrund:** „Größe passt nicht“ mit 33,3 % aller Retouren
* **Höchste Retourenquote nach Produktkategorie:** Bekleidung mit 19,64 %
* **Durchschnittliche aktive Bearbeitungszeit:** 20,17 Minuten
* **Durchschnittliche Erstattungsdauer:** 4,69 Tage bei 110 erfolgreich erstatteten Retouren

Die Ergebnisse dienen dazu, mögliche Ansatzpunkte für Prozessverbesserungen zu identifizieren. Sie belegen noch keine tatsächliche Wirkung der vorgeschlagenen Maßnahmen.

## Lösungskonzept

Der entwickelte Lösungsvorschlag umfasst:

* Automatische Prüfung der Voraussetzungen für eine Erstattung
* Automatische Auslösung geeigneter Erstattungen
* Übergabe von Ausnahmefällen und technischen Fehlern an Finance
* Transparente Statusführung für berechtigte Mitarbeitende und Kunden
* Entkopplung der Erstattung von der anschließenden Aufbereitung oder Wiedereinlagerung
* Bessere Unterstützung bei der Größenauswahl und strukturierte Auswertung größenbedingter Retouren

## Projektergebnisse

Im Repository finden sich folgende Artefakte:

* Business Problem und Scope Definition
* Stakeholder Analysis
* As-Is- und To-Be-BPMN-Modelle
* Datenmodell und SQL-Abfragen
* Business Requirements und Functional Requirements
* Acceptance Criteria und Business Rules
* Requirements Traceability Matrix
* Analyseergebnisse und Findings
* Power-BI-Dashboard
* Solution Concept und Executive Summary

## Technologien und Kompetenzen

| Bereich                  | Anwendung                                                       |
| ------------------------ | --------------------------------------------------------------- |
| Business Analysis        | Problemdefinition, Stakeholderanalyse, KPI-Analyse              |
| Requirements Engineering | Anforderungen, Akzeptanzkriterien, Business Rules, Traceability |
| Prozessmodellierung      | BPMN, As-Is-/To-Be-Modellierung                                 |
| Datenanalyse             | SQL, SQLite, Datenmodellierung                                  |
| Reporting                | Power BI, KPI-Visualisierung                                    |
| Versionsverwaltung       | Git, GitHub                                                     |

## Projektstatus und Datenbasis

Die Prozess- und Datenanalyse, die Anforderungsdokumentation, das Dashboard und das erste Lösungskonzept sind erstellt. Die vorgeschlagenen Maßnahmen wurden nicht technisch implementiert. Ihre tatsächliche Wirkung müsste nach einer Umsetzung anhand der definierten Kennzahlen überprüft werden.

**Hinweis:** ShopNow GmbH und die verwendeten Daten sind fiktiv. Die Daten wurden für dieses Portfolio-Projekt erstellt und stellen keine realen Unternehmensdaten dar.
