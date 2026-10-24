---
layout: single
title: "Food tours and cooking classes"
permalink: /en/tours/food-tours-and-cooking-classes/
description: "Street food, markets, craft beer and handmade pasta in Rome."
ref: "cat-food-cucina"
classes: wide
author_profile: false
lang: en
locale: en
tr: tradotto
tr_hash: 17jaxqh
---
<p class="nv-lead">Street food, markets, craft beer and handmade pasta in Rome.</p>

<div class="nv-grid">
{% assign items = site.tour | where: "cat", "food-cucina" | where: "lang", page.lang | sort: "ordine" %}
{% for t in items %}{% include tour-card.html t=t %}{% endfor %}
</div>

<p class="nv-nota">Cannot find the right date or destination? <a href="{% include url-ref.html ref="contatti" %}">Write to us</a>: if there are enough requests we open a new departure. <a href="{% include url-ref.html ref="tour" %}">All categories</a>.</p>
