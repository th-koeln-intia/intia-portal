---
title: Methoden
title_above: Werkzeuge
permalink: /tools/methods/
hero_tags: toppage
subtitle: |
  Eine Übersicht von Methoden die Hilfreich zum entwerfen, erstellen und evaluieren von Alltagshilfen sind.
---

<!--
# Das Methodenradar

Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.

<a href='#' class='button is-dark is-rounded'>
      <span>Zur Methodenliste</span>
      <span class='icon is-small'>
        <i class='fas fa-chevron-right fa-xs'></i>
      </span>
</a>

<a href='#' class='button is-dark is-rounded'>
      <span>Mehr zum Radar</span>
      <span class='icon is-small'>
        <i class='fas fa-chevron-right fa-xs'></i>
      </span>
</a>

# Das Methodenradar benutzen

Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.

<div id="radar"></div>

-->

# Methodenliste

{% assign entries=site.methods | sort:page.sort %}
{% for entry in entries %}

<h2> {{entry.title}} </h2>
<p class="text-green has-text-weight-bold">{{entry.subtitle}}</p>

{{entry.abstract}}

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
