# Buchungsprobleme

Lösungen für häufige Probleme im Zusammenhang mit Buchungen und dem Kalender.

---

## Keine verfügbaren Zeitfenster

### Der Kunde sieht keine Zeitfenster

**Mögliche Ursachen:**

| Ursache | Lösung |
|---------|--------|
| Öffnungszeiten nicht konfiguriert | Überprüfen Sie **Einstellungen > Öffnungszeiten** |
| Geschlossener Tag | Überprüfen Sie, dass der Tag nicht als geschlossen markiert ist |
| Aktive Blockierung | Überprüfen Sie **Einstellungen > Schliessungen** |
| Alle Hebebühnen belegt | Die Zeitfenster sind tatsächlich ausgebucht |
| Externer Kalender | Ein externes Ereignis blockiert das Zeitfenster |

### Zu überprüfende Punkte

1. **Öffnungszeiten konfiguriert?**
   - Gehen Sie zu **Einstellungen > Öffnungszeiten**
   - Überprüfen Sie, dass der betreffende Tag Öffnungszeiten hat

2. **Aktive Blockierungen?**
   - Gehen Sie zu **Einstellungen > Schliessungen**
   - Überprüfen Sie, dass keine Blockierung für diesen Zeitraum besteht

3. **Externer Kalender?**
   - Wenn Sie einen externen Kalender synchronisiert haben
   - Überprüfen Sie, dass kein Ereignis das Zeitfenster blockiert

4. **Alle Hebebühnen?**
   - Überprüfen Sie, dass Sie mindestens eine aktive Hebebühne haben
   - Überprüfen Sie die spezifischen Zeiten jeder Hebebühne

---

## Das Zeitfenster ist verschwunden

### Ein Zeitfenster war verfügbar, ist es nicht mehr

**Mögliche Ursachen:**

1. **Jemand anderes hat gebucht**: Wer zuerst kommt, mahlt zuerst
2. **Sie haben einen Termin erstellt**: Das Zeitfenster ist jetzt belegt
3. **Externer Kalender aktualisiert**: Ein neues Ereignis blockiert
4. **Blockierung hinzugefügt**: Eine manuelle Blockierung wurde erstellt

### Lösung

Überprüfen Sie den Kalender an diesem Datum, um zu sehen, was das Zeitfenster belegt.

---

## Termin kann nicht erstellt werden

### Fehlermeldung bei der Erstellung

**Häufige Fehler:**

| Meldung | Ursache | Lösung |
|---------|---------|--------|
| "Zeitfenster nicht verfügbar" | Bereits gebucht | Wählen Sie ein anderes Zeitfenster |
| "Kunde erforderlich" | Kein Kunde ausgewählt | Wählen oder erstellen Sie einen Kunden |
| "Fahrzeug erforderlich" | Kein Fahrzeug | Fügen Sie dem Kunden ein Fahrzeug hinzu |
| "Ausserhalb der Zeiten" | Zeitfenster ausserhalb der Öffnungszeiten | Überprüfen Sie die Zeiten |

### Das Formular lädt nicht

1. Aktualisieren Sie die Seite (F5)
2. Leeren Sie den Browser-Cache
3. Probieren Sie einen anderen Browser
4. Überprüfen Sie Ihre Internetverbindung

---

## Termin nicht im Kalender sichtbar

### Der Termin wurde erstellt, erscheint aber nicht

**Überprüfungen:**

1. **Richtiges Datum?** Navigieren Sie zum Termindatum
2. **Richtige Filiale?** Wählen Sie die richtige Filiale im Filter
3. **Richtige Hebebühne?** Der Termin ist vielleicht auf einer anderen Hebebühne
4. **Status?** Ein stornierter Termin kann ausgeblendet sein

### Suche verwenden

1. Verwenden Sie die globale Suche (`Strg+K`)
2. Geben Sie den Kundennamen oder das Kennzeichen ein
3. Klicken Sie auf den Termin, um direkt dorthin zu gelangen

---

## Der Kunde kann seinen Termin nicht ändern

### Der Änderungslink funktioniert nicht

**Mögliche Ursachen:**

1. **Link abgelaufen**: Links haben eine begrenzte Gültigkeit
2. **Termin bereits vorbei**: Vergangene Termine können nicht geändert werden
3. **Termin storniert**: Der Termin wurde möglicherweise storniert

### Lösungen

1. Senden Sie eine neue Bestätigungs-E-Mail mit einem neuen Link
2. Ändern Sie den Termin selbst über das Dashboard
3. Erstellen Sie bei Bedarf einen neuen Termin

---

## Terminkonflikt

### Zwei Termine gleichzeitig auf derselben Hebebühne

Das sollte nicht passieren, da PitStoply Konflikte überprüft. Wenn es passiert:

1. **Überprüfen Sie die genauen Zeiten**: Vielleicht überschneiden sich die Termine nicht wirklich
2. **Verschieben Sie einen Termin**: Ändern Sie einen der beiden, um den Konflikt zu lösen
3. **Kontaktieren Sie den Support**, wenn das Problem weiterhin besteht

---

## Benachrichtigungen nicht gesendet

### Der Kunde hat keine Bestätigung erhalten

1. Überprüfen Sie, dass Benachrichtigungen in den Einstellungen **aktiviert** sind
2. Überprüfen Sie die **E-Mail-Adresse des Kunden** (keine Fehler)
3. Bitten Sie den Kunden, seinen **Spam** zu überprüfen
4. Für SMS überprüfen Sie Ihr **Guthaben**

[Siehe SMS-Fehlerbehebung](sms.md)

---

## Probleme mit der öffentlichen Buchungsseite

### Die Seite lädt nicht

1. Überprüfen Sie die URL: `pitstoply.ch/ihr-slug`
2. Überprüfen Sie, dass der Slug in Ihren Einstellungen korrekt ist
3. Versuchen Sie, den Browser-Cache zu leeren

### Die Seite ist leer (kein Service/Zeitfenster)

1. Überprüfen Sie, dass mindestens ein **Service aktiv** ist
2. Überprüfen Sie, dass mindestens eine **Hebebühne aktiv** ist
3. Überprüfen Sie die **Öffnungszeiten** der Filiale/Hebebühne

---

## Langsame Performance

### Der Kalender oder die Zeitfenster laden langsam

**Lösungen:**

1. Warten Sie einige Sekunden (normal bei vielen Daten)
2. Aktualisieren Sie die Seite
3. Vermeiden Sie, mehrere PitStoply-Tabs zu öffnen
4. Überprüfen Sie Ihre Internetverbindung

{% hint style="info" %}
Wenn Leistungsprobleme anhalten, kontaktieren Sie den Support mit Details zu Ihrer Situation (Anzahl Termine, verwendeter Browser).
{% endhint %}

---

## Support kontaktieren

Wenn keine Lösung funktioniert:

- **E-Mail**: support@pitstoply.ch
- Fügen Sie bei:
  - Beschreibung des Problems
  - Betroffenes Datum und Uhrzeit
  - Screenshots wenn möglich
  - Verwendeter Browser und Gerät
