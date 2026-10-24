---
layout: single
title: "Snow and winter"
permalink: /en/tours/snow-and-winter/
description: "Days and weekends in the snow with a tour leader: Livata, Terminillo, Abruzzo."
ref: "cat-neve-inverno"
classes: wide
author_profile: false
lang: en
locale: en
tr: tradotto
tr_hash: 1h6b5l
---
<p class="nv-lead">Days and weekends in the snow with a tour leader: Livata, Terminillo, Abruzzo.</p>

<div class="nv-grid">
{% assign items = site.tour | where: "cat", "neve-inverno" | where: "lang", page.lang | sort: "ordine" %}
{% for t in items %}{% include tour-card.html t=t %}{% endfor %}
</div>

<p class="nv-nota">Cannot find the right date or destination? <a href="{% include url-ref.html ref="contatti" %}">Write to us</a>: if there are enough requests we open a new departure. <a href="{% include url-ref.html ref="tour" %}">All categories</a>.</p>
