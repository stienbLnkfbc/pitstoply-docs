# Den Kalender verwenden

Der Kalender ist Ihr zentrales Werkzeug zur Visualisierung und Verwaltung aller Termine.

## Übersicht

### Zum Kalender gelangen

1. Klicken Sie im Hauptmenü auf **Kalender**
2. Oder klicken Sie im Dashboard auf **Kalender anzeigen**

### Ansichtstypen

| Ansicht | Ideal für |
|---------|-----------|
| **Tag** | Detaillierte Planung, volle Tage |
| **Woche** | Wöchentliche Übersicht |
| **Timeline** | Alle Hebebühnen nebeneinander sehen |

{% hint style="tip" %}
**Empfehlung**: Die **Timeline**-Ansicht ist am praktischsten für Werkstätten mit mehreren Hebebühnen, da sie alle Arbeitsplätze in Spalten anzeigt.
{% endhint %}

---

## Im Kalender navigieren

### Datum wechseln

| Aktion | Wie |
|--------|-----|
| Vorheriger/nächster Tag | Pfeile `<` und `>` |
| Vorherige/nächste Woche | Navigationsschaltflächen |
| Bestimmtes Datum | Auf den Datumsauswähler klicken |
| Heute | Schaltfläche **Heute** |

### Nach Filiale filtern

Wenn Sie mehrere Filialen haben:
1. Verwenden Sie den Filialenauswähler oben
2. Es werden nur die Hebebühnen dieser Filiale angezeigt

---

## Den Kalender lesen

### Auf jedem Termin angezeigte Informationen

Jeder Terminblock zeigt:
- **Uhrzeit** des Beginns
- **Kunde** (Vor-/Nachname)
- **Service** (Symbol)
- **Fahrzeug** (Kennzeichen)
- **Status** (Badge-Farbe)

### Farbcode der Status

| Farbe | Status | Bedeutung |
|-------|--------|-----------|
| 🟡 Gelb | Ausstehend | Nicht bestätigt |
| 🔵 Blau | Bestätigt | Bereit für den Tag |
| 🟣 Violett | In Bearbeitung | Kunde da, Arbeit läuft |
| 🟢 Grün | Erledigt | Service durchgeführt |
| 🔴 Rot | Storniert | Termin abgesagt |
| ⚪ Grau | Nicht erschienen | No-Show |

---

## Schnellaktionen

### Termin vom Kalender aus erstellen

1. **Doppelklicken** Sie auf ein freies Zeitfenster
2. Das Erstellungsformular öffnet sich mit vorausgefülltem Datum/Uhrzeit
3. Vervollständigen Sie die Informationen und speichern Sie

### Termin ändern

1. **Klicken** Sie auf den Termin
2. Ein Detailfenster öffnet sich
3. Klicken Sie auf **Bearbeiten**
4. Nehmen Sie Ihre Änderungen vor
5. Speichern Sie

### Termin verschieben (Drag & Drop)

1. Klicken und halten Sie den Termin
2. Ziehen Sie ihn zum neuen Zeitfenster
3. Lassen Sie los zum Bestätigen

{% hint style="warning" %}
**Achtung**: Das Verschieben ist nur zu verfügbaren Zeitfenstern möglich (offene Zeiten, kein Konflikt).
{% endhint %}

### Status schnell ändern

1. Klicken Sie auf den Termin
2. Ändern Sie im Detailbereich den Status
3. Der Kalender aktualisiert sich automatisch

---

## Externe Ereignisse (synchronisierte Kalender)

Wenn Sie einen externen Kalender (Google, Outlook) verbunden haben:

### Wie sie angezeigt werden

- Externe Ereignisse werden in **Hellgrau** angezeigt
- Sie blockieren das Zeitfenster (keine Buchung möglich)
- Sie tragen die Bezeichnung "Extern" oder den Namen des Quellkalenders

### Warum synchronisieren?

| Vorteil | Beschreibung |
|---------|--------------|
| Konflikte vermeiden | Ein privater Termin blockiert automatisch |
| Einheitliche Ansicht | Alle Ihre Ereignisse an einem Ort |
| Bidirektional | PitStoply-Termine erscheinen in Ihrem Kalender |

[Kalendersynchronisation konfigurieren](../konfiguration/externer-kalender.md)

---

## Blockierungen und Schliessungen

### Blockierte Zeitfenster

Nicht verfügbare Zeitfenster erscheinen:
- In **Dunkelgrau**: Ausserhalb der Öffnungszeiten
- Mit **Schraffur**: Manuelle Blockierung (Schliessung, Urlaub)

### Blockierung vom Kalender aus erstellen

1. Doppelklicken Sie auf das zu blockierende Zeitfenster
2. Wählen Sie **Blockierung erstellen**
3. Definieren Sie Dauer und Grund
4. Bestätigen Sie

---

## Berichte und Exporte

### Planung drucken

1. Klicken Sie in der Tages- oder Wochenansicht auf **Drucken**
2. Der Browser öffnet eine druckbare Version
3. Drucken Sie oder speichern Sie als PDF

### PDF-Bericht

1. Klicken Sie auf **Bericht**
2. Wählen Sie den Zeitraum (Tag, Woche)
3. Wählen Sie die Filialen
4. Laden Sie das PDF herunter

{% hint style="info" %}
Der PDF-Bericht enthält alle Termindetails: Kunde, Fahrzeug, Service, Notizen.
{% endhint %}

---

## Kalendereinstellungen

### Anzeige anpassen

Unter **Einstellungen > Kalenderanzeige** (falls verfügbar):
- Erste angezeigte Stunde
- Letzte angezeigte Stunde
- Zeitfenster-Inkrement (15, 30, 60 Min)

### Benachrichtigungen bei neuen Terminen

Sie können eine Benachrichtigung erhalten, wenn ein neuer Termin erstellt wird (von einem Online-Kunden):
- Browser-Benachrichtigung
- E-Mail
- Ton

---

## Tastenkürzel

| Kürzel | Aktion |
|--------|--------|
| `←` `→` | Vorheriger/nächster Tag |
| `T` | Zurück zu heute |
| `D` | Tagesansicht |
| `W` | Wochenansicht |
| `N` | Neuer Termin |

---

## Häufige Fragen

<details>
<summary><strong>Warum sind einige Zeitfenster ausgegraut?</strong></summary>

Ausgegraute Zeitfenster sind nicht verfügbar, weil:
- Ausserhalb der konfigurierten Öffnungszeiten
- Durch eine Schliessung/Urlaub blockiert
- Durch ein externes Ereignis belegt (synchronisierter Kalender)

</details>

<details>
<summary><strong>Kann ich den Kalender mehrerer Filialen gleichzeitig sehen?</strong></summary>

Derzeit zeigt der Kalender jeweils eine Filiale an. Verwenden Sie den Auswähler, um zwischen Filialen zu wechseln.

</details>

<details>
<summary><strong>Wie sehe ich schnell die Termine der nächsten Woche?</strong></summary>

Klicken Sie auf den Pfeil `>` oder verwenden Sie den Datumsauswähler, um direkt zur gewünschten Woche zu navigieren.

</details>
