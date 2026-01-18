# Öffnungszeiten

Konfigurieren Sie Ihre Öffnungszeiten präzise, damit die Buchungszeitfenster Ihrer tatsächlichen Verfügbarkeit entsprechen.

## Die Hierarchie der Öffnungszeiten verstehen

PitStoply verwaltet Öffnungszeiten auf zwei Ebenen:

```
Filiale (Standard)
    └── Hebebühne 1 (kann eigene Zeiten haben)
    └── Hebebühne 2 (kann eigene Zeiten haben)
    └── Hebebühne 3 (verwendet Filialzeiten)
```

{% hint style="info" %}
**Standardmässig** verwenden alle Hebebühnen die Öffnungszeiten ihrer Filiale. Sie können bei Bedarf spezifische Zeiten pro Hebebühne festlegen.
{% endhint %}

---

## Öffnungszeiten der Filiale konfigurieren

### Auf die Einstellungen zugreifen

1. Gehen Sie zu **Einstellungen > Öffnungszeiten**
2. Wählen Sie die betreffende Filiale

### Öffnungszeiten pro Tag festlegen

Für jeden Wochentag:

| Feld | Beschreibung |
|------|--------------|
| **Geöffnet** | Ist der Tag ein Arbeitstag? |
| **Öffnungszeit** | Beginn der verfügbaren Zeitfenster |
| **Schliesszeit** | Ende der verfügbaren Zeitfenster |

**Typisches Beispiel:**

| Tag | Öffnung | Schliessung |
|-----|---------|-------------|
| Montag | 08:00 | 18:00 |
| Dienstag | 08:00 | 18:00 |
| Mittwoch | 08:00 | 18:00 |
| Donnerstag | 08:00 | 18:00 |
| Freitag | 08:00 | 17:00 |
| Samstag | 08:00 | 12:00 |
| Sonntag | Geschlossen | - |

### Geschlossener Tag

Um einen Tag als geschlossen zu markieren:
1. Deaktivieren Sie das Kontrollkästchen **Geöffnet** für diesen Tag
2. Oder lassen Sie die Uhrzeiten leer

---

## Öffnungszeiten einer spezifischen Hebebühne konfigurieren

Wenn eine Hebebühne andere Zeiten hat als die Filiale:

### Warum Zeiten pro Hebebühne?

| Situation | Lösung |
|-----------|--------|
| Eine Hebebühne nur morgens verfügbar | Spezifische Zeiten |
| Eine Hebebühne mit Teilzeit-Mitarbeiter | Reduzierte Zeiten |
| Eine Hebebühne für bestimmte Services reserviert | Angepasste Zeiten |

### Wie konfigurieren

1. Gehen Sie zu **Einstellungen > Filialen**
2. Klicken Sie auf die Filiale
3. Wählen Sie die Hebebühne
4. Aktivieren Sie **Eigene Öffnungszeiten**
5. Definieren Sie die spezifischen Zeiten

{% hint style="tip" %}
Die Zeiten der Hebebühne **ersetzen** die der Filiale. Wenn die Hebebühne montags 8-12 Uhr geöffnet ist, aber die Filiale 8-18 Uhr, ist nur 8-12 Uhr für diese Hebebühne verfügbar.
{% endhint %}

---

## Mittagspause

Um eine Mittagspause zu blockieren:

### Option 1: Über wiederkehrende Schliessungen

1. Gehen Sie zu **Einstellungen > Schliessungen**
2. Erstellen Sie eine wiederkehrende Blockierung:
   - Uhrzeit: 12:00 - 14:00
   - Wiederholung: Alle Arbeitstage
   - Grund: Mittagspause

### Option 2: Aufgeteilte Öffnungszeiten

Erstellen Sie zwei Zeitblöcke pro Tag:
- Vormittag: 08:00 - 12:00
- Nachmittag: 14:00 - 18:00

{% hint style="warning" %}
**Hinweis**: Die Verwaltung mehrerer Zeitblöcke pro Tag hängt von Ihrer Version ab. Kontaktieren Sie den Support, wenn diese Option nicht verfügbar ist.
{% endhint %}

---

## Saisonale Öffnungszeiten

Wenn sich Ihre Öffnungszeiten je nach Saison ändern (Sommer/Winter):

### Vorgehensweise

1. Ändern Sie die Zeiten zu Beginn jeder Saison
2. Oder verwenden Sie Blockierungen für Ausnahmezeiten

### Beispiel: Sommerzeiten

| Tag | Winter | Sommer |
|-----|--------|--------|
| Samstag | 08:00 - 12:00 | 07:00 - 14:00 |

{% hint style="info" %}
**Tipp**: Planen Sie eine Erinnerung in Ihrem Kalender, um sich an die Zeitenänderung bei Saisonwechsel zu erinnern.
{% endhint %}

---

## Auswirkung auf Buchungen

### Angezeigte Zeitfenster

Kunden sehen **nur** die Zeitfenster, die Ihren Öffnungszeiten entsprechen:
- Ausserhalb der Zeiten = unsichtbar
- Während der Zeiten = sichtbar (ausser wenn bereits belegt)

### Servicedauer

Ein Zeitfenster wird nur angeboten, wenn der Service **vollständig** vor Schliessung durchgeführt werden kann.

**Beispiel**:
- Schliessung um 18:00
- Service von 45 Minuten
- Letztes angebotenes Zeitfenster: 17:15

---

## Konfiguration überprüfen

### Schnelltest

1. Öffnen Sie Ihre öffentliche Buchungsseite
2. Navigieren Sie zu verschiedenen Tagen
3. Überprüfen Sie, ob die Zeitfenster Ihren Erwartungen entsprechen

### Zu überprüfende Punkte

- [ ] Geschlossene Tage zeigen keine Zeitfenster
- [ ] Zeitfenster beginnen zur Öffnungszeit
- [ ] Die letzten Zeitfenster respektieren die Schliesszeit
- [ ] Hebebühnen mit eigenen Zeiten funktionieren

---

## Häufige Fragen

<details>
<summary><strong>Kann ich jede Woche unterschiedliche Zeiten haben?</strong></summary>

Nein, die Zeiten werden pro Wochentag definiert und gelten für alle Wochen. Für punktuelle Ausnahmen verwenden Sie die **Schliessungen**.

</details>

<details>
<summary><strong>Wie blockiere ich ein bestimmtes Zeitfenster, ohne den ganzen Tag zu schliessen?</strong></summary>

Verwenden Sie **Einstellungen > Schliessungen**, um eine Blockierung für ein bestimmtes Zeitfenster zu erstellen (z.B. 10:00-11:00 am 15. Januar).

</details>

<details>
<summary><strong>Beeinflussen Zeitenänderungen bestehende Termine?</strong></summary>

Nein, bereits gebuchte Termine bleiben gültig. Die neuen Zeiten gelten nur für neue Buchungen.

</details>

<details>
<summary><strong>Wie manage ich einen Teilzeit-Mitarbeiter?</strong></summary>

Erstellen Sie eine Hebebühne, die diesem Mitarbeiter gewidmet ist, mit seinen eigenen Zeiten. So ist diese Hebebühne nur verfügbar, wenn der Mitarbeiter anwesend ist.

</details>
