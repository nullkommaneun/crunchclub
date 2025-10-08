  ______                                           __                  _______             __  __       
 /      \                                         /  |                /       \           /  |/  |      
/$$$$$$  |  ______   __    __  _______    _______ $$ |____   __    __ $$$$$$$  |  ______  $$ |$$ |      
$$ |  $$/  /      \ /  |  /  |/       \  /       |$$      \ /  |  /  |$$ |__$$ | /      \ $$ |$$ |      
$$ |      /$$$$$$  |$$ |  $$ |$$$$$$$  |/$$$$$$$/ $$$$$$$  |$$ |  $$ |$$    $$< /$$$$$$  |$$ |$$ |      
$$ |   __ $$ |  $$/ $$ |  $$ |$$ |  $$ |$$ |      $$ |  $$ |$$ |  $$ |$$$$$$$  |$$ |  $$ |$$ |$$ |      
$$ \__/  |$$ |      $$ \__$$ |$$ |  $$ |$$ \_____ $$ |  $$ |$$ \__$$ |$$ |  $$ |$$ \__$$ |$$ |$$ |      
$$    $$/ $$ |      $$    $$/ $$ |  $$ |$$       |$$ |  $$ |$$    $$ |$$ |  $$ |$$    $$/ $$ |$$ |      
 $$$$$$/  $$/        $$$$$$/  $$/   $$/  $$$$$$$/ $$/   $$/  $$$$$$$ |$$/   $$/  $$$$$$/  $$/ $$/       
                                                            /  \__$$ |                                  
                                                            $$    $$/                                   
                                                             $$$$$$/                                    

# 🍜 CrunchClub QR-Registrierung

Willkommen im offiziellen Repository des **CrunchClub QR-Systems**.  
Dieses Projekt macht aus jedem Besuch im Restaurant eine **digitale, fälschungssichere Stempelkarte** – ohne App, ohne Anmeldung, ohne Papier.

---

## ✨ Was ist das?

Das System ist ein **Bonus- und Mitgliedschaftsprogramm**, das direkt über das Smartphone der Gäste funktioniert.  
Statt einer klassischen Papiertreuekarte scannt man im CrunchClub einfach einen **QR-Code**.  

Die Teilnahme ist:

- ✅ **Anonym** – keine persönlichen Daten notwendig  
- ✅ **Einfach** – kein App-Download, nur der Browser  
- ✅ **Sofort sichtbar** – Gäste sehen direkt ihren Status  
- ✅ **Flexibel** – neue Aktionen, Kampagnen und Belohnungen sind jederzeit möglich  

---

## 🥢 Wie funktioniert das?

**1. QR-Code scannen**  
Am Tresen, auf dem Tisch oder auf Flyern – der Gast scannt den Code.

**2. Automatische Weiterleitung**  
Die Seite `go.html` übernimmt:
- Sie erstellt im Hintergrund eine **anonyme Kennung** für den Gast (einmalig pro Gerät).  
- Danach leitet sie den Aufruf an den Server weiter.

**3. Prüfung & Speicherung**  
Der Server prüft:
- Ist der QR-Code gültig?  
- Ist es ein neuer Besuch?  
- Wurde der Code schon einmal eingelöst?  

Das Ergebnis wird anonym gespeichert – ohne Namen, ohne E-Mail, ohne Telefonnummer.

**4. Rückmeldung auf dem Handy**  
Die Seite `thanks/index.html` zeigt sofort an:
- ✅ **Neu registriert** – erster Besuch, Mitgliedschaft angelegt  
- 👋 **Welcome Back** – wiederkehrender Gast, neuer Code zählt  
- ℹ️ **Bereits eingelöst** – Code wurde schon benutzt  

Zusätzlich werden **Besuche und eingelöste Codes** transparent angezeigt.

---

## 🍣 Warum ist das für Restaurants nützlich?

### Vorteile für Gäste
- Kein Papier, kein Verlieren von Stempelkarten  
- Sofortige Übersicht über Status und Punkte  
- Spielerisches, modernes Erlebnis  

### Vorteile für das Restaurant
- **Kundentreue aufbauen**: Jeder Besuch wird erfasst, Wiederkehrer werden belohnt  
- **Mehr Transparenz**: Übersicht über eingelöste QR-Codes  
- **Flexibilität**: Neue Codes für Events, Kampagnen, Specials oder saisonale Aktionen  
- **Kein Mehraufwand**: Gäste nutzen ihr eigenes Handy – keine zusätzliche Technik notwendig  
- **Sicher & anonym**: Keine sensiblen Daten, kein Risiko bei Datenschutz  

---

## 📈 Beispiel für den Einsatz

- „Nach 5 Besuchen ein kostenloses Topping“  
- „Exklusiver QR-Code bei der Eröffnungsparty – nur an diesem Tag gültig“  
- „Monatliche Kampagne: Sammle 3 Codes und erhalte ein Getränk gratis“  

---

## 🔒 Datenschutz & Vertrauen

- Es werden **keine personenbezogenen Daten** erfasst.  
- Jeder Gast erhält nur eine **anonyme Kennung**, die lokal im Browser gespeichert ist.  
- Keine Namen, keine Telefonnummern, keine E-Mails.  
- Nur anonyme, technische Daten wie Uhrzeit, QR-Code und Standort-ID.  

---

## 📂 Dieses Repository

In diesem Repo liegen die **öffentlichen Webseiten**:

- `go.html` → die Weiterleitungsseite nach dem QR-Scan  
- `thanks/index.html` → die Danke-Seite mit dem Status  

Die eigentliche Logik (Zählung, Regeln, Speicherung) läuft anonym im Hintergrund.

---

## 🚀 Kurz gesagt

Das CrunchClub QR-System ist die **digitale Stempelkarte für die Hosentasche**:  
- Keine Hürden für Gäste  
- Kein Aufwand für das Restaurant  
- Flexibel, fälschungssicher, modern  

> 👉 Gäste kommen öfter.  
> 👉 Das Restaurant steigert die Kundenbindung.  
> 👉 Und niemand verliert mehr eine Treuekarte.

---
