# Mein Abonnement verwalten

Sehen und verwalten Sie Ihr PitStoply-Abonnement: Planwechsel, Aktualisierung der Zahlungsinformationen, Rechnungen.

## Auf die Abrechnung zugreifen

1. Gehen Sie zu **Einstellungen** oder **Abrechnung**
2. Klicken Sie auf **Abonnement** oder **Billing**

{% hint style="info" %}
Nur der **Eigentümer** des Kontos hat Zugang zum Abrechnungsbereich.
{% endhint %}

---

## Abonnement-Informationen

### Was Sie sehen

| Information | Beschreibung |
|-------------|--------------|
| **Aktueller Plan** | Independent, Multi-Lift oder Network |
| **Status** | Aktiv, Testphase, Abgelaufen |
| **Nächste Abrechnung** | Datum der nächsten Abbuchung |
| **Zahlungsmittel** | Registrierte Karte |

---

## Stripe-Kundenportal

PitStoply verwendet **Stripe** für die Zahlungsverwaltung. Sie können auf das Stripe-Portal zugreifen, um:

- Ihre Rechnungen anzusehen
- Ihre Karte zu aktualisieren
- Belege herunterzuladen

### Auf das Portal zugreifen

1. Klicken Sie unter **Abrechnung** auf **Abonnement verwalten**
2. Sie werden zum Stripe-Portal weitergeleitet
3. Nehmen Sie Ihre Änderungen vor
4. Kehren Sie zu PitStoply zurück

---

## Plan wechseln

### Upgrade (auf einen höheren Plan wechseln)

1. Wählen Sie unter **Abrechnung > Pläne** den neuen Plan
2. Bestätigen Sie den Wechsel
3. **Sofortige Wirkung**: Sie haben sofort Zugang zu den neuen Funktionen
4. Der Preisunterschied wird anteilig berechnet

**Beispiel:**
- Sie wechseln von Independent (290 CHF) zu Multi-Lift (490 CHF)
- Mitten im Jahr zahlen Sie die anteilige Differenz
- Bei der nächsten Fälligkeit gilt der neue Preis

### Downgrade (auf einen niedrigeren Plan wechseln)

1. Wählen Sie den niedrigeren Plan
2. Bestätigen Sie den Wechsel
3. **Verzögerte Wirkung**: Der Wechsel gilt ab Ende des aktuellen Zeitraums

{% hint style="warning" %}
**Vor einem Downgrade** überprüfen Sie, ob Sie die Limits des neuen Plans einhalten (Anzahl Filialen, Hebebühnen, Benutzer). Sie müssen möglicherweise überzählige Elemente löschen.
{% endhint %}

---

## Zahlungsmittel aktualisieren

### Karte ändern

1. Greifen Sie auf das **Stripe-Portal** zu (über Abonnement verwalten)
2. Bereich **Zahlungsmittel**
3. Fügen Sie eine neue Karte hinzu
4. Löschen Sie die alte, wenn gewünscht

### Akzeptierte Karten

| Typ | Akzeptiert |
|-----|------------|
| Visa | ✅ |
| Mastercard | ✅ |
| American Express | ✅ |
| TWINT | ⚠️ Je nach Verfügbarkeit |

---

## Rechnungen

### Rechnungen einsehen

1. Greifen Sie auf das **Stripe-Portal** zu
2. Bereich **Rechnungsverlauf**
3. Laden Sie Rechnungen als PDF herunter

### Inhalt einer Rechnung

- Abrechnungszeitraum
- Plandetails
- Nettobetrag und MwSt
- Gezahlter Gesamtbetrag

---

## Abonnement kündigen

### Kündigungsverfahren

1. Klicken Sie unter **Abrechnung** auf **Abonnement kündigen**
2. Bestätigen Sie Ihre Wahl
3. Das Abonnement bleibt bis zum Ende des bezahlten Zeitraums aktiv
4. Nach Ablauf ist der Zugang eingeschränkt

### Was nach der Kündigung passiert

| Zeitraum | Zugang |
|----------|--------|
| Bis zum Ablauf | Vollzugang |
| Nach Ablauf | Nur-Lese-Zugang |
| 30 Tage danach | Daten archiviert |

{% hint style="warning" %}
**Achtung**: Nach 90 Tagen Inaktivität können Daten gelöscht werden. Exportieren Sie Ihre Daten vor der Kündigung, falls erforderlich.
{% endhint %}

### Abonnement reaktivieren

Wenn Sie Ihre Meinung ändern:

1. Melden Sie sich wieder bei PitStoply an
2. Gehen Sie zu **Abrechnung**
3. Wählen Sie einen Plan und führen Sie die Zahlung durch
4. Ihr Konto wird mit Ihren Daten reaktiviert

---

## Testphase

### Während der Testphase

- Vollzugang zu den Funktionen des gewählten Plans
- Keine Abbuchung
- Erinnerung vor Ende der Testphase

### Ende der Testphase

Am Ende der Testphase:
- Wenn eine Karte registriert ist: automatische Abbuchung
- Wenn keine Karte: eingeschränkter Zugang bis zur Zahlung

---

## Häufige Fragen

<details>
<summary><strong>Kann ich eine Rückerstattung erhalten?</strong></summary>

Jahresabonnements sind in der Regel nicht erstattungsfähig. Besuchen Sie unsere [Feedback-Seite](../feedback.md), um uns bei Ausnahmefällen über ein Formular zu kontaktieren.

</details>

<details>
<summary><strong>Was passiert, wenn die Zahlung fehlschlägt?</strong></summary>

Stripe versucht automatisch mehrmals. Sie erhalten Benachrichtigungen zur Aktualisierung Ihrer Karte. Nach mehreren Fehlversuchen wird der Zugang gesperrt.

</details>

<details>
<summary><strong>Kann ich per Rechnung/Überweisung zahlen?</strong></summary>

Kartenzahlung ist Standard. Für grosse Konten (Network) können Vereinbarungen mit dem Support besprochen werden.

</details>

<details>
<summary><strong>Ist die MwSt enthalten?</strong></summary>

Die angezeigten Preise enthalten die Schweizer MwSt (falls anwendbar). Die Rechnungen zeigen den Nettobetrag und die MwSt separat.

</details>

<details>
<summary><strong>Kann ich die Zahlungsfrequenz ändern?</strong></summary>

Derzeit sind Abonnements jährlich. Monatliche Optionen könnten in Zukunft verfügbar sein.

</details>
