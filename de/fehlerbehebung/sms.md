# SMS-Probleme

Lösungen für häufige Probleme im Zusammenhang mit SMS-Benachrichtigungen.

---

## SMS nicht gesendet

### Der Kunde hat die SMS nicht erhalten

**Zu überprüfende Punkte:**

| Überprüfung | Wie |
|-------------|-----|
| SMS aktiviert? | **Einstellungen > Benachrichtigungen** - SMS aktiviert ✅ |
| Ausreichend Guthaben? | **Einstellungen > SMS** - Guthaben überprüfen |
| Gültige Nummer? | Kundenkarte - Nummer im internationalen Format |
| Benachrichtigungstyp aktiviert? | Bestätigung/Erinnerung in Einstellungen aktiviert |

---

## Guthaben bei null

### SMS werden nicht mehr gesendet

**Ursache:** Sie haben keine SMS-Guthaben mehr.

**Lösung:**

1. Gehen Sie zu **Einstellungen > SMS**
2. Klicken Sie auf **Guthaben kaufen**
3. Wählen Sie ein Paket
4. Führen Sie die Zahlung durch

Ausstehende SMS werden nach dem Aufladen gesendet (innerhalb der Gültigkeitsfrist).

[SMS-Tarife ansehen](../abrechnung/sms-guthaben.md)

---

## Ungültige Telefonnummer

### Meldung "Ungültige Nummer" im Verlauf

**Mögliche Ursachen:**

1. **Falsches Format**: Die Nummer muss im internationalen Format sein
2. **Unvollständige Nummer**: Es fehlen Ziffern
3. **Festnetznummer**: Einige Festnetznummern empfangen keine SMS

### Korrektes Format für die Schweiz

| Format | Beispiel | Gültig |
|--------|----------|--------|
| International | +41791234567 | ✅ |
| Mit Leerzeichen | +41 79 123 45 67 | ✅ |
| Ohne Vorwahl | 0791234567 | ⚠️ Funktioniert möglicherweise nicht |
| Festnetz | +41211234567 | ❌ SMS nicht unterstützt |

### Nummer korrigieren

1. Öffnen Sie die Kundenkarte
2. Ändern Sie die Telefonnummer
3. Verwenden Sie das Format `+41XXXXXXXXX`
4. Speichern Sie

---

## SMS verspätet

### Die SMS kommt nach der geplanten Zeit an

**Mögliche Ursachen:**

1. **Anbieterverzögerung**: Einige Minuten Verzögerung sind normal
2. **Überlastetes Netz**: Zeiten hoher Auslastung
3. **Anbieterproblem**: Vorfall beim Mobilfunkanbieter

**Was Sie tun können:**

- Warten Sie einige Minuten
- Erinnerungen werden mit einer Marge gesendet (z.B. "24h vorher" = zwischen 24h und 23h vorher)

---

## SMS doppelt erhalten

### Der Kunde hat dieselbe SMS zweimal erhalten

**Mögliche Ursachen:**

1. **Vorübergehendes technisches Problem**: Selten, kontaktieren Sie den Support
2. **Zwei Aktionen ausgelöst**: Überprüfen Sie den SMS-Verlauf

### Verlauf überprüfen

1. Gehen Sie zu **Einstellungen > SMS > Verlauf**
2. Suchen Sie nach Kunde oder Nummer
3. Überprüfen Sie, ob tatsächlich zwei SMS gesendet wurden

---

## SMS abgeschnitten oder unleserlich

### Der SMS-Text ist abgeschnitten

**Ursache:** SMS sind auf 160 Zeichen begrenzt. Lange Nachrichten werden aufgeteilt.

**Was passiert:**
- Kurze Nachrichten: 1 SMS
- Lange Nachrichten: 2-3 SMS (separat gezählt)

Moderne Smartphones kombinieren lange SMS normalerweise automatisch.

---

## Falsche Sonderzeichen

### Umlaute oder Zeichen werden falsch angezeigt

**Ursache:** Einige Sonderzeichen können je nach Anbieter oder Telefon Probleme verursachen.

**Problematische Zeichen:**
- Emojis: ⚠️ Werden möglicherweise nicht angezeigt
- Sonderzeichen: €, £ usw.

**Lösung:** Die Standard-SMS-Vorlagen vermeiden diese Probleme. Wenn Sie anpassen, halten Sie es einfach.

---

## Sender ID nicht erkannt

### Die SMS kommt von einer unbekannten Nummer

**Erklärung:**

PitStoply-SMS kommen entweder:
- Von einer **Nummer** (+41...): Normal, Standardverhalten
- Von einem **Namen** (z.B. "GarageMueller"): Wenn Sender ID konfiguriert

### Sender ID konfigurieren

{% hint style="info" %}
Die Sender ID (Absendername) funktioniert nicht bei allen Anbietern und in allen Ländern. Die Standardnummer ist zuverlässiger.
{% endhint %}

---

## Der Kunde sagt, er hat nichts erhalten

### Aber der Verlauf zeigt "Gesendet"

**Überprüfungen beim Kunden:**

1. Richtige Telefonnummer überprüfen
2. Blockierte/gefilterte SMS überprüfen
3. Überprüfen, dass das Telefon nicht ausgeschaltet war
4. Netzabdeckung zum Zeitpunkt des Versands überprüfen

**Überprüfungen bei PitStoply:**

1. Überprüfen Sie den SMS-Verlauf für diesen Kunden
2. Überprüfen Sie den Status (Gesendet, Fehlgeschlagen)
3. Überprüfen Sie die registrierte Nummer

---

## Status im Verlauf

| Status | Bedeutung |
|--------|-----------|
| ✅ **Gesendet** | SMS an Anbieter übermittelt |
| ⏳ **Ausstehend** | Wird gerade gesendet |
| ❌ **Fehlgeschlagen** | Fehler beim Senden |

{% hint style="warning" %}
"Gesendet" bedeutet an den Anbieter übermittelt, nicht unbedingt vom Kunden empfangen. Die endgültige Zustellung hängt vom Mobilfunkanbieter ab.
{% endhint %}

---

## SMS für einen Kunden deaktivieren

Wenn ein Kunde keine SMS mehr erhalten möchte:

1. Öffnen Sie seine Kundenkarte
2. Löschen Sie seine Telefonnummer
3. Oder deaktivieren Sie SMS in seinen Präferenzen (falls Option verfügbar)

E-Mails werden weiterhin gesendet, wenn eine E-Mail-Adresse hinterlegt ist.

---

## Support kontaktieren

Für anhaltende Probleme:

- **E-Mail**: support@pitstoply.ch
- Fügen Sie bei:
  - Betroffene Telefonnummer (verwendetes Format)
  - Datum und Uhrzeit des geplanten Versands
  - Screenshot des SMS-Verlaufs
