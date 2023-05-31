---
title: Methoden
title_above: Werkzeuge
permalink: /werkzeuge/methoden/
hero_tags: toppage
subtitle: |
    Hier finden sich Methoden und ein Methodenradar. Die Methoden können dabei unterstützen, technische Alltagshilfen zu entwerfen, umzusetzen und zu beurteilen. Das Methodenradar erleichtert die Auswahl. Es zeigt, wann eine Methode sinnvoll in einem Entwicklungsprozess eingesetzt werden kann und wie partizipativ sie ist.
jekyll-hyperlink-glossary: false
---

# Das Methodenradar

Wer sinnvoll mit Methoden arbeiten möchte, muss sie kennen und wissen, wie und wofür man sie benutzt. Man kann die Methoden nach ihrem Ziel sortieren (zum Beispiel nach Phasen, die in bestimmten Prozessen durchlaufen werden). Neben dieser weit verbreiteten Vorgehensweise könnte man bei der partizipativ inklusiven Technikentwicklung auch nach Partizipationsmöglichkeiten sortieren: Wie ausgeprägt ist die Zusammenarbeit zwischen denjenigen, die die Technik entwickeln und denen, die sie nutzen? Um das zu beurteilen, gibt es das „Stufenmodell der Partizipation“. Es beschreibt (je nach Autor:in) in sieben Stufen, wie gut diejenigen, die es betrifft, beteiligt werden können.

Das INTIA Methodenradar sortiert Methoden nach diesem Stufenmodell, also danach, wie stark die Beteiligung ist. Jeder Ring ist dabei eine Stufe, angefangen von „nicht beteiligt“ bis zur „vollständigen Entscheidungsmacht“. Außerdem ist das Radar in vier Bereiche (Sektoren) aufgeteilt, in die die verschiedenen Methoden eingeordnet sind. So zum Beispiel Methoden, die dabei helfen, eine Domäne zu entdecken oder Methoden, die diese Domäne definieren. Auch Methoden, die dabei helfen, Produkte zu entwickeln und zu beurteilen, sind im Methodenradar zu finden.

<a href='#methodenliste' class='button is-dark is-rounded'>
      <span>Zur Methodenliste</span>
      <span class='icon is-small'>
        <i class='fas fa-chevron-right fa-xs'></i>
      </span>
</a>
<!--
<a href='#' class='button is-dark is-rounded'>
      <span>Mehr zum Radar</span>
      <span class='icon is-small'>
        <i class='fas fa-chevron-right fa-xs'></i>
      </span>
</a>
-->

# Das Methodenradar benutzen

Im INTIA-Methodenradar gibt es eine Übersicht über verschiedene Methoden, die dabei unterstützen können, Alltagshilfen zu entwerfen, umzusetzen und zu beurteilen. Jeder Punkt im Radar steht für eine bestimmte Methode und führt zu einer genaueren Erklärung. Über dem Radar sind Menüpunkte zu sehen, mit denen man einzelne Teile des Radars genauer anschauen kann. Die Bedeutung der einzelnen Ringe im Radar kann in der Legende unten nachgelesen werden.
<br>
<br>
Die dunklen Punkte im Radar befinden sich bereits auf der Plattform mit einer Detailbeschreibung und sind ebenfalls der untenstehenden Liste zu entnehmen. Die helleren Punkte dagegen befinden sich noch nicht auf der Plattform und folgen später noch.

<div id="radar"></div>

# Methodenliste

{% assign entries=site.methods | sort:page.sort %}
{% for entry in entries %}

<h2 class="has-text-left"> {{entry.title}} </h2>
{{entry.subtitle}}

<a href="{{ entry.url | relative_url }}" class="button float_right is-rounded has-text-centert is-dark {% if item.link == page.url %}is-active{% endif %}">
    <span> Mehr lesen</span>
    <span class="icon is-small">
    <i class="fas fa-chevron-right fa-xs"></i>
    </span>
</a>

{% endfor %}

<script>
let config = {{ site.data.radar-config | jsonify }};
let structure = {{ site.data.radar-structure | jsonify }};
let entries = {{ site.data.radar-entries | jsonify }}; 
createRadar(config, structure, entries);
</script>
