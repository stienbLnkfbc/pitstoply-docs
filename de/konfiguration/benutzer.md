# Benutzer und Zugriff

Verwalten Sie die Personen, die Zugang zu Ihrem PitStoply-Konto haben, und definieren Sie deren Berechtigungen.

## Benutzertypen

| Rolle | Beschreibung | Berechtigungen |
|-------|--------------|----------------|
| **Eigentümer (Owner)** | Ersteller des Kontos | Vollzugriff, Abrechnung |
| **Mitarbeiter (Employee)** | Teammitglied | Operativer Zugriff, keine Abrechnung |

---

## Auf die Benutzerverwaltung zugreifen

1. Gehen Sie zu **Einstellungen**
2. Klicken Sie auf **Benutzer**

---

## Benutzer hinzufügen

### Mitarbeiter einladen

1. Klicken Sie auf **Benutzer hinzufügen**
2. Füllen Sie die Informationen aus:

| Feld | Beschreibung |
|------|--------------|
| **Name** | Vollständiger Name des Mitarbeiters |
| **E-Mail** | E-Mail-Adresse (dient als Kennung) |
| **Rolle** | Employee |

3. Klicken Sie auf **Einladen**

### Einladungsprozess

1. Der Mitarbeiter erhält eine Einladungs-E-Mail
2. Er klickt auf den Link, um sein Passwort zu erstellen
3. Er kann sich dann bei PitStoply anmelden

{% hint style="info" %}
Die Einladung läuft nach 7 Tagen ab. Sie können sie bei Bedarf erneut senden.
{% endhint %}

---

## Berechtigungen nach Rolle

### Eigentümer (Owner)

Vollzugriff auf alle Funktionen:

| Funktion | Zugriff |
|----------|---------|
| Dashboard | ✅ |
| Kalender / Termine | ✅ |
| Kunden | ✅ |
| Einstellungen | ✅ |
| Abrechnung / Abonnement | ✅ |
| Benutzerverwaltung | ✅ |

### Mitarbeiter (Employee)

Operativer Zugriff ohne administrative Funktionen:

| Funktion | Zugriff |
|----------|---------|
| Dashboard | ✅ |
| Kalender / Termine | ✅ |
| Kunden | ✅ |
| Einstellungen | ⚠️ Eingeschränkt |
| Abrechnung / Abonnement | ❌ |
| Benutzerverwaltung | ❌ |

{% hint style="warning" %}
Ein Mitarbeiter kann keine Abrechnungsinformationen sehen oder ändern und keine anderen Benutzer hinzufügen.
{% endhint %}

---

## Limits je nach Plan

Die Anzahl der Benutzer hängt von Ihrem Abonnement ab:

| Plan | Max. Benutzer |
|------|---------------|
| Independent | 2 |
| Multi-Lift | 5 |
| Network | Unbegrenzt |

Um mehr Benutzer hinzuzufügen, [aktualisieren Sie Ihren Plan](../abrechnung/plaene.md).

---

## Bestehende Benutzer verwalten

### Benutzer bearbeiten

1. Klicken Sie in der Benutzerliste auf den Benutzer
2. Ändern Sie die Informationen (Name, E-Mail)
3. Speichern Sie

### Benutzer deaktivieren

Um einem Mitarbeiter den Zugang zu entziehen:

1. Öffnen Sie die Benutzerkarte
2. Klicken Sie auf **Deaktivieren** oder **Löschen**
3. Bestätigen Sie

{% hint style="info" %}
Ein deaktivierter Benutzer kann sich nicht mehr anmelden, aber sein Aktionsverlauf wird beibehalten.
{% endhint %}

### Einladung erneut senden

Wenn ein Mitarbeiter seine Einladung nicht erhalten oder verloren hat:

1. Finden Sie den Benutzer in der Liste
2. Klicken Sie auf **Einladung erneut senden**

---

## Benutzereinstellungen

Jeder Benutzer kann seine Einstellungen anpassen:

### Sprache

1. Klicken Sie auf Ihren Namen/Profil
2. Wählen Sie Ihre bevorzugte **Sprache**
3. Die Oberfläche wird in dieser Sprache angezeigt

### Passwort

1. Gehen Sie zu Ihrem **Profil**
2. Klicken Sie auf **Passwort ändern**
3. Geben Sie das alte und das neue Passwort ein

---

## Sicherheit

### Bewährte Praktiken

| Empfehlung | Warum |
|------------|-------|
| Eindeutige Passwörter | Vermeidet Kettenreaktionen bei Kompromittierung |
| Berufliche E-Mail | Bessere Rückverfolgbarkeit |
| Ehemalige Mitarbeiter deaktivieren | Datensicherheit |

### Was tun, wenn ein Mitarbeiter geht

1. **Deaktivieren** Sie sofort sein Konto
2. Überprüfen Sie, ob er keine aktiven Sitzungen hat
3. Ändern Sie gemeinsame Passwörter (falls zutreffend)

---

## Häufige Fragen

<details>
<summary><strong>Kann ich mehrere Eigentümer haben?</strong></summary>

Nein, es gibt nur einen Eigentümer pro Konto. Sie können Mitarbeitern erweiterten Zugang geben, aber sie haben keinen Zugriff auf die Abrechnung.

</details>

<details>
<summary><strong>Kann ein Mitarbeiter die Einnahmen/Statistiken sehen?</strong></summary>

Ja, das Dashboard mit KPIs ist für Mitarbeiter sichtbar. Nur die Abrechnung (Abonnement, Zahlungen) ist verborgen.

</details>

<details>
<summary><strong>Wie übertrage ich die Eigentümerschaft des Kontos?</strong></summary>

Die Übertragung der Eigentümerschaft erfordert die Kontaktaufnahme mit dem Support über unsere [Feedback-Seite](../feedback.md), wo Sie ein Formular ausfüllen können.

</details>

<details>
<summary><strong>Können Benutzer unterschiedliche Zugänge pro Filiale haben?</strong></summary>

Derzeit haben alle Benutzer Zugang zu allen Filialen. Eine feinere Berechtigungsverwaltung pro Filiale ist geplant.

</details>
