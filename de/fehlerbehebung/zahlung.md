# Zahlungsprobleme

Lösungen für häufige Probleme im Zusammenhang mit Abonnement und Zahlungen.

---

## Zahlung abgelehnt

### Meine Karte wurde abgelehnt

**Häufige Ursachen:**

| Ursache | Lösung |
|---------|--------|
| Unzureichende Mittel | Überprüfen Sie Ihren Kontostand |
| Karte abgelaufen | Aktualisieren Sie die Karte im Stripe-Portal |
| Zahlungslimit | Kontaktieren Sie Ihre Bank |
| Online-Zahlung gesperrt | Aktivieren Sie Online-Zahlungen bei Ihrer Bank |
| 3D Secure fehlgeschlagen | Versuchen Sie es erneut und validieren Sie die Authentifizierung |

### Wie erneut versuchen

1. Gehen Sie zu **Abrechnung > Abonnement verwalten**
2. Greifen Sie auf das Stripe-Portal zu
3. Aktualisieren Sie Ihr Zahlungsmittel
4. Versuchen Sie die Zahlung erneut

---

## Karte abgelaufen

### Mein Abonnement wurde gesperrt

**Was passiert:**
1. Stripe versucht, mit der registrierten Karte abzubuchen
2. Die Zahlung schlägt fehl (Karte abgelaufen)
3. Stripe versucht automatisch mehrmals
4. Nach mehreren Fehlschlägen wird das Abonnement gesperrt

### Lösung

1. Greifen Sie auf das **Stripe-Portal** zu (über Abrechnung)
2. Fügen Sie eine neue gültige Karte hinzu
3. Stripe versucht automatisch erneut
4. Oder klicken Sie auf **Jetzt bezahlen**, falls verfügbar

---

## Ich finde meine Rechnungen nicht

### Wo sind meine Rechnungen?

1. Gehen Sie zu **Abrechnung**
2. Klicken Sie auf **Abonnement verwalten**
3. Im Stripe-Portal, Bereich **Rechnungsverlauf**
4. Laden Sie Rechnungen als PDF herunter

### Rechnung für die Buchhaltung

Die Stripe-Rechnungen enthalten:
- Rechnungsnummer
- Leistungsdetails
- Nettobetrag und MwSt
- Ihre Daten und die von PitStoply

---

## Unerwartete Abbuchung

### Ich wurde abgebucht, obwohl ich dachte, ich hätte gekündigt

**Überprüfungen:**

1. **Kündigung wirksam?** Überprüfen Sie unter Abrechnung, dass das Abonnement wirklich gekündigt ist
2. **Datum der Wirksamkeit?** Die Kündigung wird am Ende des bezahlten Zeitraums wirksam
3. **SMS-Guthaben?** Eine Abbuchung kann für einen SMS-Guthaben-Kauf sein

### Einspruch

Wenn Sie glauben, dass eine Abbuchung ungerechtfertigt ist:
1. Kontaktieren Sie support@pitstoply.ch mit den Details
2. Erheben Sie nicht direkt einen Bankeinspruch (dies kann Ihr Konto sperren)

---

## Planwechsel nicht wirksam

### Ich habe den Plan gewechselt, aber nichts hat sich geändert

**Für ein Upgrade (höherer Plan):**
- Die Wirkung ist **sofort**
- Aktualisieren Sie die Seite
- Melden Sie sich ab und wieder an

**Für ein Downgrade (niedrigerer Plan):**
- Die Wirkung ist **verzögert** bis zum Ende des aktuellen Zeitraums
- Sie behalten die aktuellen Funktionen bis zum Ablauf

---

## Testphase beendet

### Ich habe nach der Testphase keinen Zugang mehr

**Was passiert:**
- Die Testphase ist beendet
- Keine Karte war registriert
- Der Zugang ist eingeschränkt

**Lösung:**
1. Melden Sie sich bei PitStoply an
2. Gehen Sie zu **Abrechnung**
3. Wählen Sie einen Plan
4. Geben Sie Ihre Zahlungsinformationen ein
5. Ihr Zugang wird wiederhergestellt

---

## Rückerstattung

### Kann ich eine Rückerstattung erhalten?

**Allgemeine Richtlinie:**
- Jahresabonnements sind in der Regel nicht erstattungsfähig
- SMS-Guthaben ist nicht erstattungsfähig

**Mögliche Ausnahmen:**
- Grosses technisches Problem auf unserer Seite
- Doppelte Abrechnung durch Fehler
- Ausnahmefälle werden einzeln geprüft

**Rückerstattung beantragen:**
1. Kontaktieren Sie support@pitstoply.ch
2. Erklären Sie Ihre Situation
3. Fügen Sie die betreffenden Rechnungen bei

---

## MwSt und Abrechnung

### Häufige Fragen

<details>
<summary><strong>Ist die MwSt in den Preisen enthalten?</strong></summary>

Ja, die angezeigten Preise enthalten die Schweizer MwSt (7.7%). Die Details erscheinen auf den Rechnungen.

</details>

<details>
<summary><strong>Kann ich eine Rechnung mit meiner MwSt-Nummer erhalten?</strong></summary>

Ihre Rechnungsinformationen können im Stripe-Portal aktualisiert werden. Fügen Sie Ihre UID/MwSt-Nummer in den Abrechnungseinstellungen hinzu.

</details>

<details>
<summary><strong>Kann ich per Banküberweisung zahlen?</strong></summary>

Kartenzahlung ist Standard. Für grosse Konten (Network-Plan) können Vereinbarungen besprochen werden. Kontaktieren Sie uns.

</details>

---

## Eingeschränkter Zugang

### Meldung "Abonnement abgelaufen"

**Ursachen:**
1. Nicht behobener Zahlungsfehler
2. Gekündigtes Abonnement und Zeitraum beendet
3. Testphase ohne Zahlung beendet

**Lösung:**
1. Melden Sie sich an
2. Gehen Sie zu **Abrechnung**
3. Regularisieren Sie Ihre Situation (Zahlung oder neuer Plan)

### Was Sie noch tun können

Im eingeschränkten Modus:
- ✅ Ihre Daten ansehen (nur lesen)
- ❌ Neue Termine erstellen
- ❌ Einstellungen ändern

---

## Zahlungssicherheit

### Sind meine Kartendaten sicher?

**Ja.** PitStoply verwendet **Stripe** für alle Zahlungen:

| Aspekt | Schutz |
|--------|--------|
| Kartenspeicherung | Stripe (nicht PitStoply) |
| Übertragung | Verschlüsselt (HTTPS/TLS) |
| Konformität | PCI-DSS Level 1 |
| Authentifizierung | 3D Secure unterstützt |

PitStoply sieht niemals Ihre vollständige Kartennummer.

---

## Support kontaktieren

Für Zahlungsprobleme:

- **E-Mail**: support@pitstoply.ch
- **Anzugebende Informationen**:
  - Name der Werkstatt
  - Konto-E-Mail
  - Datum des Problems
  - Betroffener Betrag (falls zutreffend)
  - Screenshot des Fehlers
