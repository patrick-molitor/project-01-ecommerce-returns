# Executive Summary – Optimierung des Retourenprozesses bei ShopNow GmbH

## Ausgangssituation und Zielsetzung

Die fiktive ShopNow GmbH ist ein Onlinehändler für Mode- und Lifestyleprodukte. Im betrachteten Szenario ist die Retourenquote von 12 % im Jahr 2025 auf 18 % im Jahr 2026 gestiegen. Gleichzeitig haben sich die durchschnittlichen Retourenkosten von 7,80 € auf 9,20 € und die manuelle Bearbeitungszeit von 11 auf 15 Minuten erhöht.

Ziel des Projekts ist es, den bestehenden Retourenprozess zu analysieren, Optimierungspotenziale zu identifizieren und ein fachliches Lösungskonzept zu entwickeln. Im Mittelpunkt stehen die Reduzierung manueller Bearbeitungsschritte, eine kürzere Erstattungsdauer und eine bessere Unterstützung bei der Auswahl passender Artikel und Größen.

## Analyse und wichtigste Erkenntnisse

Für die Analyse wurden ein Datenmodell erstellt und synthetische Daten mit SQL ausgewertet. Die Ergebnisse zeigen folgende Ansatzpunkte:

* **Retourenquote:** 180 Retouren bei 1.000 Bestellungen entsprechen einer Retourenquote von 18 % im analysierten Datensatz.
* **Retourengründe:** Mit 33,3 % ist „Größe passt nicht“ der häufigste erfasste Retourengrund.
* **Produktkategorien:** Bekleidung weist mit 19,64 % die höchste Retourenquote der vier betrachteten Kategorien auf.
* **Aktive Bearbeitungszeit:** Die durchschnittliche aktive Bearbeitungszeit beträgt im Datensatz rund 20,17 Minuten.
* **Erstattungsdauer:** Für 110 erfolgreich erstattete Retouren ergibt sich eine durchschnittliche Dauer von rund 4,69 Tagen.

Die Ergebnisse weisen auf Ansatzpunkte bei der Größenunterstützung, der Prozessbearbeitung und der Erstattungsabwicklung hin. Da die Daten synthetisch sind, dienen die Kennzahlen der Demonstration der Analysemethodik und sind nicht als reale Unternehmenswerte zu verstehen.

## Vorgeschlagenes Lösungskonzept

Auf Basis der Prozess- und Anforderungsanalyse wurde ein To-Be-Prozess entwickelt. Die wesentlichen Maßnahmen sind:

* Automatische Prüfung der Voraussetzungen für eine Erstattung und automatisches Auslösen der Erstattung, sofern diese erfüllt sind.
* Übergabe von Ausnahmefällen oder technischen Fehlern an Finance zur manuellen Klärung.
* Aktualisierung des Retourenstatus und Bereitstellung des Status für berechtigte Mitarbeitende sowie für den jeweils zugehörigen Kunden.
* Entkopplung der Erstattung von der Artikelaufbereitung, damit eine Erstattung nicht unnötig auf die Wiedereinlagerung oder Aufbereitung warten muss.
* Bessere Unterstützung der Kunden bei der Größenwahl sowie strukturierte Erfassung größenbezogener Retourendaten.

## Anforderungen und Erfolgsmessung

Die Business Requirements wurden in funktionale Anforderungen, Akzeptanzkriterien und Business Rules überführt und in einer Traceability Matrix miteinander verknüpft.

Für die Erfolgsmessung wurden folgende Zielsetzungen definiert:

* Reduzierung des manuellen Bearbeitungsaufwands.
* Reduzierung der durchschnittlichen aktiven Bearbeitungszeit auf maximal 15 Minuten.
* Verringerung des Anteils größenbedingter Retouren gegenüber der definierten Ausgangsbasis.
* Reduzierung der durchschnittlichen Erstattungsdauer auf maximal 2,25 Tage.

Die genaue Messdefinition für die aktive Bearbeitungszeit und den Startzeitpunkt der Erstattungsdauer sowie der konkrete Zielwert für größenbedingte Retouren müssen fachlich noch bestätigt beziehungsweise festgelegt werden.

## Erstellte Projektartefakte

* Stakeholderanalyse
* As-Is- und To-Be-BPMN-Prozessmodelle
* Datenmodell und SQL-basierte Datenanalyse
* Business Requirements, Functional Requirements und Akzeptanzkriterien
* Business Rules und Requirements Traceability Matrix
* Power-BI-Dashboard zur Visualisierung zentraler Retourenkennzahlen
* Fachliches Lösungskonzept

**Projektstatus:** Fachliche Analyse, Anforderungsdokumentation und erster Lösungsvorschlag sind erstellt. Die vorgeschlagenen Maßnahmen wurden noch nicht implementiert; ihre tatsächliche Wirkung muss anhand der definierten Kennzahlen überprüft werden.
