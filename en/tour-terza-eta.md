---
layout: single
title: "Trips for seniors"
permalink: /en/tours/trips-for-seniors/
description: "Slow pace, frequent stops and a tour leader: villages, lakes and spas."
ref: "cat-terza-eta"
classes: wide
author_profile: false
lang: en
locale: en
tr: tradotto
tr_hash: 1dcmw0y
---
<p class="nv-lead">Slow pace, frequent stops and a tour leader: villages, lakes and spas.</p>

<div class="nv-grid">
{% assign items = site.tour | where: "cat", "terza-eta" | where: "lang", page.lang | sort: "ordine" %}
{% for t in items %}{% include tour-card.html t=t %}{% endfor %}
</div>

<p class="nv-nota">Cannot find the right date or destination? <a href="{% include url-ref.html ref="contatti" %}">Write to us</a>: if there are enough requests we open a new departure. <a href="{% include url-ref.html ref="tour" %}">All categories</a>.</p>
