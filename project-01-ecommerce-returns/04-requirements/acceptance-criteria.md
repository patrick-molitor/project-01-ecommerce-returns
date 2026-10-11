# Acceptance Criteria – Retourenmanagement

## Ziel

Dieses Dokument definiert überprüfbare Akzeptanzkriterien für die funktionalen Anforderungen an den optimierten Retourenprozess der ShopNow GmbH.

Die Kriterien dienen dazu, die erwarteten Systemfunktionen eindeutig zu beschreiben und ihre spätere Umsetzung überprüfbar zu machen.

## FR-01 – Retouren automatisiert erfassen und zuordnen

### FR-01.1 – Retouren-ID erzeugen

- **AK-01.1.1:** Bei der Registrierung einer Retoure erzeugt das System eine eindeutige Retouren-ID.
- **AK-01.1.2:** Die Retouren-ID ist mit der zugehörigen Bestellung verknüpft.
- **AK-01.1.3:** Eine Retoure kann anhand ihrer Retouren-ID eindeutig identifiziert werden.

### FR-01.2 – Bearbeitungsstatus aktualisieren

- **AK-01.2.1:** Das System speichert den aktuellen Bearbeitungsstatus einer Retoure.
- **AK-01.2.2:** Bei definierten Prozessschritten wird der Bearbeitungsstatus entsprechend aktualisiert.
- **AK-01.2.3:** Der aktuelle Bearbeitungsstatus kann von berechtigten Mitarbeitenden eingesehen werden.

### FR-01.3 – Warenbestand aktualisieren

- **AK-01.3.1:** Bei der Entscheidung zur Wiedereinlagerung übermittelt das System die erforderliche Bestandsänderung an das angebundene Warenwirtschaftssystem.
- **AK-01.3.2:** Nach erfolgreicher Verarbeitung wird der Artikel im Warenwirtschaftssystem als verkaufsfähig geführt.
- **AK-01.3.3:** Kann die Bestandsänderung nicht erfolgreich verarbeitet werden, wird der Fall zur Klärung kenntlich gemacht.

### FR-01.4 – Erstattung automatisieren

- **AK-01.4.1:** Sind alle definierten Voraussetzungen erfüllt, stößt das System die Erstattung automatisch an.
- **AK-01.4.2:** Fälle, die nicht automatisiert verarbeitet werden können, werden zur manuellen Prüfung an Finance übergeben.
- **AK-01.4.3:** Das System dokumentiert, ob die Erstattung automatisch angestoßen oder manuell bearbeitet wurde.
- **AK-01.4.4:** Bei einem technischen oder buchhalterischen Fehler wird keine unkontrollierte doppelte Erstattung ausgelöst.

## FR-02 – Bearbeitungszeiten erfassen

### FR-02.1 – Prozesszeitpunkte dokumentieren

- **AK-02.1.1:** Das System dokumentiert die für die Messung der aktiven Bearbeitungszeit festgelegten Start- und Endzeitpunkte.
- **AK-02.1.2:** Die dokumentierten Zeitpunkte sind einer eindeutigen Retoure zugeordnet.
- **AK-02.1.3:** Fehlende oder nicht plausibel zuordenbare Zeitpunkte werden für die Auswertung kenntlich gemacht.

### FR-02.2 – Aktive Bearbeitungszeit auswertbar machen

- **AK-02.2.1:** Die aktive Bearbeitungszeit einer Retoure kann aus den definierten Messdaten ermittelt werden.
- **AK-02.2.2:** Die Bearbeitungszeiten mehrerer Retouren können zu einem Durchschnittswert zusammengefasst werden.
- **AK-02.2.3:** Die Berechnung berücksichtigt nur Retouren, für die die erforderlichen Messdaten vollständig vorliegen.

## FR-03 – Kunden bei der Größenwahl unterstützen

### FR-03.1 – Größeninformationen bereitstellen

- **AK-03.1.1:** Für den ausgewählten Artikel werden relevante Maß- und Größeninformationen zusätzlich zu den verfügbaren Größen angezeigt.
- **AK-03.1.2:** Die angezeigten Maße sind eindeutig beschriftet und mit Maßeinheiten versehen.
- **AK-03.1.3:** Die Größeninformationen sind eindeutig dem ausgewählten Artikel zugeordnet.

### FR-03.2 – Größenempfehlung bereitstellen

- **AK-03.2.1:** Das System vergleicht die vom Kunden angegebenen Körpermaße mit den hinterlegten Maßangaben des ausgewählten Artikels.
- **AK-03.2.2:** Die Größenempfehlung bezieht sich auf eine für den ausgewählten Artikel verfügbare Größe.
- **AK-03.2.3:** Fehlen erforderliche Körper- oder Produktmaße, gibt das System keine auf unvollständigen Daten beruhende Größenempfehlung aus.
- **AK-03.2.4:** Die Größenempfehlung ist eindeutig dem ausgewählten Artikel zugeordnet.

### FR-03.3 – Größenbezogene Retourendaten erfassen

- **AK-03.3.1:** Bei der Retourenanmeldung kann der Kunde den Retourengrund „Größe passt nicht“ auswählen.
- **AK-03.3.2:** Die Retoure ist mit dem zurückgesendeten Artikel verknüpft.
- **AK-03.3.3:** Die bestellte Größe wird für die Retoure gespeichert.
- **AK-03.3.4:** Bei Auswahl des Retourengrunds „Größe passt nicht“ kann der Kunde angeben, ob der Artikel zu groß oder zu klein ausfällt.
- **AK-03.3.5:** Der zum Artikel hinterlegte Lieferant kann der Retoure für Auswertungen zugeordnet werden.
- **AK-03.3.6:** Die erfassten Daten können nach Artikel, bestellter Größe, Größenabweichung und Lieferant ausgewertet werden.

## FR-04 – Erstattungsdauer messen und auswerten

### FR-04.1 – Erstattungszeitpunkte dokumentieren

- **AK-04.1.1:** Das System dokumentiert den definierten Startzeitpunkt eines Erstattungsfalls.
- **AK-04.1.2:** Das System dokumentiert den Zeitpunkt der erfolgreichen Erstattung.
- **AK-04.1.3:** Die Zeitpunkte sind der jeweiligen Retoure eindeutig zugeordnet.

### FR-04.2 – Gesamte Erstattungsdauer ermitteln

- **AK-04.2.1:** Die gesamte Erstattungsdauer kann aus dem definierten Startzeitpunkt und dem Zeitpunkt der erfolgreichen Erstattung ermittelt werden.
- **AK-04.2.2:** Die Erstattungsdauer mehrerer abgeschlossener Fälle kann zu einem Durchschnittswert zusammengefasst werden.
- **AK-04.2.3:** Fälle ohne dokumentierte erfolgreiche Erstattung werden nicht als abgeschlossene Erstattungsfälle in die Berechnung aufgenommen.

### FR-04.3 – Manuelle Bearbeitungsdauer separat erfassen

- **AK-04.3.1:** Die Dauer manueller Bearbeitung durch Finance wird separat dokumentiert.
- **AK-04.3.2:** Die manuelle Bearbeitungsdauer kann unabhängig von der gesamten Erstattungsdauer ausgewertet werden.
- **AK-04.3.3:** Die gesamte Erstattungsdauer wird durch manuelle Warte- oder Bearbeitungszeiten nicht rechnerisch verkürzt.