---
hero_tags: subpage pdf
title_above: Wissen
title: Anleitung der Erstinbetriebnahme des INTIA-Koffers
permalink: /knowhow/instructions/first_use
hero_image: /assets/img/uploads/neuigkeit-koffertermin-piksl-1.jpg
preview_image: /assets/img/uploads/neuigkeit-koffertermin-piksl-1.jpg
---

<!--StartFragment-->

Bevor der INTIA-Koffer benutzt werden kann, muss er für die Erstinbetriebnahme vorbereitet werden. Dafür gibt es zwei verschiedene Anleitungen: Eine Anleitung für die Erstinbetriebnahme des INTIA-Koffers **mit** Router, sowie eine Anleitung der Erstinbetriebnahme des INTIA-Koffers **ohne** Router. Die Anleitung für die Erstinbetriebnahme des INTIA-Koffers **ohne** Router findest du weiter unten.

### Anleitung zur Erstinbetriebnahme des INTIA-Koffers **mit** Router  

- Koffer öffnen
- Mini-Computer herausholen
- Router herausholen
- Licht mit Fassung herausholen und an den Stream stecken
- Router an den Strom
- Wenn Router an und nicht eingerichtet
- Mit einem WLAN-fähigen Gerät nachsehen, ob der Router ein WLAN freigegeben hat (in der Anleitung, welche dem Router beiliegt, nachschauen)
- Bei der Router-Einrichtung dem WLAN den Namen "INTIA" und das Passwort "BuntesLicht10" geben
- Andere Namen sind möglich, benötigen aber ein paar Extraschritte beim Mini-Computer
- Bei multiplen Koffern sollten unterschiedliche WLAN-Namen benutzt werden
- Nach der Einrichtung des Routers den Mini-Computer an den Strom geben

1. Wenn das WLAN "INTIA" heißt, verbindet sich der Computer von selbst. Auf dem Display erscheint eine Zahlenfolge, die folgender ähnelt "192.168.1.100"
2. Wenn das WLAN anders heißt:

   1. Nach einigen Minuten erscheint ein neues WLAN mit dem Namen "INTIA-(zufällige Zahlen)"
   2. Mit diesem WLAN verbinden
   3. Eine Webseite wird angezeigt auf der ein WLAN eingerichtet werden kann
   4. Nach fertigem Einrichten erscheint eine Zahlenfolge die folgender ähnelt "192.168.1.100"
   5. Wenn dies nicht geschieht den Mini-Computer neu starten und kurz warten

- Nun ein internetfähiges Endgerät (PC, Tablet, Smartphone) mit dem WLAN verbinden, mit dem der Mini-Computer verbunden ist
- Bei Mobilgeräten kann es zu Problemen kommen, wenn das WLAN keinen Internetzugriff dabei bietet. Die Mobilen Daten zu deaktivieren kann helfen
- In den Browser die Zahlenfolge eingeben, die auf dem Gerät angezeigt wird und dem Anhang ":1880/ui" bzw. "192.168.1.100:1880/ui". Eine Seite sollte sich öffnen
- Nun können die Glühbirnen hinzugefügt werden. Dafür findest du bald hier eine Anleitung.

Nun können alle anderen Smart-Geräte hinzugefügt werden.

Geräte, die nicht kommerziell erworben wurden, sondern zu unseren selbstgebauten Technik-Blöcken gehören, müssen anders hinzugefügt werden:

- Gerät mit Strom versorgen (die meisten USB-Ports reichen hierfür aus!)
- Nach einiger Zeit öffnet sich ein neues WLAN ohne Passwort
- Nachdem mit dem WLAN verbunden, sollte sich eine Webseite öffnen
- Auf dieser kann ein WLAN hinzugefügt werden

NodeRed

- gehe auf die Interne NodeRed Seite mit IP:1880
- Sind hier noch keine Flows (Flows sind die Programm-Abläufe) Importieren (Bilder)
- Importiere Wunsch-Flows aus unserer Sammlung
- - UI um die Page auf IP:1880/ui besuchbar zu machen
  - EscapeGame um das EscapeGame zu installieren
  - Verschiedene Beispiel-Flows für unsere Entwicklungen wie die Pomodoro-Kiste
- Geräte müssen nun den Nodes zugewiesen werden (Bilder)

EscapeGame

- Wurde das EscapeGame installiert oder wird ein PI-Image genutzt, das es vorinstalliert hat?
- Wurden folgenden Geräte korrekt in NodeRed einem Node zugewiesen?
- - Button
  - Glühbirne
  - Kiste (sollte bereits korrekt sein)
  - Keypad (sollte bereits korrekt sein)
- Eigentlich ist das EscapeGame beim ersten Mal aktiviert
- EscapeGame kann auf IP:1880/ui deaktiviert und aktiviert werden
- Dort können ebenfalls die verschiedenen Geräte observiert werden
- Wenn es nicht schon aktiv ist, bitte das EscapeGame aktivieren

### Anleitung zur Erstinbetriebnahme des INTIA-Koffers **ohne** Router  

- Koffer öffnen
- Mini-Computer herausholen
- Licht mit Fassung herausholen und an den Stream stecken
- Nach der Einrichtung des Routers den Mini-Computer an den Strom geben

1. 1. Nach einigen Minuten erscheint ein neues WLAN mit dem Namen "INTIA-(zufällige Zahlen)"
   2. Mit diesem WLAN verbinden
   3. Eine Webseite wird angezeigt, auf der ein WLAN eingerichtet werden kann
   4. Nach fertigem Einrichten erscheint eine Zahlenfolge die folgender ähnelt "192.168.1.100"
   5. Wenn dies nicht geschieht, den Mini-Computer neu starten und kurz warten

- Nun ein internetfähiges Endgerät (PC, Tablet, Smartphone) mit dem WLAN verbinden, mit dem der Mini-Computer verbunden ist
- Bei Mobilgeräten kann es zu Problemen kommen, wenn das WLAN keinen Internetzugriff dabei bietet. Die Mobilen Daten zu deaktivieren kann helfen
- In den Browser die Zahlenfolge eingeben, die auf dem Gerät angezeigt wird und dem Anhang ":1880/ui" beispielsweise "192.168.1.100:1880/ui". Eine Seite sollte sich öffnen
- Nun können die Glühbirnen hinzugefügt werden. Dafür findest du bald hier eine Anleitung.

Nun können alle anderen Smart-Geräte hinzugefügt werden.

Geräte, die nicht kommerziell erworben wurden, sondern zu unseren selbstgebauten Technik-Blöcken gehören, müssen anders hinzugefügt werden:

- Gerät mit Strom versorgen (die meisten USB-Ports reichen hierfür aus!)
- Nach einiger Zeit öffnet sich ein neues WLAN ohne Passwort
- Nachdem mit dem WLAN verbunden, sollte sich eine Webseite öffnen
- Auf dieser kann ein WLAN hinzugefügt werden

NodeRed

- gehe auf die Interne NodeRed Seite mit IP:1880
- Sind hier noch keine Flows (Flows sind die Programm-Abläufe) Importieren (Bilder)
- Importiere Wunsch-Flows aus unserer Sammlung
- - UI um die Page auf IP:1880/ui besuchbar zu machen
  - EscapeGame um das EscapeGame zu installieren
  - Verschiedene Beispiel-Flows für unsere Entwicklungen wie die Pomodoro-Kiste
- Geräte müssen nun den Nodes zugewiesen werden (Bilder)

EscapeGame

- Wurde das EscapeGame installiert oder wird ein PI-Image genutzt, das es vorinstalliert hat?
- Wurden folgenden Geräte korrekt in NodeRed einem Node zugewiesen?
- - Button
  - Glühbirne
  - Kiste (sollte bereits korrekt sein)
  - Keypad (sollte bereits korrekt sein)
- Eigentlich ist das EscapeGame beim ersten Mal aktiviert
- EscapeGame kann auf IP:1880/ui deaktiviert und aktiviert werden
- Dort können ebenfalls die verschiedenen Geräte observiert werden
- Wenn es nicht schon aktiv ist, bitte das EscapeGame aktivieren

<!--EndFragment-->
