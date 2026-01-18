# E-Mail-Benachrichtigungen

Konfigurieren Sie die automatischen E-Mails, die an Ihre Kunden gesendet werden, um sie über ihre Termine zu informieren.

## E-Mail-Typen

| E-Mail | Auslöser | Inhalt |
|--------|----------|--------|
| **Bestätigung** | Neue Buchung | Termindetails, Änderungslink |
| **Erinnerung 24h** | 24h vor dem Termin | Erinnerung mit Details |
| **Erinnerung am Tag** | 2h vor dem Termin | Last-Minute-Erinnerung |
| **Änderung** | Termin geändert | Neue Details |
| **Stornierung** | Termin storniert | Stornierungsbestätigung |

---

## Auf die Einstellungen zugreifen

1. Gehen Sie zu **Einstellungen**
2. Klicken Sie auf **Benachrichtigungen**
3. Abschnitt **E-Mail**

---

## E-Mails aktivieren/deaktivieren

### Pro E-Mail-Typ

Für jeden E-Mail-Typ können Sie:

1. **Aktivieren**: Die E-Mail wird automatisch gesendet
2. **Deaktivieren**: Die E-Mail wird nicht gesendet

{% hint style="tip" %}
**Empfehlung**: Halten Sie mindestens die **Bestätigung** und die **24h-Erinnerung** aktiviert, um No-Shows zu reduzieren.
{% endhint %}

### Empfohlene Konfiguration

| E-Mail | Empfehlung |
|--------|------------|
| Bestätigung | ✅ Immer aktiv |
| Erinnerung 24h | ✅ Immer aktiv |
| Erinnerung am Tag | ⚡ Optional (nützlich bei vielen No-Shows) |
| Änderung | ✅ Aktiv |
| Stornierung | ✅ Aktiv |

---

## Inhalt der E-Mails

### Bestätigungs-E-Mail

Wird sofort nach einer Buchung gesendet.

**Inhalt:**
- Termindetails (Datum, Uhrzeit, Service)
- Filialinformationen (Adresse)
- Betroffenes Fahrzeug
- **Änderungs-/Stornierungslink**
- Kontaktdaten

### Erinnerungs-E-Mail

Wird automatisch gemäss der konfigurierten Frist gesendet.

**Inhalt:**
- Erinnerung an die Termindetails
- Filialadresse
- Änderungslink bei Bedarf

### Änderungs-E-Mail

Wird gesendet, wenn ein Termin geändert wird (von Ihnen oder dem Kunden).

**Inhalt:**
- Altes Datum/Uhrzeit
- Neues Datum/Uhrzeit
- Aktualisierte Details

### Stornierungsmail

Wird gesendet, wenn ein Termin storniert wird.

**Inhalt:**
- Bestätigung der Stornierung
- Details des stornierten Termins
- Einladung, einen neuen Termin zu buchen

---

## Absender der E-Mails

### Standardadresse

E-Mails werden von `noreply@pitstoply.ch` mit dem Namen Ihrer Werkstatt gesendet.

**Beispiel:**
```
Von: Garage Müller AG <noreply@pitstoply.ch>
```

### Personalisierter Absender (Custom Mailer)

{% hint style="info" %}
**Erweiterte Funktion**: Sie können Ihren eigenen SMTP-Server konfigurieren, um E-Mails von Ihrer Domain zu senden (z.B. `termin@garage-mueller.ch`).

[Siehe Custom Mailer Konfiguration](#) (demnächst verfügbar)
{% endhint %}

---

## Sprache der E-Mails

E-Mails werden standardmässig in der Sprache der Werkstatt gesendet.

Wenn der Kunde eine andere Sprachpräferenz hat (über sein Portal), wird die E-Mail in seiner Sprache gesendet.

---

## E-Mails überprüfen

### Versand testen

1. Erstellen Sie einen Testtermin mit Ihrer eigenen E-Mail
2. Überprüfen Sie, ob Sie die Bestätigung erhalten
3. Überprüfen Sie Inhalt und Formatierung
4. Löschen Sie den Testtermin

### Empfangsprobleme

Wenn E-Mails nicht ankommen:

1. Überprüfen Sie den Spam/Junk-Ordner
2. Überprüfen Sie, ob die E-Mail-Adresse des Kunden korrekt ist
3. [Siehe Fehlerbehebung](#)

---

## Häufige Fragen

<details>
<summary><strong>Kann ich den Text der E-Mails anpassen?</strong></summary>

Derzeit sind die Vorlagen standardisiert. Eine Inhaltsanpassung ist für eine zukünftige Version geplant.

</details>

<details>
<summary><strong>Werden E-Mails in HTML oder Text gesendet?</strong></summary>

E-Mails werden in HTML mit einer Text-Fallback-Version für E-Mail-Clients gesendet, die HTML nicht unterstützen.

</details>

<details>
<summary><strong>Kann ich den Verlauf der gesendeten E-Mails sehen?</strong></summary>

Der detaillierte E-Mail-Verlauf ist derzeit nicht verfügbar. Sie können die gesendeten SMS unter **Einstellungen > SMS > Verlauf** sehen.

</details>

<details>
<summary><strong>Was tun, wenn ein Kunde sagt, er erhält keine E-Mails?</strong></summary>

1. Überprüfen Sie die E-Mail-Adresse in seiner Kundenkarte
2. Bitten Sie ihn, seinen Spam zu überprüfen
3. Versuchen Sie, manuell erneut zu senden, falls möglich
4. Als letzten Ausweg aktivieren Sie SMS für diesen Kunden

</details>

<details>
<summary><strong>Kann ich eine E-Mail manuell senden?</strong></summary>

Derzeit sind E-Mails automatisch. Für manuelle Kontakte verwenden Sie Ihren eigenen E-Mail-Dienst.

</details>
