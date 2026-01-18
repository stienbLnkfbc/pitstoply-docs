# Servicetypen

Konfigurieren Sie die Dienstleistungen, die Sie Ihren Kunden bei der Buchung anbieten.

## Verfügbare Services

PitStoply bietet vordefinierte Servicetypen für Werkstätten:

| Service | Beschreibung | Standard-Dauer |
|---------|--------------|----------------|
| **Räderwechsel** | Austausch kompletter Räder (Felgen + montierte Reifen) | 30 Min |
| **Reifenwechsel** | Demontage und Montage der Reifen auf Felgen | 45-60 Min |

---

## Auf die Konfiguration zugreifen

1. Gehen Sie zu **Einstellungen**
2. Klicken Sie auf **Services** oder **Servicetypen**

---

## Service aktivieren/deaktivieren

### Service aktivieren

1. Finden Sie in der Serviceliste den gewünschten Service
2. Aktivieren Sie den Toggle **Aktiv**
3. Der Service wird für Buchungen verfügbar

### Service deaktivieren

1. Deaktivieren Sie den Toggle **Aktiv**
2. Der Service erscheint nicht mehr bei Buchungen

{% hint style="info" %}
Das Deaktivieren eines Services betrifft keine bestehenden Termine dieses Typs.
{% endhint %}

---

## Service anpassen

### Dauer ändern

Die Dauer bestimmt die Grösse des blockierten Zeitfensters im Kalender.

1. Klicken Sie auf den zu ändernden Service
2. Passen Sie die **Dauer** an (in Minuten)
3. Speichern Sie

**Empfohlene Dauern:**

| Service | Kurze Dauer | Standard-Dauer | Lange Dauer |
|---------|-------------|----------------|-------------|
| Räderwechsel | 20 Min | 30 Min | 45 Min |
| Reifenwechsel | 45 Min | 60 Min | 90 Min |

{% hint style="tip" %}
**Tipp**: Planen Sie einen Puffer für Unvorhergesehenes ein. Besser ein etwas längeres Zeitfenster als Verspätungen in Serie.
{% endhint %}

### Richtpreis ändern

Der angezeigte Preis ist indikativ und informativ für den Kunden.

1. Klicken Sie auf den Service
2. Ändern Sie den **Preis** (in CHF)
3. Speichern Sie

{% hint style="warning" %}
Der angezeigte Preis ist nicht vertraglich bindend. Es ist eine Orientierung für den Kunden. Die tatsächliche Abrechnung erfolgt nach Ihren eigenen Prozessen.
{% endhint %}

---

## Auswirkung auf Zeitfenster

### Berechnung der Verfügbarkeit

Die Servicedauer beeinflusst direkt die angebotenen Zeitfenster:

**Beispiel mit Schliessung um 18 Uhr:**

| Servicedauer | Letztes mögliches Zeitfenster |
|--------------|-------------------------------|
| 30 Min | 17:30 |
| 45 Min | 17:15 |
| 60 Min | 17:00 |

### Services mit unterschiedlichen Dauern

Wenn Sie mehrere Services mit unterschiedlichen Dauern anbieten, passen sich die Zeitfenster automatisch an den vom Kunden gewählten Service an.

---

## Bewährte Praktiken

### Realistische Dauern

| Zu vermeiden | Empfohlen |
|--------------|-----------|
| Zu kurze Dauer (Stress, Verspätungen) | Dauer mit Puffer |
| Zu lange Dauer (Kapazitätsverlust) | Dauer basierend auf Ihrer realen Erfahrung |

### Kohärente Preise

- Zeigen Sie Preise an, die mit Ihrer tatsächlichen Preisgestaltung übereinstimmen
- Erwähnen Sie, wenn der Preis je nach Fahrzeug variiert

---

## Häufige Fragen

<details>
<summary><strong>Kann ich meine eigenen Servicetypen erstellen?</strong></summary>

Derzeit sind die Servicetypen vordefiniert. Das Hinzufügen von benutzerdefinierten Services ist für eine zukünftige Version geplant.

</details>

<details>
<summary><strong>Wird der Preis automatisch abgerechnet?</strong></summary>

Nein, PitStoply verwaltet nicht die Abrechnung der Services. Der angezeigte Preis ist rein informativ.

</details>

<details>
<summary><strong>Kann ich unterschiedliche Dauern je nach Fahrzeug haben?</strong></summary>

Nein, die Dauer ist pro Servicetyp festgelegt. Für Sonderfälle (SUV, Lieferwagen) können Sie nach der Buchung manuell anpassen.

</details>

<details>
<summary><strong>Wie gehe ich mit einem Service um, der länger dauert als geplant?</strong></summary>

Sie können den Termin im Kalender ändern, um seine Dauer zu verlängern, wenn das folgende Zeitfenster frei ist.

</details>
