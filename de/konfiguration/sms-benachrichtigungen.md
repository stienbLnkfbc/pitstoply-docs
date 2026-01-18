# SMS-Benachrichtigungen

Senden Sie automatische SMS an Ihre Kunden, um Abwesenheiten zu reduzieren und das Erlebnis zu verbessern.

## Voraussetzungen

Um SMS-Benachrichtigungen zu nutzen:
1. **SMS-Guthaben** verfügbar haben ([Guthaben kaufen](../abrechnung/sms-guthaben.md))
2. SMS-Benachrichtigungen in den Einstellungen **aktivieren**
3. Ihre Kunden müssen eine **gültige Telefonnummer** haben

---

## SMS-Benachrichtigungen aktivieren

### Allgemeine Konfiguration

1. Gehen Sie zu **Einstellungen > Benachrichtigungen**
2. Aktivieren Sie im Abschnitt **SMS**:

| Option | Wann aktivieren |
|--------|-----------------|
| **Bestätigungs-SMS** | Um jede neue Buchung zu bestätigen |
| **Erinnerungs-SMS** | Um vor dem Termin zu erinnern |
| **Änderungs-SMS** | Wenn ein Termin geändert wird |
| **Stornierungs-SMS** | Wenn ein Termin storniert wird |

{% hint style="tip" %}
**Empfehlung**: Aktivieren Sie mindestens die **Erinnerungs-SMS** - sie ist am effektivsten zur Reduzierung von No-Shows.
{% endhint %}

### Erinnerungsfrist

Konfigurieren Sie, wann die Erinnerung gesendet wird:
- **24 Stunden vorher** (empfohlen)
- **48 Stunden vorher**
- **Am selben Tag**

---

## Erweiterte SMS-Parameter konfigurieren

### Auf detaillierte Einstellungen zugreifen

1. Gehen Sie zu **Einstellungen > SMS**
2. Konfigurieren Sie die verfügbaren Optionen

### Sender ID (Absender)

Die **Sender ID** ist der Name, der als SMS-Absender erscheint.

| Option | Anzeige | Verfügbarkeit |
|--------|---------|---------------|
| Standardnummer | +41 79 xxx xx xx | Immer |
| Personalisierter Name | "GarageMueller" | Je nach Anbieter |

{% hint style="warning" %}
**Hinweis**: Personalisierte Sender IDs (Namen) funktionieren nicht bei allen Anbietern und in allen Ländern. Die Standardnummer wird für maximale Kompatibilität empfohlen.
{% endhint %}

---

## Inhalt der SMS

### Bestätigungs-SMS

Wird sofort nach einer Buchung gesendet.

**Beispiel:**
```
Ihr Termin ist bestätigt!
📅 15.01.2026 um 10:00
📍 Garage Müller - Zürich
🚗 Räderwechsel

Ändern/Stornieren: [Link]
```

### Erinnerungs-SMS

Wird gemäss der konfigurierten Frist gesendet (z.B. 24h vorher).

**Beispiel:**
```
Erinnerung: Ihr Termin morgen!
📅 15.01.2026 um 10:00
📍 Garage Müller - Zürich
Bis bald!
```

### Änderungs-SMS

Wird gesendet, wenn der Termin geändert wird.

**Beispiel:**
```
Ihr Termin wurde geändert.
Neues Datum: 16.01.2026 um 14:00
📍 Garage Müller - Zürich
```

---

## SMS-Verfolgung

### Verlauf einsehen

1. Gehen Sie zu **Einstellungen > SMS > Verlauf**
2. Sie sehen alle gesendeten SMS mit:
   - Datum und Uhrzeit
   - Empfänger
   - Inhalt
   - Status

### Mögliche Status

| Status | Bedeutung |
|--------|-----------|
| ✅ Gesendet | SMS an Anbieter übermittelt |
| ⏳ Ausstehend | Wird gerade gesendet |
| ❌ Fehlgeschlagen | Fehler (ungültige Nummer usw.) |

---

## Guthaben und Aufladung

### Guthaben prüfen

Ihr SMS-Guthaben ist sichtbar:
- Dashboard (Benachrichtigungs-Widget)
- Einstellungen > SMS
- Beim Senden (Warnung bei niedrigem Guthaben)

### Aufladen

1. Gehen Sie zu **Einstellungen > SMS**
2. Klicken Sie auf **Guthaben kaufen**
3. Wählen Sie ein Paket
4. Führen Sie die Zahlung durch

[SMS-Pakettarife ansehen](../abrechnung/sms-guthaben.md)

---

## Sonderfälle

### Kunde ohne Telefonnummer

Wenn ein Kunde keine Nummer hat:
- Die SMS wird nicht gesendet
- Kein Guthaben wird abgezogen
- Stattdessen wird eine E-Mail gesendet (falls aktiviert)

### Ausländische Nummer

| Land | Support |
|------|---------|
| Schweiz (+41) | ✅ Optimal |
| Frankreich (+33) | ✅ Funktional |
| Deutschland (+49) | ✅ Funktional |
| Andere | ⚠️ Nicht garantiert |

### Lange SMS

Eine Standard-SMS = 160 Zeichen.
Wenn die Nachricht länger ist, zählt sie als mehrere SMS.

---

## SMS deaktivieren

### Vorübergehend

Deaktivieren Sie die Optionen in **Einstellungen > Benachrichtigungen**, ohne Ihr Guthaben zu löschen.

### Dauerhaft

Deaktivieren Sie alle SMS-Optionen. Ihr Guthaben bleibt verfügbar, falls Sie Ihre Meinung ändern.

---

## Häufige Fragen

<details>
<summary><strong>Werden SMS automatisch gesendet?</strong></summary>

Ja, gemäss Ihren Einstellungen:
- Bestätigung: automatisch bei der Buchung
- Erinnerung: automatisch gemäss konfigurierter Frist
- Änderung/Stornierung: automatisch bei der Aktion

</details>

<details>
<summary><strong>Kann ich den SMS-Text anpassen?</strong></summary>

Derzeit sind die Vorlagen vordefiniert, um Klarheit und Konformität zu gewährleisten. Eine erweiterte Anpassung ist für eine zukünftige Version geplant.

</details>

<details>
<summary><strong>Kann der Kunde auf die SMS antworten?</strong></summary>

Nein, SMS werden von einem automatisierten System gesendet. Um Ihre Werkstatt zu kontaktieren, muss der Kunde Ihre reguläre Telefonnummer verwenden.

</details>

<details>
<summary><strong>Was passiert, wenn mein Guthaben bei 0 ist?</strong></summary>

SMS werden nicht gesendet. E-Mails funktionieren weiterhin, falls aktiviert. Sie erhalten eine Warnung bei niedrigem Guthaben, bevor Sie 0 erreichen.

</details>

<details>
<summary><strong>Funktionieren SMS am Wochenende?</strong></summary>

Ja, SMS werden 24/7 gesendet, je nach auslösenden Ereignissen (Buchung, programmierte Erinnerung usw.).

</details>
