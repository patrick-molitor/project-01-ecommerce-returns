# Business Rules

## Ziel

Dieses Dokument beschreibt die fachlichen Regeln für die Bearbeitung von Retouren bei der ShopNow GmbH.

Die Regeln legen fest, wie Retouren nach der Artikelprüfung behandelt werden, unter welchen Voraussetzungen eine Erstattung automatisiert werden kann und welche Ausnahmefälle eine manuelle Bearbeitung erfordern.

## BRL-01 – Entscheidung über die Behandlung retournierter Artikel

Nach der Prüfung eines retournierten Artikels wird eine Entscheidung über dessen weitere Behandlung getroffen.

Folgende Behandlungsmöglichkeiten sind vorgesehen:

* **Wiedereinlagerung:** Der Artikel wird als verkaufsfähig eingelagert.
* **Aufbereitung:** Der Artikel wird aufbereitet und anschließend als verkaufsfähig eingelagert.
* **Entsorgung:** Der Artikel wird entsorgt und nicht wieder als verkaufsfähig eingelagert.

Die Entscheidung über die Behandlung des Artikels wird dokumentiert.

## BRL-02 – Aktualisierung des Bearbeitungsstatus

Der Bearbeitungsstatus einer Retoure wird im Verlauf des Retourenprozesses aktualisiert.

Die Statusinformationen sollen den jeweiligen Bearbeitungsstand der Retoure nachvollziehbar machen.

Die konkreten Statuswerte und ihre Zuordnung zu den einzelnen Prozessschritten müssen mit dem fachlichen Prozess abgestimmt werden.

## BRL-03 – Voraussetzungen für eine automatisierte Erstattung

Eine Erstattung darf automatisch angestoßen werden, sobald alle dafür definierten fachlichen und technischen Voraussetzungen erfüllt sind.

Kann nicht eindeutig festgestellt werden, ob die Voraussetzungen erfüllt sind, wird der Fall nicht ohne weitere Prüfung automatisiert abgeschlossen.

Die konkreten Voraussetzungen für eine automatische Erstattung müssen fachlich bestätigt und dokumentiert werden.

## BRL-04 – Manuelle Bearbeitung von Ausnahmefällen

Fälle, die nicht sicher oder nicht vollständig automatisiert verarbeitet werden können, werden zur manuellen Prüfung weitergeleitet.

Folgende Ausnahmefälle sind zu berücksichtigen:

| ID    | Ausnahmefall                                                                                                                     | Vorgesehene Behandlung                                             |
| ----- | -------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------ |
| EX-01 | Eine Retoure kann nicht eindeutig einer Bestellung zugeordnet werden.                                                            | Manuelle Klärung                                                   |
| EX-02 | Bei der Artikelprüfung wird eine Abweichung festgestellt, die nicht eindeutig nach den bestehenden Regeln behandelt werden kann. | Manuelle Prüfung                                                   |
| EX-03 | Eine Retoure liegt außerhalb der geltenden Retourenregeln.                                                                       | Manuelle Prüfung und Entscheidung über das weitere Vorgehen        |
| EX-04 | Ein Erstattungsfall weist Besonderheiten auf, die eine automatisierte Bearbeitung verhindern.                                    | Manuelle Prüfung durch Finance                                     |
| EX-05 | Bei der automatisierten Verarbeitung tritt ein technischer oder buchhalterischer Fehler auf.                                     | Manuelle Klärung; eine doppelte Erstattung muss verhindert werden. |

## BRL-05 – Dokumentation von Erstattungen

Für eine Retoure soll nachvollziehbar sein, ob eine Erstattung automatisch angestoßen oder manuell bearbeitet wurde.

Bei manueller Bearbeitung durch Finance soll die entsprechende Bearbeitungsdauer separat erfasst werden können.

Die gesamte Erstattungsdauer bleibt unabhängig davon messbar. Manuelle Bearbeitungs- oder Wartezeiten werden bei der Ermittlung der Gesamtdauer nicht abgezogen.

## Offene fachliche Fragen

* Welche konkreten Voraussetzungen müssen erfüllt sein, damit eine Erstattung automatisch ausgelöst werden darf?
* Zu welchem Zeitpunkt im Retourenprozess darf die Erstattung erfolgen?
* Welche Statuswerte sind verbindlich und welchem Prozessschritt werden sie zugeordnet?
* Wie werden Retouren behandelt, die außerhalb der geltenden Retourenregeln liegen?
* Welche Arten von Abweichungen bei der Artikelprüfung erfordern zwingend eine manuelle Entscheidung?
* Wie wird bei einem technischen Fehler sichergestellt, dass keine doppelte Erstattung erfolgt?
