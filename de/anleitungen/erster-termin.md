# Ihren ersten Termin erstellen

Diese Anleitung zeigt Ihnen, wie Sie einen Termin erstellen, sei es vom Dashboard aus oder für einen Kunden, der online bucht.

## Methode 1: Vom Dashboard aus (Sie)

### Schritt 1: Zur Erstellung gelangen

1. Melden Sie sich bei PitStoply an
2. Klicken Sie im **Dashboard** auf **Neuer Termin**
   - Oder gehen Sie zu **Termine > Erstellen**

### Schritt 2: Kunden auswählen

Zwei Optionen:

| Option | Wann verwenden |
|--------|----------------|
| **Bestehender Kunde** | Der Kunde ist bereits in Ihrer Datenbank |
| **Neuer Kunde** | Erster Besuch des Kunden |

**Für einen bestehenden Kunden:**
1. Geben Sie Name, Vorname oder Telefonnummer ein
2. Wählen Sie den Kunden aus der Liste
3. Wählen Sie das betreffende Fahrzeug (oder fügen Sie eines hinzu)

**Für einen neuen Kunden:**
1. Klicken Sie auf **Neuer Kunde**
2. Füllen Sie die Grundinformationen aus (Name, Telefon)
3. Fügen Sie ein Fahrzeug hinzu (Kennzeichen erforderlich)

### Schritt 3: Service auswählen

Wählen Sie den Servicetyp:

| Service | Beschreibung | Typische Dauer |
|---------|--------------|----------------|
| Räderwechsel | Komplette Räder tauschen | 30 Min |
| Reifenwechsel | Montage/Demontage auf Felgen | 45 Min |

{% hint style="info" %}
Dauer und Preis können unter **Einstellungen > Services** angepasst werden.
{% endhint %}

### Schritt 4: Zeitfenster wählen

1. Wählen Sie die **Filiale** (falls mehrere)
2. Wählen Sie das **Datum** im Kalender
3. Wählen Sie ein **verfügbares Zeitfenster**
   - Grau hinterlegte Zeitfenster sind bereits belegt oder ausserhalb der Öffnungszeiten

{% hint style="tip" %}
**Tipp**: Wenn kein Zeitfenster verfügbar ist, überprüfen Sie:
- Die für diesen Tag konfigurierten Öffnungszeiten
- Eventuelle Blockierungen/Schliessungen
- Die Synchronisation mit externen Kalendern
{% endhint %}

### Schritt 5: Bestätigen

1. Überprüfen Sie die Zusammenfassung
2. Wählen Sie, ob Sie den Kunden benachrichtigen möchten
3. Klicken Sie auf **Termin erstellen**

Der Termin erscheint jetzt in Ihrem Kalender!

---

## Methode 2: Online-Buchung (durch den Kunden)

### Wie es für Ihre Kunden funktioniert

1. Der Kunde ruft Ihre Seite auf: `pitstoply.ch/ihr-slug`
2. Er wählt den gewünschten Service
3. Er wählt Datum und Zeitfenster
4. Er gibt seine Kontaktdaten ein
5. Er bestätigt die Buchung

### Was Sie sehen

- Der Termin erscheint automatisch in Ihrem Kalender
- Sie erhalten eine Benachrichtigung (falls konfiguriert)
- Der Kunde erhält eine Bestätigung per E-Mail (und SMS falls aktiviert)

### Ihren Buchungslink teilen

| Methode | Vorteil |
|---------|---------|
| **QR-Code** | Ideal für Schaufenster-Anzeige |
| **Direktlink** | Für E-Mails, Website, soziale Medien |
| **Eingebetteter Button** | Für Ihre bestehende Website |

---

## Methode 3: Über den Kunden-QR-Code

Wenn Sie bereits Kunden in Ihrer Datenbank haben:

1. Jeder Kunde hat einen **einzigartigen QR-Code**
2. Der Kunde scannt seinen QR (von seiner Kundenkarte oder E-Mail)
3. Er gelangt direkt zu seinem persönlichen Portal
4. Er kann mit seinen bereits registrierten Fahrzeugen buchen

{% hint style="success" %}
**Vorteil**: Der Kunde muss seine Informationen nicht bei jeder Buchung neu eingeben.
{% endhint %}

---

## Nach der Erstellung

### Termin ändern

1. Klicken Sie auf den Termin im Kalender
2. Ändern Sie die gewünschten Informationen
3. Speichern Sie

Eine Änderungsbenachrichtigung kann an den Kunden gesendet werden.

### Termin stornieren

1. Öffnen Sie den Termin
2. Klicken Sie auf **Stornieren**
3. Bestätigen Sie die Stornierung

Das Zeitfenster wird wieder für andere Buchungen verfügbar.

### Als erledigt markieren

Nachdem Sie den Service durchgeführt haben:
1. Öffnen Sie den Termin
2. Ändern Sie den Status auf **Erledigt**

Dies aktualisiert Ihre Statistiken und gibt das Zeitfenster endgültig frei.

---

## Terminstatus

| Status | Bedeutung | Farbe |
|--------|-----------|-------|
| **Ausstehend** | Gebucht, noch nicht bestätigt | Gelb |
| **Bestätigt** | Von Ihnen oder dem System bestätigt | Blau |
| **In Bearbeitung** | Kunde ist da, Arbeit läuft | Violett |
| **Erledigt** | Service durchgeführt | Grün |
| **Storniert** | Termin abgesagt | Rot |
| **Nicht erschienen** | Kunde ist nicht gekommen | Grau |

---

## Häufige Fragen

<details>
<summary><strong>Kann der Kunde seinen Termin selbst ändern?</strong></summary>

Ja! Jede Bestätigungs-E-Mail enthält einen Änderungslink. Der Kunde kann Datum/Uhrzeit ändern oder stornieren.

</details>

<details>
<summary><strong>Wie blockiere ich ein Zeitfenster ohne einen Termin zu erstellen?</strong></summary>

Verwenden Sie die Funktion **Blockierungen** unter Einstellungen > Schliesszeiten, um bestimmte Zeitfenster zu blockieren.

</details>

<details>
<summary><strong>Kann ich einen wiederkehrenden Termin erstellen?</strong></summary>

Derzeit muss jeder Termin einzeln erstellt werden. Eine Wiederholungsfunktion ist geplant.

</details>
