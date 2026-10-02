# Zaunteam – Windows-App

Die Windows-App zum **Zaunteam-Portal**. Sie zeigt das Portal in einem eigenen
Fenster auf dem Büro-PC – ohne Browser-Tabs, die man aus Versehen schließt.

- **Das Telefon klingelt auch bei geschlossenem Fenster.** Schließt man das
  Fenster, läuft Zaunteam im Hintergrund weiter (Z-Symbol unten rechts neben
  der Uhr). Anrufe und Meldungen kommen weiter an.
- Startet automatisch mit Windows, unsichtbar im Hintergrund.
- Die Anmeldung bleibt erhalten – einmal anmelden genügt.

---

## Herunterladen

### ➜ [Zaunteam-Setup.exe herunterladen](https://github.com/kucerenkodimitri/zaunteam-desktop/releases/latest/download/Zaunteam-Setup.exe)

Der Link liefert immer die neueste Version:
`https://github.com/kucerenkodimitri/zaunteam-desktop/releases/latest/download/Zaunteam-Setup.exe`

Was sich in welcher Version geändert hat, steht unter
[Releases](https://github.com/kucerenkodimitri/zaunteam-desktop/releases).

---

## Installieren

1. `Zaunteam-Setup.exe` herunterladen und **doppelklicken**.
2. Erscheint **„Der Computer wurde durch Windows geschützt“**:
   auf **Weitere Informationen** klicken, dann auf **Trotzdem ausführen**.
   Diese Meldung kommt, weil die App noch keine digitale Signatur hat.
   Sie ist kein Hinweis auf einen Virus.
3. Die Installation läuft von selbst durch – **ohne Administratorrechte**
   und ohne weitere Fragen. Danach öffnet sich Zaunteam.
4. Einmal mit dem gewohnten Portal-Zugang anmelden. Fertig.

Die App wird nur für den angemeldeten Windows-Benutzer installiert. Sie legt
eine Verknüpfung auf dem Desktop und im Startmenü an.

---

## Updates kommen automatisch

- Zaunteam prüft regelmäßig, ob es eine neue Version gibt, und lädt sie
  im Hintergrund.
- Danach erscheint die Meldung **„Zaunteam-Update bereit“**.
  - **Klick auf die Meldung:** Zaunteam startet neu und ist nach kurzer
    Zeit (meist unter einer Minute) wieder da.
  - **Kein Klick:** Das Update wird beim nächsten Start installiert,
    z. B. nach dem Neustart des PCs. Zaunteam schließt sich dann kurz nach
    dem Start einmal und öffnet sich mit der neuen Version wieder.
- Mitten im Betrieb startet Zaunteam **nie von selbst neu**. Läuft gerade
  ein Telefongespräch, fragt Zaunteam vor jedem Neustart nach.
- Anmeldung und Einstellungen bleiben bei Updates erhalten.

Man muss nichts tun. Nur wer Zaunteam neu auf einem PC einrichtet, lädt die
Setup-Datei oben herunter.

---

## Systemvoraussetzungen

- **Windows 10 oder Windows 11, 64-Bit**
- Internetverbindung
- etwa 500 MB freier Speicherplatz
- **Zum Telefonieren:** ein Mikrofon und Lautsprecher, am besten ein
  **Headset** (USB oder Bluetooth).
  In Windows muss der Mikrofonzugriff erlaubt sein:
  *Einstellungen → Datenschutz → Mikrofon →
  „Desktop-Apps den Zugriff auf das Mikrofon erlauben“* auf **Ein**.

---

## Deinstallieren

*Windows-Einstellungen → Apps → Zaunteam → Deinstallieren.*

Dabei wird auch der automatische Start mit Windows entfernt. Die gespeicherte
Anmeldung bleibt im Ordner `%APPDATA%\Zaunteam`. Wer sie nicht mehr braucht,
löscht diesen Ordner von Hand.

---

## Datenschutz in Kürze

- Die App **zeigt nur das Zaunteam-Portal** an
  (`https://zaunteam-portal.vercel.app`). Sie hat **keine eigenen Daten** –
  Kunden, Angebote und Anrufe liegen wie bisher im Portal.
- Auf dem PC speichert sie nur die Anmeldung, die Fenstergröße und ein kleines
  Fehlerprotokoll **ohne Namen und Telefonnummern**.
- Für Updates fragt sie hier bei GitHub nach der neuesten Version und lädt sie
  herunter. Dabei werden keine Portal-Daten übertragen.
- Fremde Internetseiten öffnet sie im normalen Browser, nicht in der App.

---

## Hinweis

Dieses Projekt enthält **nur die Installationsdateien** der App.
Der Quellcode liegt nicht hier. Fragen und Wünsche bitte direkt an Zaunteam.
