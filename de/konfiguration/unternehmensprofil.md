# Unternehmensprofil

Konfigurieren Sie die Informationen Ihrer Werkstatt, die auf Ihrer Buchungsseite und in den Mitteilungen erscheinen.

## Auf die Einstellungen zugreifen

1. Gehen Sie zu **Einstellungen**
2. Klicken Sie auf **Identität** oder **Profil**

---

## Grundlegende Informationen

### Identität der Werkstatt

| Feld | Beschreibung | Wo es erscheint |
|------|--------------|-----------------|
| **Werkstattname** | Handelsname | Buchungsseite, E-Mails, Berichte |
| **Slug** | URL-Kennung | `pitstoply.ch/ihr-slug` |
| **Slogan** | Werbeslogan (optional) | Buchungsseite |

### Kontaktdaten

| Feld | Beschreibung |
|------|--------------|
| **Adresse** | Vollständige Postadresse |
| **Telefon** | Hauptnummer |
| **E-Mail** | Öffentliche Kontakt-E-Mail |
| **Website** | URL Ihrer Website (optional) |

{% hint style="info" %}
Diese Informationen erscheinen auf Ihrer öffentlichen Buchungsseite und in den an Kunden gesendeten E-Mails.
{% endhint %}

---

## Slug ändern

Der Slug ist die eindeutige Kennung Ihrer Buchungsseite.

### Slug-Regeln

| Regel | Beispiel |
|-------|----------|
| Nur Kleinbuchstaben | ✅ `garage-mueller` ❌ `Garage-Mueller` |
| Bindestriche erlaubt | ✅ `garage-mueller-ag` |
| Keine Leerzeichen | ❌ `garage mueller` |
| Keine Sonderzeichen | ❌ `garage@mueller` |

### Slug ändern

1. Ändern Sie in **Identität** das Feld **Slug**
2. Überprüfen Sie die Verfügbarkeit
3. Speichern Sie

{% hint style="warning" %}
**Achtung**: Wenn Sie den Slug ändern, funktioniert die alte URL nicht mehr. Denken Sie daran, Ihre QR-Codes und geteilten Links zu aktualisieren.
{% endhint %}

---

## Rechtliche Informationen

### Optionale Daten

| Feld | Beschreibung |
|------|--------------|
| **UID-Nummer** | Unternehmens-Identifikationsnummer (CHE-xxx.xxx.xxx) |
| **MwSt** | MwSt-Nummer falls steuerpflichtig |

Diese Informationen können auf Rechnungen und offiziellen Dokumenten erscheinen.

---

## Werkstattsprache

### Standardsprache

Legen Sie die Hauptsprache Ihrer Werkstatt fest:

| Sprache | Code |
|---------|------|
| Französisch | `fr` |
| Deutsch | `de` |

Diese Sprache bestimmt:
- Die Standardsprache Ihrer Buchungsseite
- Die Sprache der E-Mails an neue Kunden
- Die Sprache der Berichte

### Sprachwechsel

1. In **Einstellungen > Allgemein**
2. Wählen Sie die **Sprache**
3. Speichern Sie

{% hint style="info" %}
Jeder Benutzer kann auch seine eigene Sprachpräferenz in seinem persönlichen Profil festlegen.
{% endhint %}

---

## Zeitzone

PitStoply verwendet standardmässig die Zeitzone **Europe/Zurich**, die für die Schweiz geeignet ist.

Die angezeigten Uhrzeiten (Zeitfenster, Termine) verwenden diese Zeitzone automatisch.

---

## Ihre Informationen überprüfen

### Öffentliche Vorschau

Um zu sehen, wie Ihre Informationen den Kunden angezeigt werden:

1. Öffnen Sie Ihre Buchungsseite: `pitstoply.ch/ihr-slug`
2. Überprüfen Sie, ob Name, Adresse und Kontakt korrekt sind

### E-Mail-Test

Senden Sie sich eine Test-E-Mail, um das Erscheinungsbild zu überprüfen:

1. Erstellen Sie einen Testtermin mit Ihrer eigenen E-Mail
2. Überprüfen Sie die erhaltene Bestätigungs-E-Mail
3. Löschen Sie den Testtermin

---

## Häufige Fragen

<details>
<summary><strong>Kann ich mehrere Namen für verschiedene Filialen haben?</strong></summary>

Der Werkstattname ist global. Jede Filiale kann ihren eigenen Namen unter **Einstellungen > Filialen** haben.

</details>

<details>
<summary><strong>Ist die Slug-Änderung sofort wirksam?</strong></summary>

Ja, die Änderung ist sofort wirksam. Der alte Slug funktioniert sofort nicht mehr.

</details>

<details>
<summary><strong>Kann ich ein Emoji im Namen verwenden?</strong></summary>

Technisch ja, aber es wird aus Kompatibilitätsgründen nicht empfohlen (E-Mails, PDF).

</details>
