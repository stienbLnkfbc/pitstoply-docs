# Filialen und Hebebühnen

Organisieren Sie Ihre Werkstatt, indem Sie Ihre Standorte (Filialen) und Arbeitsplätze (Hebebühnen) definieren.

## Schlüsselkonzepte

### Was ist eine Filiale?

Eine **Filiale** repräsentiert einen physischen Standort, an dem Sie tätig sind:
- Eine Werkstatt
- Ein Atelier
- Ein technisches Zentrum

Auch wenn Sie nur einen Standort haben, haben Sie eine Filiale.

### Was ist eine Hebebühne?

Eine **Hebebühne** repräsentiert einen Arbeitsplatz, der einen Termin bearbeiten kann:
- Ein Wagenheber
- Eine Servicebay
- Ein Arbeitsbereich

{% hint style="info" %}
**Die Anzahl der Hebebühnen bestimmt Ihre Kapazität**: 3 Hebebühnen = 3 gleichzeitige Termine im selben Zeitfenster möglich.
{% endhint %}

---

## Limits je nach Plan

| Plan | Filialen | Hebebühnen |
|------|----------|------------|
| **Independent** | 1 | 1 |
| **Multi-Lift** | 1-3 | Unbegrenzt |
| **Network** | Unbegrenzt | Unbegrenzt |

[Abonnementpläne ansehen](../abrechnung/plaene.md)

---

## Filialen verwalten

### Auf die Einstellungen zugreifen

1. Gehen Sie zu **Einstellungen > Filialen**
2. Sie sehen die Liste Ihrer Filialen

### Filiale erstellen

1. Klicken Sie auf **Neue Filiale**
2. Füllen Sie die Informationen aus:

| Feld | Beschreibung |
|------|--------------|
| **Name** | Name, der Kunden angezeigt wird (z.B. "Zürich Zentrum") |
| **Adresse** | Vollständige Adresse |
| **Telefon** | Kontaktnummer |
| **E-Mail** | Kontakt-E-Mail |

3. Klicken Sie auf **Speichern**

### Filiale bearbeiten

1. Klicken Sie auf die Filiale
2. Ändern Sie die Informationen
3. Speichern Sie

### Filiale löschen

{% hint style="danger" %}
**Achtung**: Das Löschen einer Filiale löscht alle ihre Hebebühnen und betrifft die zugehörigen Termine.
{% endhint %}

1. Öffnen Sie die Filiale
2. Klicken Sie auf **Löschen**
3. Bestätigen Sie

---

## Hebebühnen verwalten

### Auf die Hebebühnen zugreifen

1. In **Einstellungen > Filialen**
2. Klicken Sie auf eine Filiale
3. Sie sehen die Liste der Hebebühnen

### Hebebühne erstellen

1. Klicken Sie auf **Neue Hebebühne**
2. Füllen Sie die Informationen aus:

| Feld | Beschreibung |
|------|--------------|
| **Name** | Kennung der Hebebühne (z.B. "Hebebühne 1", "Brücke A") |
| **Beschreibung** | Interne Notizen (optional) |
| **Eigene Öffnungszeiten** | Falls anders als die Filiale |
| **Aktiv** | Akzeptiert die Hebebühne Buchungen? |

3. Klicken Sie auf **Speichern**

### Hebebühnen benennen

Tipps für klare Namen:

| ✅ Gut | ❌ Zu vermeiden |
|--------|----------------|
| "Hebebühne 1", "Hebebühne 2" | "a", "b" |
| "Wagenheber", "Schnellbay" | "test" |
| "Zone A", "Zone B" | Zu lange Namen |

{% hint style="tip" %}
Die Namen der Hebebühnen erscheinen im Kalender. Halten Sie sie kurz und erkennbar.
{% endhint %}

### Hebebühne deaktivieren

Wenn eine Hebebühne vorübergehend nicht verfügbar ist (defekt, Wartung):

1. Öffnen Sie die Hebebühne
2. Deaktivieren Sie **Aktiv**
3. Speichern Sie

Die Hebebühne akzeptiert keine Buchungen mehr, aber bestehende Termine bleiben erhalten.

### Hebebühne löschen

{% hint style="warning" %}
Bestehende Termine auf dieser Hebebühne werden betroffen sein. Deaktivieren Sie lieber, anstatt zu löschen.
{% endhint %}

---

## Öffnungszeiten der Hebebühnen

Standardmässig verwendet jede Hebebühne die Öffnungszeiten ihrer Filiale.

### Spezifische Öffnungszeiten festlegen

1. Öffnen Sie die Hebebühne
2. Aktivieren Sie **Eigene Öffnungszeiten**
3. Definieren Sie die Öffnungszeiten pro Tag
4. Speichern Sie

### Anwendungsfälle

| Situation | Lösung |
|-----------|--------|
| Hebebühne nur morgens | Öffnungszeiten 8-12 Uhr |
| Hebebühne nur Wochenende | Öffnungszeiten nur Samstag |
| Hebebühne Wartung am Montag | Montag geschlossen |

---

## Multi-Filialen-Organisation

### Wie Kunden wählen

Bei der Online-Buchung:
1. Der Kunde sieht zuerst die Filialen
2. Er wählt die gewünschte aus
3. Dann wählt er Datum und Zeitfenster

### Kalender pro Filiale

In Ihrem Kalender:
- Verwenden Sie den Auswähler, um zwischen Filialen zu wechseln
- Jede Filiale zeigt ihre Hebebühnen in Spalten

---

## Bewährte Praktiken

### Für eine einfache Werkstatt (1 Filiale)

```
Filiale: "Meine Werkstatt"
├── Hebebühne 1
├── Hebebühne 2
└── Hebebühne 3
```

### Für eine Werkstatt mit spezialisierten Bereichen

```
Filiale: "Garage Müller"
├── Reifen-Hebebühne 1
├── Reifen-Hebebühne 2
├── Mechanik-Hebebühne (andere Zeiten)
└── Schnellbay (15 Min pro Termin)
```

### Für ein Werkstattnetzwerk

```
Filiale: "Zürich Zentrum"
├── Hebebühne 1
├── Hebebühne 2

Filiale: "Winterthur"
├── Hebebühne 1

Filiale: "Baden"
├── Hebebühne 1
├── Hebebühne 2
├── Hebebühne 3
```

---

## Häufige Fragen

<details>
<summary><strong>Kann ich eine Filiale umbenennen ohne Daten zu verlieren?</strong></summary>

Ja, das Umbenennen löscht keine Daten. Bestehende Termine bleiben erhalten.

</details>

<details>
<summary><strong>Wie verschiebe ich eine Hebebühne von einer Filiale in eine andere?</strong></summary>

Es ist nicht möglich, eine Hebebühne zu verschieben. Sie müssen:
1. Eine neue Hebebühne in der Zielfiliale erstellen
2. Die alte Hebebühne löschen (oder deaktivieren)

</details>

<details>
<summary><strong>Wie viele Hebebühnen sollte ich erstellen?</strong></summary>

Erstellen Sie eine Hebebühne pro realem Arbeitsplatz, der einen Termin bearbeiten kann. Wenn Sie 2 Wagenheber haben, erstellen Sie 2 Hebebühnen.

</details>

<details>
<summary><strong>Kann eine Hebebühne mehrere Servicetypen bearbeiten?</strong></summary>

Ja, standardmässig können alle Hebebühnen alle Services bearbeiten. Eine spezifische Zuweisung pro Servicetyp ist für eine zukünftige Version geplant.

</details>
