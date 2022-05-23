---
hero_tags: subpage pdf
title_above: Anleitungen
breadcrumbs: [Wissen, Anleitungen]
title: Anleitung zum Hinzufügen und Einrichten neuer Geräte
permalink: /wissen/anleitungen/neue-geraete
subtitle:
---

<!--StartFragment-->

Das von uns genutzte System nutzt überwiegend Smart Home Geräte, welche das sogenannte ZigBee-Protokoll nutzen. Das hat den Vorteil, dass aus einer Vielzahl von Geräten mit unterschiedlichsten Aufgaben gewählt werden kann. Der Nachteil ist, dass wir keine Out of The Box-Lösung anbieten können und ein paar Schritte nötig sind, um die Geräte hinzuzufügen.

## Vorbereitung

Das benötigst du:

- Stelle sicher, dass du dich mit dem Mini-Computer über das WLAN verbinden kannst.
- Überprüfe zuvor, ob das neue Gerät wirklich ZigBee geeignet ist. Der einfachste Weg hierfür ist zu schauen, ob das Zigbee-Logo auf der Verpackung abgedruckt ist.
- Siehe nach, wie man das Gerät verbindet:
  - (Sieh auf die Geräte-Liste auf unserer Plattform - jedes von uns getestetes Gerät haben wir dort aufgelistet) - noch nicht auf der Plattform!
  - Schaue in die Anleitung des Gerätes (leider steht dies nicht immer dort)
  - Schaue auf die Liste der Unterstützten Geräte von Zigbee2MQTT (EN!)
- Die Geräte immer nur nacheinander zu Zigbee2MQTT hinzufügen: Also ein Gerät nach dem anderen.
- Wenn möglich, kontrolliere den Ladestatus der beigelegten Batterien. Es ist bereits vorgekommen, dass die beigelegten Batterien leer waren.
- Du musst etwas Geduld mitbringen. Es sollte zwar nichts schief gehen, aber das kann dennoch immer mal wieder passieren. Die neuen Geräte daher am besten nicht hektisch kurz vor dem ersten Einsatz hinzufügen. Nimm dir Zeit für das Hinzufügen und Einrichten neuer Geräte.

## Anlernen Aktivieren

<figure>
  <img src="/assets/img/instructions/z2m_add_new_1.png" alt="Zettel mit technischen Begriffen liegen auf einem Tisch. Dort steht auch ein Bügeleisen." style="height:450px;">
</figure>

- Öffne die Zigbee2MQTT-Seite auf dem Mini-Computer mit folgender Seite:
  - http://intia:8080
  - Alternativ: http://192.168.4.100:8080
  - Alternativ: Wenn der Mini-Computer ein Display hat, steht dort die Adresse. Diese in die Browser mit dem Zusatz :8080 eingeben.
- Beachte, dass auf Mobilgeräten das Verbinden zu einem Netzwerk ohne Internet zu Problemen führen kann.
- Oben rechts auf "Anlernen aktivieren (Alle)” klicken.
- Nach dem Anklicken etwas mehr als vier Minuten verbleiben, um das neue Gerät hinzuzufügen.

<div class="columns is-centered is-desktop">
<div class="column is-offset-1">
<figure>
  <img src="/assets/img/instructions/z2m_add_new_2.png" alt="Zettel mit technischen Begriffen liegen auf einem Tisch. Dort steht auch ein Bügeleisen." style="height:250px;">
</figure>
</div>
<div class="column">
<figure>
  <img src="/assets/img/instructions/z2m_add_new_3.png" alt="Zettel mit technischen Begriffen liegen auf einem Tisch. Dort steht auch ein Bügeleisen." style="height:250px;">
</figure>
</div>
</div>

## Gerät Hinzufügen

- Behalte die rechte, untere Ecke der Oberfläche, auf der du gerade das Anlernen gestartet hast, im Blick.
- Bringe das neue Gerät in die Nähe des Mini-Computers.
- Wenn noch nicht geschehen: Setze die Batterie ein und warte 5-10 Sekunden.
  - Sollte auf der Webseite etwas unten rechts aufspringen, kann das bedeuten, dass der Anlernprozess bereits startet. Ist das der Fall, solltest du lieber warten. Das Zurücksetzen oder Koppeln des Gerätes ist eventuell nicht mehr notwendig.
- Starte den Kopplung-Modus an dem neuen Gerät bzw. führe ein Zurücksetzen an diesem durch.
  - Bei IKEA ist das meist ein sechsmaliges An- und Ausschalten.
  - Oft befindet sich ein entsprechender Knopf versteckt, teils unter der Batterie-Klappe, der für eine Weile (10 bis 25 Sekunden) gedrückt gehalten werden muss, bis eine LED blinkt.
- Das Gerät sollte jetzt in Ruhe mit dem Mini-Computer zurückgelassen werden.
- Wenn der Anlernprozess erfolgreich war, erscheint das Gerät in der Geräte-Liste mit einem kryptischen Gerätenamen.
  - Bei Schaltern und Knöpfen kann es helfen, ab und an die Taste zu betätigen (aber Achtung, nicht die Reset-Taste!).
  - Sollte das Gerät nicht erfolgreich hinzugefügt worden sein, lohnt es sich, einen Neustart durchzuführen.
  - Ist ein Gerät in der Liste, wurde allerdings nicht erkannt und ist mit einem Fehler versehen, musst du das Gerät entfernen. Das kannst du mit der Option "Erzwinge Entfernen" tun.
- Nicht vergessen: Das neue Gerät sollte einen "sprechenden" Namen bekommen, also einen Namen, der auf die Funktion hinweist. Dazu rechts auf den blauen Button "Umbenennen" gehen. Es ist empfehlenswert, einen Namen zu wählen, der die Funktion und den Einsatzzweck beschreibt. Weitere eindeutige Indikatoren wie Hersteller (sollte nur ein Gerät dieses Typen vom Hersteller vorliegen) können ebenfalls sinnvoll sein.
- Mit einem Click auf das Gerät oder unter dem Reiter Dashboard, kann das neue Gerät nun getestet werden. Dort können Lampen bedient werden und von Sensoren wie Tür-Kontakte oder Temperatur-Sensoren der Status abgelesen werden, also die gemessene Temperatur oder ob die Tür geschlossen oder geöffnet ist.

## Gerät nutzen

Die nachfolgenden Hinweise setzen voraus, dass bereits ein tieferes Verständnis von dem Umgang mit der Technik besteht. Zwar können diese Punkte auch von Einsteigern umgesetzt werden, allerdings werden die genutzten Technologien an dieser Stelle nicht näher erläutert.

- Das Gerät ist jetzt in NodeRed bei den Zigbee2MQTT-Nodes zu finden oder per MQTT selbst:
  - In NodeRed muss im z2m-Node aktualisiert werden. Bei Buttons oder anderen Geräten muss dabei manchmal auch das Gerät ein oder zwei Mal ausgelöst werden (beispielsweise indem eine Lampe an und aus gemacht wird oder ein Tür-Kontakt geöffnet und geschlossen wird), um alle Funktionen verfügbar zu machen.
  - Das Gerät ist über das MQTT-Topic "zigbee2mqtt/<Geräte-Name>" erreichbar. Möchte man beispielsweise eine Glühbirne über MQTT schalten, kann an das Topic "zigbee2mqtt/<Geräte-Name>/set" die Nachricht "TOGGLE" gesendet werden.
- Manche Geräte können über Zigbee2MQTT geupdatet werden. Hierfür bitte die Update-Kurzanleitung beachten.
- Ein schneller Implementierungs-Test mittels NodeRed und einem weiteren Gerät kann sinnvoll sein.
  - Handelt es sich bei dem neuen Gerät um eine Glühbirne, kann diese mittels eines Schalters oder Türkontaktes via TOGGLE oder ON/OFF eingebunden werden.
  - Handelt es sich um ein anderes Gerät, kann dieses ebenfalls eine Glühbirne ansprechen. Neben dem Anschalten von Glühbirnen ist ein Farbwechsel oder ein ALERT ebenfalls eine gute Testmethode.
- Optional, aber zu empfehlen: Gerät im NodeRed-Dashboard einbinden:
  - Einmal mit einer Textbox, um dessen Signale zu observieren.
  - Ist es steuerbar, dann mit Buttons und Switches.
  <!--EndFragment-->
