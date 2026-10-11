# Functional Requirements – Retourenmanagement

## Ziel

Dieses Dokument beschreibt die funktionalen Anforderungen an die Optimierung des Retourenprozesses der ShopNow GmbH.

Die Anforderungen leiten sich aus den Business Requirements ab und beschreiben, welche Systemfunktionen zur Unterstützung eines effizienteren und transparenteren Retourenprozesses benötigt werden.

## FR-01 – Retouren automatisiert erfassen und zuordnen

### FR-01.1 – Retouren-ID erzeugen

Das System soll bei der Registrierung einer Retoure eine eindeutige Retouren-ID erzeugen und diese mit der zugehörigen Bestellung verknüpfen.

### FR-01.2 – Bearbeitungsstatus aktualisieren

Das System soll den Bearbeitungsstatus einer Retoure speichern und bei relevanten Prozessschritten aktualisieren.

### FR-01.3 – Warenbestand aktualisieren

Das System soll bei einer Entscheidung zur Wiedereinlagerung den verfügbaren Warenbestand im angebundenen Warenwirtschaftssystem aktualisieren und den Artikel als verkaufsfähig kennzeichnen.

### FR-01.4 – Erstattung automatisieren

Das System soll eine Erstattung automatisch auslösen, sobald alle definierten Voraussetzungen erfüllt sind.

Fälle, die nicht automatisiert verarbeitet werden können, sollen zur manuellen Prüfung an Finance übergeben werden.

## FR-02 – Bearbeitungszeiten erfassen

### FR-02.1 – Prozesszeitpunkte dokumentieren

Das System soll die für die Messung der aktiven Bearbeitungszeit erforderlichen Zeitpunkte dokumentieren.

### FR-02.2 – Aktive Bearbeitungszeit auswertbar machen

Das System soll die aktive Bearbeitungszeit einer Retoure auf Basis der definierten Messpunkte ermittelbar und für Auswertungen verfügbar machen.

## FR-03 – Kunden bei der Größenwahl unterstützen

### FR-03.1 – Größeninformationen bereitstellen

Das System soll Kunden zusätzlich zur bestehenden Größenauswahl relevante Maß- und Größeninformationen zur Unterstützung der Größenauswahl bereitstellen.

### FR-03.2 – Größenempfehlung bereitstellen

Das System soll auf Basis der vom Kunden angegebenen Körpermaße und der hinterlegten Maßtabelle des ausgewählten Artikels eine Größenempfehlung bereitstellen.

### FR-03.3 – Größenbezogene Retourendaten erfassen

Das System soll Retouren aufgrund einer nicht passenden Größe strukturiert erfassen und für die Auswertung bereitstellen.

Dabei sollen die Retoure und der zugehörige Artikel verknüpft, die bestellte Größe gespeichert und die Größenabweichung – zu groß oder zu klein – erfasst werden können.

Das System soll außerdem den zum zurückgesendeten Artikel hinterlegten Lieferanten für die Auswertung bereitstellen.

## FR-04 – Erstattungsdauer messen und auswerten

### FR-04.1 – Erstattungszeitpunkte dokumentieren

Das System soll den definierten Startzeitpunkt eines Erstattungsfalls sowie den Zeitpunkt der erfolgreichen Erstattung dokumentieren.

### FR-04.2 – Gesamte Erstattungsdauer ermitteln

Das System soll die gesamte Erstattungsdauer auf Basis der definierten Zeitpunkte ermittelbar und für Auswertungen verfügbar machen.

### FR-04.3 – Manuelle Bearbeitungsdauer separat erfassen

Das System soll die Dauer manueller Bearbeitung, insbesondere durch Finance, separat erfassen und auswertbar machen.

Die manuelle Bearbeitungsdauer soll nicht von der gesamten Erstattungsdauer abgezogen werden.

## Offene Fragen

- Welche Maß- und Größeninformationen werden je Produktkategorie benötigt?
- Welche Körpermaße muss ein Kunde für eine Größenempfehlung angeben?
- Wie soll das System mit fehlenden Maßangaben umgehen?
- Wie soll bei mehreren möglichen Größen oder einer nicht eindeutigen Größenempfehlung verfahren werden?
- Welche Voraussetzungen müssen erfüllt sein, damit eine Erstattung automatisch ausgelöst werden darf?
- Welches Ereignis gilt verbindlich als Startzeitpunkt für die Messung der Erstattungsdauer?
- Welche Zeitpunkte sind zur Messung der aktiven Bearbeitungszeit erforderlich und wie wird aktive Arbeitszeit von Wartezeit abgegrenzt?