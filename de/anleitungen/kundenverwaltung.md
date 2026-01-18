# Kunden verwalten

PitStoply ermöglicht Ihnen, alle Kundeninformationen und deren Fahrzeuge zentral zu verwalten.

## Zur Kundenliste gelangen

1. Klicken Sie im Hauptmenü auf **Kunden**
2. Sie sehen die Liste aller Kunden mit:
   - Vor- und Nachname
   - Unternehmen (falls angegeben)
   - Telefon
   - Anzahl der Fahrzeuge
   - Letzter Termin

### Kunden suchen

Verwenden Sie die **Suchleiste**, um schnell einen Kunden zu finden nach:
- Vor- oder Nachname
- Telefonnummer
- Unternehmensname
- Kennzeichen eines Fahrzeugs

{% hint style="tip" %}
**Globale Suche**: Drücken Sie `Ctrl+K` (oder `Cmd+K` auf Mac), um die globale Suche von jeder Seite aus zu öffnen.
{% endhint %}

---

## Neuen Kunden anlegen

### Von der Kundenliste aus

1. Klicken Sie auf **Neuer Kunde**
2. Füllen Sie die Informationen aus:

| Feld | Erforderlich | Beschreibung |
|------|--------------|--------------|
| Vorname | ✅ | Vorname des Kunden |
| Nachname | ✅ | Familienname |
| Telefon | ✅ | Für SMS und Kontakt |
| E-Mail | ❌ | Für E-Mail-Benachrichtigungen |
| Unternehmen | ❌ | Falls Geschäftskunde |
| Notizen | ❌ | Interne Informationen |

3. Klicken Sie auf **Speichern**

### Bei einer Buchung

Falls der Kunde nicht existiert, können Sie ihn direkt bei der Terminerstellung anlegen.

---

## Fahrzeug hinzufügen

Jeder Kunde kann mehrere Fahrzeuge haben.

### Von der Kundenkarte aus

1. Öffnen Sie die Kundenkarte
2. Klicken Sie im Bereich **Fahrzeuge** auf **Fahrzeug hinzufügen**
3. Füllen Sie die Informationen aus:

| Feld | Erforderlich | Beschreibung |
|------|--------------|--------------|
| Kennzeichen | ✅ | Schweizer Format (z.B. ZH 123456) |
| Marke | ❌ | Z.B. BMW, Audi, VW |
| Modell | ❌ | Z.B. Golf, A3, 3er-Serie |
| Typ | ❌ | PKW, SUV, Lieferwagen |
| Reifen eingelagert | ❌ | Checkbox, falls Reifen gelagert werden |

4. Klicken Sie auf **Speichern**

{% hint style="info" %}
**Reifen eingelagert**: Aktivieren Sie diese Option, wenn Sie die Reifen des Kunden zwischen den Saisons lagern. Diese Information erscheint auf den Terminblättern.
{% endhint %}

---

## Kunden-QR-Code

Jeder Kunde hat einen **einzigartigen QR-Code**, der ihm Zugang zu seinem persönlichen Portal gibt.

### Wozu dient der QR-Code?

| Funktion | Beschreibung |
|----------|--------------|
| **Kundenportal** | Der Kunde kann seine Terminhistorie einsehen |
| **Schnelle Buchung** | Er kann buchen, ohne seine Daten erneut einzugeben |
| **Registrierte Fahrzeuge** | Seine Fahrzeuge sind bereits verfügbar |

### Wie wird er verwendet?

1. **Kundenkarte**: Drucken Sie eine Karte mit dem QR-Code
2. **E-Mail**: Der QR-Code kann per E-Mail gesendet werden
3. **Anzeige**: Der Kunde scannt an Ihrem Empfang

### QR-Code generieren/anzeigen

1. Öffnen Sie die Kundenkarte
2. Klicken Sie auf **QR-Code**
3. Optionen:
   - **Anzeigen**: Auf dem Bildschirm ansehen
   - **Herunterladen**: PNG-Format zum Drucken
   - **Senden**: Per E-Mail an den Kunden

---

## Kunden importieren (CSV)

Wenn Sie eine bestehende Kundendatenbank haben, können Sie diese massenhaft importieren.

### CSV-Dateiformat

Ihre Datei muss folgende Spalten enthalten:

```
vorname,nachname,telefon,email,unternehmen
Hans,Müller,+41791234567,hans@email.com,
Maria,Schmidt,+41791234568,maria@email.com,Garage Schmidt AG
```

### Importvorgang

1. Gehen Sie zu **Kunden > Importieren**
2. Laden Sie die CSV-Vorlage herunter (optional)
3. Wählen Sie Ihre Datei
4. Überprüfen Sie die Datenvorschau
5. Klicken Sie auf **Importieren**

{% hint style="warning" %}
**Achtung bei Duplikaten**: Kunden mit derselben Telefonnummer werden ignoriert, um Duplikate zu vermeiden.
{% endhint %}

---

## Detaillierte Kundenkarte

Klicken Sie auf einen Kunden, um seine vollständige Karte zu sehen:

### Angezeigte Informationen

- **Kontaktdaten**: Telefon, E-Mail, Adresse
- **Fahrzeuge**: Liste mit Kennzeichen und Reifenstatus
- **Terminhistorie**: Alle vergangenen und zukünftigen Termine
- **Notizen**: Ihre internen Notizen zum Kunden

### Verfügbare Aktionen

| Aktion | Beschreibung |
|--------|--------------|
| **Bearbeiten** | Informationen ändern |
| **Termin erstellen** | Neuer Termin für diesen Kunden |
| **QR-Code** | QR-Code anzeigen/senden |
| **Löschen** | Kunden löschen (nach Bestätigung) |

---

## Kunden bearbeiten

1. Öffnen Sie die Kundenkarte
2. Klicken Sie auf **Bearbeiten**
3. Nehmen Sie Ihre Änderungen vor
4. Klicken Sie auf **Speichern**

{% hint style="info" %}
Die Bearbeitung eines Kunden hat keinen Einfluss auf vergangene Termine.
{% endhint %}

---

## Kunden löschen

{% hint style="danger" %}
**Achtung**: Das Löschen eines Kunden löscht auch alle seine Fahrzeuge. Vergangene Termine bleiben erhalten, aber die Verbindung zum Kunden geht verloren.
{% endhint %}

1. Öffnen Sie die Kundenkarte
2. Klicken Sie auf **Löschen**
3. Bestätigen Sie die Löschung

---

## Häufige Fragen

<details>
<summary><strong>Wie füge ich zwei doppelte Kundenkarten zusammen?</strong></summary>

Derzeit ist die Zusammenführung nicht automatisch. Sie müssen:
1. Die Fahrzeuge des Duplikats notieren
2. Sie zum Hauptkunden hinzufügen
3. Das Duplikat löschen

</details>

<details>
<summary><strong>Kann ich meine Kundenliste exportieren?</strong></summary>

Der CSV-Export ist in einer zukünftigen Version geplant. In der Zwischenzeit können Sie die PDF-Berichte verwenden.

</details>

<details>
<summary><strong>Können Kunden ihre Informationen selbst ändern?</strong></summary>

Ja, über ihr QR-Code-Portal können sie ihre Kontaktdaten und Fahrzeuge aktualisieren.

</details>
