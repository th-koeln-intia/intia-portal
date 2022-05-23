---
hero_tags: subpage pdf
title_above: Anleitungen
breadcrumbs: [Wissen, Anleitungen]
title: Anleitung der Erstinbetriebnahme des INTIA-Koffers
permalink: /wissen/anleitungen/erstbenutzung
hero_image: /assets/img/uploads/neuigkeit-koffertermin-piksl-1.jpg
preview_image: /assets/img/uploads/neuigkeit-koffertermin-piksl-1.jpg
---

<!--StartFragment-->

Herzlichen Glückwunsch! Du hast einen INTIA Koffer erworben.

Um damit arbeiten zu können wird WLAN benötigt. Ähnlich wie man es vom Smartphone oder Computer kennt. Dafür gibt es zwei verschiedene Möglichkeiten: Einmal die Erstinbetriebnahme mit einem dedizierten Router und einmal ohne Router. Letzterer nutzt ein bereits existierendes WLAN. Die Nachfolgende Anleitung umfasst beide Optionen, dabei sind Schritte wo es unterschiede gibt mit einem "\*" gekennzeichnet.

{% include highlighter.html min-height25p=false content="

#### Brauche ich einen dedizierten Router oder nicht?

Wenn du planst den Koffer in verschiedene Einrichtungen mitzunehmen und dabei unabhängig sein möchtest empfiehlt sich die Nutzung eines dedizierten Routers. Hierfür haben wir Empfehlungen in der Einkaufsliste hinterlegt.

Arbeitest du innerhalb einer Einrichtung oder bist dir sicher das du an deinem Zielort WLAN hast, kannst du auf einen eigenen Router verzichten und das bereits existierende Netz nutzen. ABER: Hierbei muss man allen Bausteinen das zu nutzende Netzwerk mitteilen.

" %}

## Anleitung zur Erstinbetriebnahme des INTIA-Koffers  

1. Koffer öffnen

2. \*Router herausholen
   (Weißes Element mit der großen "1" drauf)
3. \*Router mit dem mitgelieferten USB-Kabel an den Strom anschließen. Der Router ist jetzt einsatzbereit.
   (Schwarzes Element mit der Nummer 5 ist ein USB-Hub, also eine Box die mit einem Stromstecker mehrere USB-Anschlüsse anbietet. Die dafür benötigten Kabel befinden sind in der Mitte unten)

{% include highlighter.html min-height25p=false content='

#### Wenn der Router noch nicht eingerichtet ist

Sollte der Router noch nicht eingerichtet sein sollte zuvor die Ersteinrichtung durchgeführt werden.

- Der Anleitung des Herstellers folgen
- Mit einem WLAN-fähigen Gerät nachsehen, ob der Router ein WLAN freigegeben hat
- Bei der Router-Einrichtung dem WLAN den Namen "INTIA" und das Passwort "BuntesLicht10" geben

Andere Namen sind möglich, benötigen aber ein paar Extraschritte beim Mini-Computer

' %}

4. Mini-Computer herausholen
   (Grünes Element mit Wabenmuster im Bild oben)

{% include highlighter.html min-height25p=false content="

#### Wenn der Mini-Computer noch nicht eingerichtet ist

Anleitung zur Einrichtung des Mini-Computers folgen. Siehe: https://intia.de/wissen/anleitungen/installation
" %}

5. Lampenfassung herausholen. Sicherstellen, dass eine Steckdose (ggf. durch Bereitstellen einer Mehrfachsteckdose oder eines Verlängerungskabel) in der Nähe ist. Lampenfassung an den Strom stecken.
   (Unten rechts im Bild. Ggfs. kann es sich hierbei auch um eine andere sogenannte GU10 Fassung handeln. Diese sieht etwas anders aus wird am genauso benutzt)
6. Genauso mit allen anderen Elementen im Koffer verfahren, die man nutzen möchte.
   (Nicht alle Elemente im Koffer benötigen einen Stromanschluss. Diese Geräte sind Batteriebetrieben und es kann vorkommen das diese gewechselt werden müssen)

### Nach der Einrichtung des Routers mit dem Mini-Computer fortfahren: Ein eigenes WLAN erstellen

1. Mini-Computer an den Strom und ein paar Minuten warten
   (Hierfür ein weiteres der mitgelieferten Kabel nutzen über den USB-Hub)
2. \*Wenn das WLAN "INTIA" heißt, verbindet sich der Mini-Computer von selbst. Auf dem Display erscheint eine Zahlenfolge, die folgender ähnelt "192.168.1.100"
   (Dies ist nur bei einem Koffer mit dedizierten Router möglich)
   a. Zahlenfolge bitte als "ADRESSE" notieren
3. \*Wenn das WLAN anders heißen sollte:
   (Dies ist der Fall wenn man ein existierendes Netzwerk nutzt)
   a. Nach einigen Minuten erscheint ein neues WLAN mit dem Namen "INTIA-(zufällige Zahlen)"
   b. Mit diesem WLAN verbinden
   c. Eine Webseite wird angezeigt auf der ein WLAN eingerichtet werden kann
   d. Nach fertigem Einrichten erscheint eine Zahlenfolge die folgender ähnelt "192.168.1.100"
   e. Wenn dies nicht geschieht den Mini-Computer neu starten und kurz warten
4. Nun ein internetfähiges Endgerät (PC, Tablet, Smartphone) mit dem WLAN verbinden, mit dem der Mini-Computer verbunden ist. Es erscheint die Meldung "kein gesichertes Netz", das ist aber kein Grund zur Sorge. So lange man mit dem WLAN verbunden ist, ist man nicht mehr im regulären Internet, sondern in einem kleinen Raum.
   a. Bei Mobilgeräten kann es zu Problemen kommen, wenn das WLAN nicht auch einen Internetzugriff bietet. Die Mobilen Daten zu deaktivieren kann helfen
5. In den Internet-Browser (Chrome, Firefox usw.) die zuvor Notierte "ADRESSE" mit dem Anhang ":1880/ui" eingeben (Zum Beispiel: "192.168.1.100:1880/ui"). Eine Seite sollte sich öffnen. Es kann sein das der Browser eine Warnung ausspricht und die Seite als "nicht sicher" angibt. Da es sich hierbei um eine lokale Seite (von unserem Mini-Computer) handelt und nicht eine Internetadresse kann dies Bedenkenlos geöffnet werden. Also keine Sorge!
   a. Auf dieser Seite findet man eine Grafische Oberfläche mit der man die Koffer-Inhalte steuern kann.
   b. Sollte diese Seite noch nicht vor konfiguriert sein muss der Anleitung zur: grafischen Oberfläche gefolgt werden.
   c. Z.B. kann hier das Escape Game de- und aktiviert werden.
   d. Ist das Escape Game deaktiviert, kann das Licht frei gesteuert werden. Probiere einmal mit der Lampe aus, ob es geklappt hat.
6. Nun können Glühbirne, Knöpfe und alle anderen Bausteine hinzugefügt werden. Dafür findest du HIER eine Anleitung.

![](/assets/img/instructions/intia_nodered_dashboard.png)

Abschließend kann getestet werden ob nicht nur mit der notierten ADRESSE diese Seite erreicht werden kann sondern auch folgende Adressen funktionieren:

- http://intia:1880/ui - Das Dashboard
- http://intia:1880/ - Die Programmierumgebung
- http://intia:8080/ - Oberfläche zum einrichten und Steuern der Zigbee-Bausteine

#### Geräte, die nicht kommerziell erworben wurden, sondern zu unseren selbstgebauten Technik-Blöcken gehören, müssen anders hinzugefügt werden

1. Gerät an Strom anschließen (die meisten USB-Ports reichen hierfür aus!)
2. Nach einiger Zeit öffnet sich ein neues WLAN ohne Passwort
3. Nachdem mit dem WLAN verbunden, sollte sich eine Webseite öffnen
4. Auf dieser kann ein WLAN hinzugefügt werden

### Grafische Oberfläche

1. Wir befinden uns auf der grafischen Oberfläche oder diese ist nicht erreichbar unter der zuvor notierten "ADRESSE" mit dem Anhang ":1880/ui"
2. Dann müssen wir erst noch die Konfiguration dieser Oberfläche einrichten. Dafür geht man auf die zuvor Notierte "ADRESSE" und dem Anhang ":1880" oder http://intia:1880/.
3. Wir sehen jetzt eine Oberfläche die sich Node-Red nennt.
4. Sind hier noch keine Flows (Flows sind die Programm-Abläufe) vorhanden, müssen sie importiert werden (Bilder)
5. Importiere Wunsch-Flows aus unserer Sammlung
   a. Ein Dashboard um die Webseite auf ADRESSE:1880/ui besuchbar zu machen
   b. Escape Game um das Escape Game zu installieren
   c. Verschiedene Beispiel-Flows für unsere Entwicklungen wie die Pomodoro-Kiste
6. Geräte müssen nun den Nodes zugewiesen werden (Bilder)

### Escape Game

In diesem Teil wird kurz beschrieben wie man die Bausteine mit dem Escape Game verwendet.

Handelt es sich bei dem Betriebssystem auf dem Mini-Computer um eines von INTIA vorbereitetes sollte das Escape Game bereits installiert sein. War dies nicht der Fall wurde im schritt zuvor beschreiben wie man das Escape Game nach installiert.

<!--EndFragment-->
