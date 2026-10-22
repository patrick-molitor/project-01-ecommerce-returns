# Solution Concept – Retourenprozess ShopNow

## 1. Ziel der Lösung

Ziel ist es, den Retourenprozess von ShopNow effizienter zu gestalten, den manuellen Bearbeitungsaufwand zu reduzieren und die Erstattungsdauer zu verkürzen.

Die Lösung setzt insbesondere bei der Bearbeitung eingegangener Retouren, der Erstattungsabwicklung und der Transparenz des Retourenstatus an.

## 2. Vorgeschlagene Prozessverbesserungen

### Automatisierte Erstattungsabwicklung

Nach Abschluss der Artikelprüfung prüft das Retourensystem automatisch, ob die Voraussetzungen für eine Erstattung erfüllt sind.

* Sind alle Voraussetzungen erfüllt, wird die Erstattung automatisch ausgelöst.
* Fehlen Voraussetzungen, wird der Fall zur manuellen Klärung an Finance übergeben.
* Tritt bei der automatischen Erstattung ein technischer Fehler auf, wird der Fall ebenfalls an Finance übergeben.

Die Erstattung muss nicht warten, bis ein Artikel aufbereitet oder wieder eingelagert wurde.

### Transparente Statusführung

Der Retourenstatus wird im System aktualisiert und steht berechtigten Mitarbeitenden sowie dem zugehörigen Kunden im Kundenportal zur Verfügung.

Während eine Erstattung bearbeitet wird, bleibt der Status auf „Erstattung wird bearbeitet“. Erst nach erfolgreicher Erstattung wird der Status auf „Erstattet“ gesetzt.

Kunden sehen ausschließlich den allgemeinen Prozess- und Erstattungsstatus ihrer eigenen Retouren, nicht die internen Behandlungsentscheidungen.

### Behandlung von Ausnahmefällen

Fälle, die nicht automatisch bearbeitet werden können, werden an die zuständige Stelle zur manuellen Klärung übergeben. Dadurch sollen problematische Fälle nachvollziehbar bearbeitet werden, ohne den regulären automatisierten Ablauf unnötig zu unterbrechen.

## 3. Erwarteter Nutzen

| Maßnahme                                            | Erwarteter Nutzen                                |
| --------------------------------------------------- | ------------------------------------------------ |
| Automatische Prüfung der Erstattungsvoraussetzungen | Weniger manuelle Prüfschritte                    |
| Automatisches Auslösen der Erstattung               | Weniger manuelle Bearbeitung durch Finance       |
| Strukturierte Behandlung von Ausnahmefällen         | Nachvollziehbare Klärung problematischer Fälle   |
| Transparente Statusführung                          | Bessere Information für Kunden und Mitarbeitende |
| Entkopplung von Erstattung und Artikelaufbereitung  | Erstattung kann früher erfolgen                  |

*Die genannten Punkte beschreiben den erwarteten Nutzen. Eine tatsächliche Verbesserung muss nach der Umsetzung anhand geeigneter Kennzahlen überprüft werden.*

## 4. Erfolgsmessung

Die Wirkung der Lösung wird anhand der definierten Business Requirements bewertet:

* **Manueller Bearbeitungsaufwand:** Reduzierung manueller Prozessschritte und manueller Erstattungsbearbeitung.
* **Aktive Bearbeitungszeit:** Reduzierung auf durchschnittlich maximal 15 Minuten je Retoure.
* **Retouren wegen unpassender Größe:** Verringerung des Anteils gegenüber der definierten Ausgangsbasis.
* **Erstattungsdauer:** Reduzierung auf durchschnittlich maximal 2,25 Tage.

## 5. Zugehörige Artefakte

* To-Be-BPMN-Modell des Retourenprozesses
* Business Requirements
* Functional Requirements
* Acceptance Criteria
* Business Rules
* SQL-basierte Datenanalyse und Findings
