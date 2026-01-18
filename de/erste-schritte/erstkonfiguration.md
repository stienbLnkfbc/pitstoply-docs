# Erstkonfiguration

Dieser Leitfaden begleitet Sie bei der Konfiguration Ihres PitStoply-Kontos in wenigen Minuten.

## Schritt 1: Unternehmensinformationen

Nach Ihrer ersten Anmeldung werden Sie von einem Konfigurationsassistenten geführt.

### Erforderliche Informationen

| Feld | Beschreibung | Beispiel |
|------|--------------|----------|
| **Unternehmensname** | Der Name, der Ihren Kunden angezeigt wird | Garage Martin AG |
| **Slug** | Personalisierte URL Ihrer Seite | garage-martin-ag |
| **Adresse** | Vollständige Adresse | Handelsstrasse 12, 8001 Zürich |
| **Telefon** | Hauptkontaktnummer | +41 44 123 45 67 |
| **E-Mail** | Kontakt-E-Mail | kontakt@garage-martin.ch |

{% hint style="info" %}
**Der Slug** definiert die Adresse Ihrer öffentlichen Buchungsseite. Zum Beispiel: `pitstoply.ch/garage-martin-ag`
{% endhint %}

## Schritt 2: Filialen und Hebebühnen

### Was ist eine Filiale?

Eine Filiale repräsentiert einen physischen Standort (eine Werkstatt, ein Atelier). Wenn Sie nur einen Standort haben, haben Sie nur eine Filiale.

### Was ist eine Hebebühne?

Eine Hebebühne repräsentiert einen Arbeitsplatz, an dem ein Termin durchgeführt werden kann (Hebebühne, Serviceplatz usw.). Termine werden bestimmten Hebebühnen zugewiesen.

### Konfiguration

1. **Erstellen Sie Ihre Filiale** mit Name und Adresse
2. **Fügen Sie Ihre Hebebühnen hinzu** (mindestens 1)
3. **Legen Sie die Öffnungszeiten** für jede Hebebühne fest

{% hint style="warning" %}
**Wichtig**: Die Anzahl der Filialen und Hebebühnen hängt von Ihrem Abonnementplan ab.
{% endhint %}

| Plan | Filialen | Hebebühnen |
|------|----------|------------|
| Independent | 1 | 1 |
| Multi-Lift | 1 | Unbegrenzt |
| Zusätzliche Filiale | +1 | - |

## Schritt 3: Dienstleistungen und Dauer

Konfigurieren Sie die Servicetypen, die Sie anbieten:

| Servicetyp | Beschreibung | Standarddauer |
|------------|--------------|---------------|
| Reifenwechsel | Komplette Montage/Demontage | 60 Min |
| Kompletträderwechsel | 2 Felgensätze | 30 Min |

### Dauer anpassen

Sie können die Dauer jedes Services nach Ihrer Organisation anpassen. Diese Dauern bestimmen die verfügbaren Zeitfenster in Ihrem Kalender.

## Schritt 4: Benachrichtigungen

Konfigurieren Sie, wie Ihre Kunden benachrichtigt werden:

### E-Mail (inklusive)

* **Bestätigung**: Wird automatisch nach der Buchung gesendet
* **Stornierung**: Wird automatisch nach Terminabsage gesendet
* **Erinnerung**: Wird 24h vor dem Termin gesendet
* **Erinnerung am Tag**: Wird 2h vor dem Termin gesendet
* **Verschiebung**: Wird gesendet, wenn der Termin geändert wird

### SMS (Guthaben erforderlich)

* Gleiches Prinzip wie E-Mails
* Erfordert den Kauf von SMS-Guthaben
* Konfigurierbar unter Einstellungen > SMS

{% hint style="info" %}
**Empfehlung**: Aktivieren Sie mindestens E-Mail-Erinnerungen, um No-Shows zu reduzieren.
{% endhint %}

## Schritt 5: Loslegen!

Sobald diese Schritte abgeschlossen sind:

1. ✅ Ihre Buchungsseite ist unter `pitstoply.ch/ihr-slug` erreichbar
2. ✅ Sie können Termine vom Dashboard aus erstellen
3. ✅ Ihre Kunden können online buchen

---

## Empfohlene nächste Schritte

* [ ] [Erscheinungsbild anpassen](../konfiguration/erscheinungsbild.md) (Logo, Farben)
* [ ] [Schliesszeiten konfigurieren](../konfiguration/schliesszeiten.md) (Urlaub, Feiertage)
* [ ] [Benutzer hinzufügen](../konfiguration/benutzer.md) (Mitarbeiter)
* [ ] [Buchung testen](../anleitungen/erster-termin.md) aus Kundensicht
