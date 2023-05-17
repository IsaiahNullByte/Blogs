---
title: "Download-And-Execute-Payload-Hidden-Inside-PNG-Image"
date: 2023-05-16
layout: default
author: Isaiah Miller
---

<small>{{ page.date | date: "%-d %B %Y" }}</small>
<h1>{{ page.title }}</h1>

<p class="view">by {{ page.author | default: site.author }}</p>

{{content}}

{% if page.tags %}
  <small>tags: <em>{{ page.tags | join: "</em> - <em>" }}</em></small>
{% endif %}
