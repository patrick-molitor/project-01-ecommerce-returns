# Requirements Traceability Matrix

## Ziel

Diese Matrix stellt die Beziehungen zwischen den Business Requirements (BR), den Functional Requirements (FR) und den zugehörigen Acceptance Criteria (AK) dar.

Sie unterstützt die Nachvollziehbarkeit der Anforderungen und hilft dabei, Lücken oder nicht zugeordnete Anforderungen zu erkennen.

## Traceability Matrix

| Business Requirement | Functional Requirement | Zugehörige Acceptance Criteria | Zusammenhang |
|---|---|---|---|
| BR-01 – Manuellen Bearbeitungsaufwand reduzieren | FR-01.1 – Retouren-ID erzeugen | AK-01.1.1–AK-01.1.3 | Eindeutige Zuordnung unterstützt die automatisierte Bearbeitung. |
| BR-01, BR-04 | FR-01.2 – Bearbeitungsstatus aktualisieren | AK-01.2.1–AK-01.2.3 | Der Status macht den Bearbeitungsstand nachvollziehbar. |
| BR-01 | FR-01.3 – Warenbestand aktualisieren | AK-01.3.1–AK-01.3.3 | Die Bestandsaktualisierung reduziert manuelle Folgearbeiten. |
| BR-01, BR-04 | FR-01.4 – Erstattung automatisieren | AK-01.4.1–AK-01.4.4 | Die Automatisierung reduziert manuelle Bearbeitung und soll die Erstattungsdauer verkürzen. |
| BR-02 | FR-02.1 – Prozesszeitpunkte dokumentieren | AK-02.1.1–AK-02.1.3 | Die Zeitpunkte bilden die Grundlage für die Messung. |
| BR-02 | FR-02.2 – Aktive Bearbeitungszeit auswertbar machen | AK-02.2.1–AK-02.2.3 | Die Auswertung ermöglicht die Überprüfung des Zielwerts von maximal 15 Minuten. |
| BR-03 | FR-03.1 – Größeninformationen bereitstellen | AK-03.1.1–AK-03.1.3 | Die Informationen unterstützen die Auswahl einer passenden Größe. |
| BR-03 | FR-03.2 – Größenempfehlung bereitstellen | AK-03.2.1–AK-03.2.4 | Die Größenempfehlung unterstützt die Auswahl einer passenden Größe. |
| BR-03 | FR-03.3 – Größenbezogene Retourendaten erfassen | AK-03.3.1–AK-03.3.6 | Die Daten ermöglichen eine strukturierte Analyse größenbezogener Retouren. |
| BR-04 | FR-04.1 – Erstattungszeitpunkte dokumentieren | AK-04.1.1–AK-04.1.3 | Die Zeitpunkte bilden die Grundlage für die Messung der Erstattungsdauer. |
| BR-04 | FR-04.2 – Gesamte Erstattungsdauer ermitteln | AK-04.2.1–AK-04.2.3 | Die Auswertung ermöglicht die Überprüfung des Zielwerts von maximal 2,25 Tagen. |
| BR-01, BR-04 | FR-04.3 – Manuelle Bearbeitungsdauer separat erfassen | AK-04.3.1–AK-04.3.3 | Die manuelle Bearbeitung wird sichtbar, während die gesamte Erstattungsdauer unverändert gemessen wird. |

## Offene Punkte

- Die Messdefinition für BR-02 muss fachlich bestätigt werden.
- Der Startzeitpunkt für die Messung der Erstattungsdauer bei BR-04 muss fachlich bestätigt werden.
- Die Voraussetzungen für eine automatisierte Erstattung müssen abschließend definiert werden.
- Die fachlichen Regeln für eine Größenempfehlung müssen konkretisiert werden.

## Verwendung

Die Matrix dient als Grundlage für die Überprüfung, ob alle Business Requirements durch funktionale Anforderungen unterstützt werden und ob für die funktionalen Anforderungen überprüfbare Akzeptanzkriterien vorhanden sind.