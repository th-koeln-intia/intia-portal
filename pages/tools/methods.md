---
title: Methoden
title_above: Werkzeuge
permalink: /werkzeuge/methoden/
hero_tags: toppage
subtitle: |
  Hier sind Methoden aufgeführt, die zum Entwerfen, Erstellen und Evaluieren von Alltagshilfen nützlich sind.
jekyll-hyperlink-glossary: false
---

# Das Methodenradar

Um produktiv mit Methoden zu arbeiten ist es wichtig, sie systematisch zu kategorisieren. Eine häufig werden Methoden nach ihrem Zweck sortiert. Hierzu lassen sich z.B. die Phasen in einem Prozess nutzen.
Neben dieser gängigen Praxis kann man für partizipativ inklusive Technikentwicklung die Frage stellen: "Wie partizipativ sind die Methoden?" Eine solche Einordnung kann man mithilfe des Stufenmodells der Partizipation abbilden. Dieses Modell besteht (je nach Autor:in) aus sieben Stufen, die unterschiedliche Grade von Partizipation beschreiben.
Das INTIA-Methodenradar strukturiert Methoden nach eben diesen Stufen der Partizipation. Dabei stellt jeder Ring eine Stufe dar, von der "Nicht-beteiligung" bis zur "vollständigen Entscheidungsmacht". Zusätzlich dazu ist das Radar in vier Sektoren unterteilt, die verschiedene Domänen abbilden, von Methoden die bei der Entdeckung einer Domäne helfen, über solche die eben diese Domäne definieren, bis hin zur Entwicklung von Produkten und deren Evaluation.
Eine detailierte Erklärung zur Entstehung und Struktur des INTIA-Methodenradars folgt noch.

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

Im untenstehenden INTIA-Methodenradar ist eine Übersicht von Methoden zum Entwerfen, Erstellen und Evaluieren von Alltagshilfen. Jeder Punkt im Radar stellt hier eine Methode dar und führt zu ihrer Detailbeschreibung. Mithilfe der Menüpunkte über dem Radar können einzelne Quadranten fokusiert werden.
Die Bedeutung der einzelnen Ringe ist der untenstehenden Legende zu entnehmen.

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
