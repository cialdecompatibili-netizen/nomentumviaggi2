---
layout: single
title: "Events, concerts and parties"
permalink: /en/tours/events-concerts-and-parties/
description: "Coaches for concerts and matches, birthday parties and stag and hen parties."
ref: "cat-eventi-concerti"
classes: wide
author_profile: false
lang: en
locale: en
tr: tradotto
tr_hash: w25ifx
---
<p class="nv-lead">Coaches for concerts and matches, birthday parties and stag and hen parties.</p>

<div class="nv-grid">
{% assign items = site.tour | where: "cat", "eventi-concerti" | where: "lang", page.lang | sort: "ordine" %}
{% for t in items %}{% include tour-card.html t=t %}{% endfor %}
</div>

<p class="nv-nota">Cannot find the right date or destination? <a href="{% include url-ref.html ref="contatti" %}">Write to us</a>: if there are enough requests we open a new departure. <a href="{% include url-ref.html ref="tour" %}">All categories</a>.</p>
