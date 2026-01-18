# Externer Kalender

Synchronisieren Sie Ihre externen Kalender (Google, Outlook), um Doppelbuchungen zu vermeiden und Ihre Planung zu zentralisieren.

## Warum synchronisieren?

| Vorteil | Beschreibung |
|---------|--------------|
| **Konflikte vermeiden** | Ihre persönlichen Termine blockieren automatisch Zeitfenster |
| **Einheitliche Ansicht** | Alle Ihre Ereignisse an einem Ort |
| **Keine Doppeleingabe** | Nur ein Kalender zu verwalten |

---

## Unterstützte Kalender

PitStoply synchronisiert über **OneCal** mit:

| Kalender | Support |
|----------|---------|
| Google Calendar | ✅ |
| Microsoft Outlook | ✅ |
| Apple iCloud | ✅ |
| Andere (CalDAV) | ⚠️ Je nach Kompatibilität |

---

## Kalender verbinden

### Schritt 1: Auf die Einstellungen zugreifen

1. Gehen Sie zu **Einstellungen**
2. Klicken Sie auf **Externer Kalender** oder **Integrationen**

### Schritt 2: Verbindung hinzufügen

1. Klicken Sie auf **Kalender verbinden**
2. Wählen Sie den Anbieter (Google, Outlook usw.)
3. Sie werden zur Autorisierungsseite weitergeleitet

### Schritt 3: Zugriff autorisieren

1. Melden Sie sich bei Ihrem Konto an (Google, Microsoft usw.)
2. Autorisieren Sie PitStoply für den Zugriff auf Ihren Kalender
3. Sie werden zu PitStoply zurückgeleitet

### Schritt 4: Kalender auswählen

1. Wählen Sie, welche Kalender synchronisiert werden sollen
2. Definieren Sie die Synchronisierungsrichtung
3. Speichern Sie

---

## Synchronisierungsoptionen

### Synchronisierungsrichtung

| Option | Beschreibung |
|--------|--------------|
| **Nur Import** | Externe Ereignisse blockieren PitStoply-Zeitfenster |
| **Nur Export** | PitStoply-Termine erscheinen in Ihrem externen Kalender |
| **Bidirektional** | Beide Richtungen (empfohlen) |

### Synchronisierungsfrequenz

Die Synchronisierung erfolgt automatisch:
- Bei jeder Verbindung
- Alle 15-30 Minuten im Hintergrund
- Manuell über die Schaltfläche **Synchronisieren**

---

## Wie es funktioniert

### Externe Ereignisse → PitStoply

Wenn Sie ein Ereignis in Ihrem externen Kalender haben:

1. PitStoply erkennt das Ereignis
2. Das entsprechende Zeitfenster wird **blockiert**
3. Kunden können zu dieser Zeit nicht buchen

**Anzeige im Kalender:**
- Externe Ereignisse in hellgrau
- Label "Extern" oder Name des Quellkalenders

### PitStoply → Externer Kalender

Wenn ein Termin in PitStoply erstellt wird:

1. Das Ereignis wird in Ihrem externen Kalender erstellt
2. Details enthalten: Kunde, Service, Fahrzeug
3. Automatische Aktualisierung bei Terminänderung

---

## Verbindungen verwalten

### Verbundene Kalender anzeigen

Unter **Einstellungen > Externer Kalender** sehen Sie:
- Liste der verbundenen Konten
- Ausgewählte Kalender
- Status der letzten Synchronisierung

### Kalender trennen

1. Finden Sie die zu entfernende Verbindung
2. Klicken Sie auf **Trennen**
3. Bestätigen Sie

{% hint style="warning" %}
Das Trennen eines Kalenders löscht keine bestehenden Ereignisse in Ihrem externen Kalender.
{% endhint %}

### Manuell neu synchronisieren

Wenn Sie glauben, dass die Synchronisierung nicht aktuell ist:

1. Klicken Sie auf **Jetzt synchronisieren**
2. Warten Sie einige Sekunden
3. Überprüfen Sie Ihren Kalender

---

## Anwendungsfälle

### Ihre Ferien blockieren

1. Erstellen Sie ein "Ferien"-Ereignis in Google Calendar
2. PitStoply blockiert diese Tage automatisch
3. Keine manuelle Blockierung in PitStoply erforderlich

### Besprechungen und persönliche Termine

1. Ihre Teambesprechungen blockieren Zeitfenster
2. Ihre Arzttermine blockieren ebenfalls
3. Kein Kunde kann während dieser Zeiten buchen

### Mit dem Team teilen

1. Teilen Sie Ihren PitStoply-Kalender (via Export)
2. Das Team sieht die Termine in ihrem eigenen Kalender
3. Vereinfachte Koordination

---

## Fehlerbehebung

### Synchronisierung funktioniert nicht

1. Überprüfen Sie, ob die Verbindung aktiv ist
2. Versuchen Sie, zu trennen und wieder zu verbinden
3. Überprüfen Sie die erteilten Berechtigungen

### Ereignisse erscheinen nicht

1. Überprüfen Sie, ob der richtige Kalender ausgewählt ist
2. Warten Sie einige Minuten (Cache)
3. Erzwingen Sie eine manuelle Synchronisierung

### Doppelte Ereignisse

Wenn Sie Duplikate sehen:
1. Überprüfen Sie die Synchronisierungseinstellungen
2. Synchronisieren Sie nur einen Kalender pro Konto

---

## Häufige Fragen

<details>
<summary><strong>Ist die Synchronisierung sofort?</strong></summary>

Nein, es kann eine Verzögerung von einigen Minuten geben. Für dringende Änderungen verwenden Sie die manuelle Synchronisierung.

</details>

<details>
<summary><strong>Kann ich mehrere Kalender synchronisieren?</strong></summary>

Ja, Sie können mehrere Konten verbinden und mehrere Kalender pro Konto auswählen.

</details>

<details>
<summary><strong>Sind die Kundendetails in meinem externen Kalender sichtbar?</strong></summary>

Ja, exportierte Ereignisse enthalten den Kundennamen, den Service und das Fahrzeug. Stellen Sie sicher, dass Ihr externer Kalender gesichert ist.

</details>

<details>
<summary><strong>Was passiert, wenn ich ein externes Ereignis lösche?</strong></summary>

Das Zeitfenster wird bei der nächsten Synchronisierung in PitStoply wieder verfügbar.

</details>
