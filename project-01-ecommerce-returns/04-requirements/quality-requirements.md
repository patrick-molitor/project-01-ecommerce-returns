# Quality Requirements – Retourenmanagement

## 1. Ziel und Geltungsbereich

Dieses Dokument beschreibt ausgewählte Qualitätsanforderungen für die geplante Optimierung des Retourenprozesses der ShopNow GmbH.

Die Qualitätsanforderungen ergänzen die Functional Requirements um übergreifende Anforderungen an Datenintegrität, Zuverlässigkeit, Nachvollziehbarkeit und Benutzbarkeit.

Die Anforderungen sind Projektvorschläge und müssen vor einer tatsächlichen Umsetzung mit den relevanten Stakeholdern abgestimmt werden.

---

## QR-01 – Vermeidung doppelter Erstattungen

**Qualitätsmerkmal:** Zuverlässigkeit und Datenintegrität  
**Priorität:** Hoch  
**Status:** Vorgeschlagen  
**Bezug zu Functional Requirements:** FR-01.4 – Automatische Erstattung

### Anforderung

Das System muss sicherstellen, dass derselbe Erstattungsfall nicht mehrfach erfolgreich erstattet wird, auch wenn die Verarbeitung aufgrund eines technischen Fehlers wiederholt wird.

### Begründung

Doppelte Erstattungen können finanzielle Schäden verursachen. Bei einer automatisierten Erstattungsbearbeitung muss deshalb sichergestellt werden, dass wiederholte Verarbeitungsversuche nicht zu mehrfachen Erstattungen führen.

### Akzeptanzkriterien

- **AK-QR-01.1:** Wird derselbe Erstattungsfall erneut verarbeitet, darf dadurch keine zweite Erstattung ausgelöst werden.
- **AK-QR-01.2:** Bei einem technischen Fehler muss der Erstattungsstatus nachvollziehbar bleiben.
- **AK-QR-01.3:** Ein fehlgeschlagener Erstattungsversuch muss erkennbar sein und eine kontrollierte erneute Verarbeitung oder manuelle Klärung ermöglichen.

### Offene Punkte

- Welche technischen Fehlerfälle müssen bei der erneuten Verarbeitung berücksichtigt werden?
- Wie wird sichergestellt, dass der Status einer Erstattung auch bei einem Fehler zwischen System und Zahlungsdienstleister korrekt bleibt?

---

## QR-02 – Eindeutige Zuordnung und konsistente Verarbeitung von Retourendaten

**Qualitätsmerkmal:** Datenintegrität  
**Priorität:** Hoch  
**Status:** Vorgeschlagen  
**Bezug zu Functional Requirements:** FR-01.1 – Retoure eindeutig identifizieren und Bestellung zuordnen

### Anforderung

Das System muss sicherstellen, dass jede erfasste Retoure eindeutig identifiziert und der zugehörigen Bestellung zugeordnet werden kann. Die Zuordnung muss während der weiteren Retourenbearbeitung erhalten bleiben.

### Begründung

Eine korrekte Zuordnung von Retouren zu Bestellungen und Produkten ist eine Voraussetzung für die zuverlässige Retourenbearbeitung und die korrekte Auswertung der Retourendaten.

Fehlerhafte Zuordnungen können zu falschen Bearbeitungsentscheidungen und verfälschten Analyseergebnissen führen.

### Akzeptanzkriterien

- **AK-QR-02.1:** Jede erfasste Retoure besitzt eine eindeutige Retouren-ID.
- **AK-QR-02.2:** Eine Retoure darf nur einer eindeutig identifizierten Bestellung zugeordnet werden.
- **AK-QR-02.3:** Kann keine eindeutige Zuordnung hergestellt werden, darf die Retoure nicht automatisch weiterverarbeitet werden. Sie muss zur manuellen Klärung gekennzeichnet werden.

### Offene Punkte

- Welche Prüfungen müssen bei der Zuordnung zwischen Retoure und Bestellung durchgeführt werden?
- Welche Daten müssen bei einer fehlerhaften oder unvollständigen Zuordnung für die manuelle Klärung verfügbar sein?

---

## QR-03 – Nachvollziehbarkeit der Retourenbearbeitung

**Qualitätsmerkmal:** Nachvollziehbarkeit und Auditierbarkeit  
**Priorität:** Hoch  
**Status:** Vorgeschlagen  
**Bezug zu Functional Requirements:** FR-01.2 und FR-01.4 sowie die definierten Exception Flows

### Anforderung

Das System muss relevante Statusänderungen, Erstattungsversuche und manuelle Eingriffe an einer Retoure nachvollziehbar dokumentieren.

### Begründung

Die Dokumentation relevanter Bearbeitungsschritte ermöglicht die Analyse von Verzögerungen, Fehlerfällen und manuellen Eingriffen.

Sie unterstützt damit die Untersuchung des manuellen Bearbeitungsaufwands und der Erstattungsdauer.

### Akzeptanzkriterien

- **AK-QR-03.1:** Relevante Statusänderungen werden mit Zeitpunkt und zugehörigem Retourenfall dokumentiert.
- **AK-QR-03.2:** Automatische Erstattungsversuche und deren Ergebnisse werden nachvollziehbar dokumentiert.
- **AK-QR-03.3:** Manuelle Eingriffe werden mit Zeitpunkt, Bearbeitungsart und verantwortlicher Rolle dokumentiert.
- **AK-QR-03.4:** Die dokumentierten Informationen können zur Analyse von Bearbeitungsverläufen und Fehlerfällen ausgewertet werden.

### Offene Punkte

- Welche Ereignisse müssen zwingend dokumentiert werden?
- Welche Informationen dürfen im Rahmen der Protokollierung gespeichert werden?
- Welche Aufbewahrungsfristen und Zugriffsberechtigungen sind erforderlich?

---

## QR-04 – Verständlichkeit der Größenempfehlung

**Qualitätsmerkmal:** Benutzbarkeit  
**Priorität:** Hoch  
**Status:** Vorgeschlagen  
**Bezug zu Functional Requirements:** FR-04.1 und FR-04.2

### Anforderung

Das System muss die Größenempfehlung und die zugehörigen Größeninformationen so darstellen, dass Kunden die Empfehlung dem ausgewählten Artikel eindeutig zuordnen und nachvollziehen können.

### Begründung

Die Bereitstellung einer Größenempfehlung allein stellt nicht sicher, dass Kunden diese verstehen und sinnvoll nutzen können.

Eine eindeutige Zuordnung zum ausgewählten Artikel und eine verständliche Darstellung der relevanten Größeninformationen sollen die Nutzung der Größenempfehlung unterstützen.

### Akzeptanzkriterien

- **AK-QR-04.1:** Die Größenempfehlung ist eindeutig dem ausgewählten Artikel zugeordnet.
- **AK-QR-04.2:** Die empfohlene Größe ist klar erkennbar und entspricht einer für den ausgewählten Artikel verfügbaren Größe.
- **AK-QR-04.3:** Die für die Empfehlung relevanten Maß- und Größeninformationen werden verständlich bezeichnet und mit den erforderlichen Maßeinheiten dargestellt.
- **AK-QR-04.4:** Wenn keine zuverlässige Empfehlung erstellt werden kann, wird keine scheinbar eindeutige Empfehlung ausgegeben.

### Offene Punkte

- Wie soll die Verständlichkeit der Größenempfehlung überprüft werden?
- Welche Informationen benötigt der Kunde, um die Empfehlung nachvollziehen zu können?
- Wie soll das System mit unvollständigen oder widersprüchlichen Größeninformationen umgehen?

---

## 5. Traceability und weitere Abstimmung

Die Qualitätsanforderungen ergänzen die bestehenden Business Requirements und Functional Requirements.

Vor der Umsetzung sind insbesondere folgende Punkte zu bearbeiten:

1. Die Qualitätsanforderungen mit den zugehörigen Functional Requirements und Business Requirements verknüpfen.
2. Überschneidungen zwischen Qualitätsanforderungen, Functional Requirements und bestehenden Akzeptanzkriterien prüfen.
3. Die offenen Punkte mit den relevanten Stakeholdern abstimmen.
4. Die Akzeptanzkriterien bei Bedarf präzisieren und für die spätere Überprüfung vorbereiten.

Die Qualitätsanforderungen gelten bis zur fachlichen Abstimmung als Vorschläge für die geplante Lösung.