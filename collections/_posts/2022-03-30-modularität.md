---
hero_tags: subpage post pdf
title_above: AKTUELLES
published: true
title: Modularität
author: Dennis Christian Wilk
hero_image: /assets/img/uploads/neuigkeit_modularität_platzhalterbild.jpg
preview_image: /assets/img/uploads/neuigkeit_modularität_platzhalterbild.jpg
subtitle: Warum sind Fertiglösungen doch oft der DiY-Hardware überlegen? Was hat
  es mit “dummen” Hardware-Elementen auf sich? Und was hat das mit Modularität
  zu tun?
---
<!--StartFragment-->

Personen und ihre Probleme sind vielseitig. Somit auch die Bedarfe und mögliche Lösungsansätze. Es ist somit unwahrscheinlich, dass ein Koffer alleine für einen Großteil aller Einsatzbereiche gerüstet und zeitgleich ideal gepackt ist. Warum sollte dennoch eine sparsame Ausstattung angestrebt werden? Zum einen sollte der Preis nicht künstlich hochgetrieben werden. Zum anderen wirkt ein großer Umfang entgegen der Zugänglichkeit. Es ist somit sinnvoll, wenige Kern-Inhalte anzustreben und den Fokus auf eine einfache und schnelle Erweiterbarkeit zu legen. Aus diesem Grund ist die Modularisierung ein Kernaspekt der Bausteine des INTIA-Koffers. 

Aktuell wird dies über zwei Hauptsäulen erreicht: Fertiglösungen vor DiY-Hardware und “dumme” Hardware-Elemente. Die genauere Bedeutung wird im Folgenden aufgeschlüsselt. 

**Fertiglösungen vor DiY-Hardware** 

Diese Säule der Modularisierbarkeit ist schnell erläutert. Eine Selbstentwicklung bedeutet Zeit und Aufwand. Auch wenn DiY oft günstiger erscheint, wird die Aufbauzeit und das benötigte Know-How sowie zusätzliche Werkzeuge oft nicht mit eingerechnet. Zwar lässt sich ein Temperatursensor für unter 5€ bauen, dafür werden aber Kabel und Lötkolben benötigt - und dann besitzt die Eigenentwicklung noch kein Gehäuse und ist kabelgebunden.  

Für 10-15€ ist eine Fertiglösung in jeglicher Hinsicht überlegen: Ansprechendes Design, kabellos, zuverlässig und schnell eingebunden. Dank dieser Charakteristika ist es auch für Nicht-Techniker:innen möglich, die Bausteine des INTIA-Koffers zu erweitern. Es spricht also einiges für Fertiglösungen, statt aufwendig DiY-Hardware zu basten.  



**“Dumme” Hardware-Elemente** 

Im Kontext des Smart-Homes wird oft von smarter, also kluger Hardware geredet. Dies ist aber eine Bezeichnung, die oft zu Fehlschlüssen führt. Die “kluge Glühbirne” besitzt keine Intelligenz. Man kann mit ihr alleine nicht mal einen Wecker oder Schalt-Zeiten einstellen. Smart-Hardware kann Befehle ausführen. Dafür braucht es aber eine Art Steuerung. Das Smarte am Smart-Home ist also die Schaltzentrale, das Gateway, der Computer im Zentrum. Etwas, was alle Geräte steuert und koordiniert.  

Dieses Konzept wird im Koffer adaptiert. Alle Geräte werden möglichst funktionsarm konzipiert bzw. eingebunden. Somit verhalten sich die Elemente im Koffer wie Arme und Beine – und der Mini-Computer ist das Gehirn. Diese Konzeption ermöglicht einen leichten Austausch. Mit wenigen Schritten kann eine Glühbirne durch ein Display getauscht oder ein weiterer Button dazwischengeschaltet werden. Dies fördert auch die Selbst-Entwicklung von Geräten. Auch wenn Fertiglösungen bevorzugt werden, ist es manchmal notwendig, ein DiY-Element zu erstellen und einzubinden. Ein Beispiel hierfür sind Sensoren, die Auskunft über Pflanzen und Erde geben. Das zu bauende Element muss nur einfachste Informationen versenden. Der Sensor weiß nicht, ob die Pflanze Wasser braucht. Die Verarbeitung dieser Informationen wird komplett vom zentralen Mini-Computer übernommen. 



**Limitationen** 

Zum einen sollten alle Fertig-Lösungen das Zigbee-Protokoll beherrschen. Dabei sollte darauf geachtet werden, dass sich die Geräte auf der Kompatibilitätsseite von Zigbee2MQTT befinden. <https://www.zigbee2mqtt.io/supported-devices/> Sollte dies nicht der Fall sein, ist es aber sehr wahrscheinlich, dass eine Kompatibilität bald hinzugefügt wird - dieses Projekt ist sehr lebendig und hoch aktiv. Zum anderen müssen alle DiY-Lösungen mittels MQTT kommunizieren. 



**How-To-Anleitungen** 

Diese sehr einfachen, klaren Prinzipien müssen auch für wenig Technik-affine Menschen “operationalisierbar” gemacht werden - sprich: In einfachen Worten müssen folgende Fragen erklärt werden: 

* Wie entscheide ich, ob sich eine neue Komponente (irgendwas Neues von IKEA o.ä.) als Modul eignet? 
* Wenn es sich eignet: Wie binde ich das neue Modul ein? 

**Fazit zur Modularisierung** 

Zusammenfassend kann gesagt werden, dass der modulare Charakter der Bausteine des INTIA-Koffers es einfach macht für Nicht-Techniker:innen, weitere Elemente hinzuzufügen. Außerdem könnenMaker:innen schnell neue Elemente einbinden, die sie selbst entwickelt haben, wenn bestimmte Faktoren beachtet werden. 

Dadurch, dass sich die “Intelligenz” in dem zentralen Mini-Computers befindet, ist eine Erweiterung sehr einfach. 

Allerdings müssen dabei die genannten Limitationen bedacht werden. 

<!--EndFragment-->