---
hero_tags: subpage pdf
title_above: Anleitungen
breadcrumbs: [Wissen, Anleitungen]
title: Anleitung Mini-Computer installieren
permalink: /wissen/anleitungen/installation
hero_image: /assets/img/uploads/dsc_0060.jpg
preview_image: /assets/img/uploads/dsc_0060.jpg
subtitle: Bevor es mit der Erstinbetriebnahme des INTIA-Koffers losgehen kann, muss der Mini-Computer installiert werden. Dazu findest du hier die Anleitung.
---

<!--StartFragment-->

## Vorbereitung 

Benötigt wird

- Raspberry als Mini-Computer
- optional Raspberry Case
- optional OLED-Display für den Raspberry (AZDelivery 0,96 Zoll OLED Display I2C SSD1306 Chip 128 x 64 oder größer) - Jumper-Kabel werden empfohlen Weiblich-Weiblich
- Micro SD-Karte (mindestens 16GB; 32GB oder mehr wird empfohlen, da hiermit ein Sprachassistenten-Upgrade einfacher wird)
- Netzteil für Raspberry

## Installation 

Das Betriebssystem wird auf den Raspberry geschrieben. Hier muss nicht viel beachtet werden. Mit einem kleinen Programm wird eine Datei auf die SD-Karte geschrieben. NICHT die Datei auf die SD-Karte kopieren, das funktioniert nicht. In dem Prozess wird die SD-Karte formatiert (alle Daten auf der SD-Karte werden gelöscht). Also bitte beachten, dass nichts auf der SD-Karte ist, was wichtig ist!

- SD-Karten Image herunterladen (link!)
- SD-Karte in einen Computer geben
- Unter Windows die Software Etcher installieren und ausführen: <https://www.balena.io/etcher/>
  ![](https://wiki.th-koeln.de/download/attachments/27691881/image2022-1-14_13-44-25.png?version=1&modificationDate=1642418237042&api=v2)
- Select Image - Die IMG-Datei auswählen, die zuvor von uns heruntergeladen wurde
- Select drive - Die SD-Karte auswählen
- Flash!
- Warten, bis es fertig ist
- SD-Karte in den Raspberry

## Optional aber empfohlen: Case und Display zusammensetzen 

Der Mini-Computer läuft auch ohne Display und Gehäuse, also einer Plastikschale, die das Gerät schützt. Dennoch ist es empfehlenswert, das Gerät mit einem Case, einem Gehäuse oder einer Schale zu schützen. Das Gerät ist aber sehr stabil und daher das Risiko gering, das etwas kaputt geht, wenn kein Gehäuse drum ist. Wenn es also passiert, dass der Raspberry bereits da ist aber noch kein Case fertig ist, kann man ohne Sorge bereits die Installation durchführen und jeder Zeit die nachfolgenden Schritte nachholen.

- Display anschließen wie auf dem Bild mit Jumper-Kabel
  ![](https://m.media-amazon.com/images/I/611iVBH-XFS._SL1500_.jpg)
- Wenn im Case keine Lücke ist für das Display vorhanden ist, kann dieses nach Belieben raus gelöst werden (keine Angst!) - Unsere 3D-Druck-Case-Vorlage hat Lücken (Datei muss noch erstellt und hochgeladen werden!!!!)
- Display an dem Case befestigen
- Raspberry in Case geben
- Zusammenstecken und zu machen
- Fertig

Jetzt kann es mit der Erstinbetriebnahme weitergehen.

<!--EndFragment-->
