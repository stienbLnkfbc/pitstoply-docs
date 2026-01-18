# Kundenportal (QR-Code)

Jeder Kunde hat einen einzigartigen QR-Code, der ihm Zugang zu seinem persönlichen Portal gibt, um seine Termine und Fahrzeuge zu verwalten.

## Was ist das Kundenportal?

Das Kundenportal ist eine Webseite, die über QR-Code zugänglich ist, wo Ihre Kunden:

| Funktion | Beschreibung |
|----------|--------------|
| **Fahrzeuge ansehen** | Liste der registrierten Fahrzeuge |
| **Termin buchen** | Ohne erneute Eingabe ihrer Daten |
| **Verlauf einsehen** | Vergangene und zukünftige Termine |
| **Daten aktualisieren** | Telefon, E-Mail ändern |

---

## Wie es funktioniert

### Für den Kunden

1. Der Kunde scannt seinen QR-Code (Smartphone)
2. Er gelangt direkt zu seinem Portal: `pitstoply.ch/c/ABC123XYZ`
3. Seine Fahrzeuge sind bereits aufgelistet
4. Er kann in wenigen Klicks buchen

### Vorteile

| Für Sie | Für den Kunden |
|---------|----------------|
| Weniger manuelle Eingabe | Schnelle Buchung |
| Aktuelle Kundendaten | Zugänglicher Verlauf |
| Kundenbindung | Personalisiertes Erlebnis |

---

## QR-Code generieren und teilen

### Von der Kundenkarte aus

1. Gehen Sie zu **Kunden**
2. Öffnen Sie die Kundenkarte
3. Klicken Sie auf **QR-Code**

### Verfügbare Optionen

| Aktion | Beschreibung |
|--------|--------------|
| **Anzeigen** | QR auf dem Bildschirm ansehen |
| **Herunterladen** | PNG-Datei erhalten |
| **Per E-Mail senden** | Der Kunde erhält seinen QR per E-Mail |

---

## Anwendungsfälle

### Physische Kundenkarte

Drucken Sie eine Visitenkarte mit dem QR-Code des Kunden:

1. Laden Sie den QR-Code herunter (PNG)
2. Integrieren Sie ihn in ein Kartendesign
3. Drucken und übergeben Sie sie dem Kunden

### Willkommens-E-Mail

Senden Sie den QR-Code automatisch an neue Kunden:

1. Legen Sie den Kunden in PitStoply an
2. Klicken Sie auf **QR per E-Mail senden**
3. Der Kunde erhält seinen Zugangscode

### Anzeige an der Kasse

Zeigen Sie einen generischen QR-Code (Ihre Buchungsseite) für neue Kunden und den persönlichen QR für bestehende Kunden.

---

## Sicherheit des QR-Codes

### Ist der Code sicher?

Ja. Jeder QR-Code enthält einen **einzigartigen Zufallscode** (z.B. `ABC123XYZ`), der:

- Nicht erratbar ist
- Keine persönlichen Daten in der URL preisgibt
- Bei Bedarf neu generiert werden kann

### QR-Code neu generieren

Wenn ein Kunde seinen QR verliert oder Sie einen unbefugten Zugriff vermuten:

1. Öffnen Sie die Kundenkarte
2. Klicken Sie auf **QR-Code > Neu generieren**
3. Der alte Code wird ungültig
4. Senden Sie dem Kunden den neuen

---

## Was der Kunde sieht

### Portal-Startseite

Der Kunde sieht:

- **Seine Daten**: Name, Telefon, E-Mail
- **Seine Fahrzeuge**: Liste mit Kennzeichen
- **Button "Termin buchen"**: Schnelle Buchung
- **Verlauf**: Vergangene und zukünftige Termine

### Buchung über das Portal

1. Der Kunde klickt auf **Termin buchen**
2. Er wählt ein Fahrzeug (oder fügt eines hinzu)
3. Er wählt Service, Datum und Zeitfenster
4. Er bestätigt - keine erneute Eingabe seiner Kontaktdaten!

---

## Fahrzeug über das Portal hinzufügen

Der Kunde kann selbst ein Fahrzeug hinzufügen:

1. In seinem Portal, Bereich **Fahrzeuge**
2. Klick auf **Fahrzeug hinzufügen**
3. Gibt Kennzeichen, Marke, Modell ein
4. Das Fahrzeug erscheint in Ihrer Datenbank

{% hint style="info" %}
Vom Kunden hinzugefügte Fahrzeuge sind sofort in Ihrer PitStoply-Oberfläche sichtbar.
{% endhint %}

---

## Häufige Fragen

<details>
<summary><strong>Kann der Kunde seine Daten ändern?</strong></summary>

Ja, der Kunde kann Telefon und E-Mail über sein Portal aktualisieren. Sie sehen die Änderungen in seiner Karte.

</details>

<details>
<summary><strong>Was passiert, wenn der Kunde seinen QR-Code verliert?</strong></summary>

Sie können ihm den Code per E-Mail erneut senden oder bei Bedarf einen neuen generieren.

</details>

<details>
<summary><strong>Ist das Portal ohne QR-Code zugänglich?</strong></summary>

Nein, der Zugang erfolgt nur über den QR-Code. Das gewährleistet, dass nur der Kunde auf seine Daten zugreifen kann.

</details>

<details>
<summary><strong>Kann ich das Portal für einen Kunden deaktivieren?</strong></summary>

Sie können seinen QR-Code neu generieren, was den alten ungültig macht. Es gibt keine Option zur vollständigen Deaktivierung.

</details>
