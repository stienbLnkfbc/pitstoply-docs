# Öffentliche Buchungsseite

Ihre Buchungsseite ermöglicht es Ihren Kunden, rund um die Uhr online Termine zu buchen.

## Auf Ihre Seite zugreifen

### URL Ihrer Seite

Ihre Buchungsseite ist erreichbar unter:

```
https://pitstoply.ch/ihr-slug
```

**Beispiel:** `https://pitstoply.ch/garage-mueller-ag`

### Ihren Slug finden

1. Gehen Sie zu **Einstellungen > Identität**
2. Das Feld **Slug** zeigt Ihre Kennung

---

## Was Ihre Kunden sehen

### Schritt 1: Serviceauswahl

Der Kunde sieht die von Ihnen angebotenen Services:
- Räderwechsel
- Reifenwechsel
- Andere konfigurierte Services

Jeder Service zeigt:
- Den Namen
- Die geschätzte Dauer
- Den Richtpreis (falls konfiguriert)

### Schritt 2: Filialauswahl (falls mehrere)

Wenn Sie mehrere Filialen haben, wählt der Kunde, wohin er kommen möchte:
- Name der Filiale
- Adresse

### Schritt 3: Datumswahl

Ein Kalender wird angezeigt mit:
- Verfügbaren Tagen in Farbe
- Ausgebuchten oder geschlossenen Tagen ausgegraut
- Aktuellem und folgenden Monaten

### Schritt 4: Zeitfensterwahl

Die verfügbaren Zeitfenster für das gewählte Datum werden angezeigt:
- Uhrzeiten als Schaltflächen
- Nur freie Zeitfenster sind anklickbar

### Schritt 5: Kundeninformationen

Der Kunde gibt seine Kontaktdaten ein:
- Vor- und Nachname
- Telefon (erforderlich)
- E-Mail (für Bestätigung)
- Kennzeichen des Fahrzeugs
- Marke und Modell (optional)
- Notizen/Kommentare

### Schritt 6: Bestätigung

Eine Zusammenfassung mit allen Informationen wird angezeigt. Der Kunde bestätigt seine Buchung.

---

## Personalisierung der Seite

### Personalisierte Elemente

Ihre Seite spiegelt Ihre Identität wider:

| Element | Quelle |
|---------|--------|
| **Logo** | Einstellungen > Erscheinungsbild |
| **Farben** | Personalisiertes Theme |
| **Werkstattname** | Einstellungen > Identität |
| **Adresse** | Filialeinstellungen |

### Angezeigte Informationen

- Name Ihrer Werkstatt
- Logo
- Verfügbare Services
- Kontaktdaten

---

## Ihre Seite teilen

### Teilungsmethoden

| Methode | Wie |
|---------|-----|
| **Direktlink** | Kopieren Sie `pitstoply.ch/ihr-slug` |
| **QR-Code** | Generieren Sie einen QR, der auf die URL zeigt |
| **Website-Button** | Integrieren Sie einen Link auf Ihrer Seite |
| **Soziale Medien** | Teilen Sie den Link auf Facebook, Instagram |
| **E-Mail** | Fügen Sie den Link zu Ihrer Signatur hinzu |
| **SMS** | Senden Sie den Link an Ihre Kunden |

### QR-Code generieren

1. Verwenden Sie einen kostenlosen QR-Code-Generator (z.B. qr-code-generator.com)
2. Geben Sie Ihre URL ein: `https://pitstoply.ch/ihr-slug`
3. Laden Sie den QR-Code herunter
4. Drucken Sie ihn für Ihr Schaufenster oder Ihre Visitenkarte

### Button für Ihre Website

Beispiel HTML-Code:

```html
<a href="https://pitstoply.ch/ihr-slug"
   style="background: #007bff; color: white; padding: 10px 20px; text-decoration: none; border-radius: 5px;">
   Termin buchen
</a>
```

---

## Buchungsoptionen

### Änderung durch den Kunden

Nach der Buchung erhält der Kunde eine E-Mail mit einem Link zum:
- Datum/Uhrzeit ändern
- Termin stornieren

### Automatische Erinnerungen

Je nach Ihrer Konfiguration erhält der Kunde:
- Bestätigungs-E-Mail (sofort)
- Bestätigungs-SMS (falls aktiviert)
- Erinnerung 24h vorher (falls aktiviert)

---

## Überprüfen, dass alles funktioniert

### Empfohlener Test

1. Öffnen Sie Ihre Seite in einem privaten Browser
2. Testen Sie eine vollständige Buchung mit Ihren Daten
3. Überprüfen Sie:
   - Die Zeitfenster entsprechen Ihren Öffnungszeiten
   - Das Design ist korrekt
   - Die Bestätigungs-E-Mail kommt an
4. Löschen Sie Ihren Testtermin nach der Überprüfung

### Kontrollpunkte

- [ ] Das Logo wird korrekt angezeigt
- [ ] Die Farben sind stimmig
- [ ] Die Services sind korrekt
- [ ] Die Zeitfenster entsprechen den Öffnungszeiten
- [ ] Die E-Mail-Bestätigung funktioniert
- [ ] Die SMS kommt an (falls aktiviert)

---

## Suchmaschinenoptimierung

### Natürliche Referenzierung

Ihre Seite profitiert von grundlegenden SEO-Elementen:
- Titel mit dem Namen Ihrer Werkstatt
- Beschreibung mit Ihrer Tätigkeit
- Strukturierte Tags

### Sichtbarkeit verbessern

- Fügen Sie den Link bei Google My Business hinzu
- Erwähnen Sie ihn in Ihren sozialen Medien
- Integrieren Sie ihn in Ihre E-Mail-Signatur

---

## Häufige Fragen

<details>
<summary><strong>Kann ich meine Buchungsseite vorübergehend deaktivieren?</strong></summary>

Derzeit gibt es keinen globalen Ein/Aus-Schalter. Sie können:
- Alle Zeitfenster über Schliessungen blockieren
- Die Öffnungszeiten auf null reduzieren

</details>

<details>
<summary><strong>Können Kunden mehrere aufeinanderfolgende Termine buchen?</strong></summary>

Jede Buchung ist unabhängig. Der Kunde muss den Prozess für jeden Termin wiederholen.

</details>

<details>
<summary><strong>Wie begrenzen ich die Anzahl der Buchungen pro Tag?</strong></summary>

Die Anzahl ist begrenzt durch Anzahl der Hebebühnen × verfügbare Zeitfenster. Um die Kapazität zu reduzieren, können Sie:
- Die Öffnungszeiten reduzieren
- Einige Hebebühnen deaktivieren
- Die Servicedauer erhöhen

</details>

<details>
<summary><strong>Ist die Seite für Mobilgeräte optimiert?</strong></summary>

Ja, die Seite ist responsive und passt sich automatisch an Smartphones und Tablets an.

</details>
