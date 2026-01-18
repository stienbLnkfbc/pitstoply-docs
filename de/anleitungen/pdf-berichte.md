# PDF-Berichte generieren

PitStoply ermöglicht Ihnen, PDF-Berichte zu generieren, um Ihre Tage zu planen und Ihre Aktivitäten zu verfolgen.

## Verfügbare Berichtstypen

| Bericht | Inhalt | Verwendung |
|---------|--------|------------|
| **Tagesplanung** | Termine des Tages, nach Hebebühne | Werkstatt-Anzeige |
| **Wochenplanung** | Termine der Woche | Team-Planung |
| **Multi-Filialen-Export** | Alle Planungen als ZIP | Multi-Standort-Netzwerke |

---

## Tagesbericht generieren

### Vom Kalender aus

1. Gehen Sie zum **Kalender**
2. Wählen Sie das gewünschte Datum
3. Klicken Sie auf **PDF-Bericht** oder das Druckersymbol
4. Das PDF wird heruntergeladen

### Inhalt des Tagesberichts

Der Bericht enthält:

- **Kopfzeile**: Logo, Werkstattname, Datum
- **Pro Hebebühne**: Terminliste mit:
  - Beginn-/Endzeit
  - Kunde (Name, Telefon)
  - Fahrzeug (Kennzeichen, Marke)
  - Angeforderter Service
  - Eventuelle Notizen
- **Zusammenfassung**: Gesamtzahl der Termine

### Typische Verwendung

- Drucken Sie die Planung und hängen Sie sie in der Werkstatt auf
- Verteilen Sie jedem Techniker seine Tagesplanung
- Behalten Sie eine Papier-Aufzeichnung der Termine

---

## Wochenbericht generieren

### Vom Kalender aus

1. Gehen Sie zum **Kalender**
2. Wechseln Sie zur **Wochen**-Ansicht
3. Klicken Sie auf **PDF-Bericht**
4. Wählen Sie die zu exportierende Woche

### Inhalt des Wochenberichts

- Komprimierte Ansicht der gesamten Woche
- Termine nach Tag gruppiert
- Wochenstatistiken:
  - Gesamtzahl der Termine
  - Aufteilung nach Service
  - Auslastungsrate

---

## Multi-Filialen-Export (ZIP)

Wenn Sie mehrere Filialen haben, exportieren Sie alle Planungen auf einmal:

1. Gehen Sie zu **Kalender** oder **Berichte**
2. Klicken Sie auf **Multi-Filialen-Export**
3. Wählen Sie:
   - Den Zeitraum (Tag oder Woche)
   - Die einzubeziehenden Filialen
4. Laden Sie die ZIP-Datei herunter

Das ZIP enthält ein PDF pro Filiale.

---

## Berichts-Personalisierung

### Personalisierte Elemente

Die Berichte übernehmen automatisch:

| Element | Quelle |
|---------|--------|
| **Logo** | Einstellungen > Erscheinungsbild |
| **Werkstattname** | Einstellungen > Identität |
| **Kontaktdaten** | Filialeinstellungen |

### Berichtssprache

Der Bericht wird in der Sprache Ihres Kontos generiert (DE oder FR).

---

## Bericht drucken

### Druckempfehlungen

| Parameter | Empfehlung |
|-----------|------------|
| **Format** | A4 |
| **Ausrichtung** | Hochformat (täglich) oder Querformat (wöchentlich) |
| **Ränder** | Normal |
| **Farbe** | Schwarz-Weiss reicht aus |

### Direktdruck

Vom heruntergeladenen PDF:
1. Öffnen Sie die Datei
2. `Strg+P` (oder `Cmd+P` auf Mac)
3. Wählen Sie Ihren Drucker
4. Drucken

---

## Automatisierung (geplant)

{% hint style="info" %}
**Geplante Funktion**: Automatischer Versand der Planung per E-Mail jeden Morgen.
{% endhint %}

In der Zwischenzeit können Sie den Bericht jeden Tag manuell generieren.

---

## Häufige Fragen

<details>
<summary><strong>Kann ich den Berichtsinhalt anpassen?</strong></summary>

Derzeit ist das Format standardisiert. Eine erweiterte Anpassung ist in einer zukünftigen Version geplant.

</details>

<details>
<summary><strong>Werden die Berichte gespeichert?</strong></summary>

Nein, die Berichte werden auf Anfrage generiert. Sie können sie nach dem Download lokal speichern.

</details>

<details>
<summary><strong>Kann ich einen Bericht für einen vergangenen Zeitraum generieren?</strong></summary>

Ja, navigieren Sie im Kalender zum vergangenen Datum oder zur vergangenen Woche und generieren Sie dann den Bericht normal.

</details>

<details>
<summary><strong>Enthält der Bericht stornierte Termine?</strong></summary>

Nein, nur bestätigte und ausstehende Termine erscheinen in den Berichten.

</details>
