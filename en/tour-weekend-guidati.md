---
layout: single
title: "Weekends and guided trips"
permalink: /en/tours/weekends-and-guided-trips/
description: "Two or three days with a guide, coach and hotel: Tuscia, Umbria, Naples, Ponza."
ref: "cat-weekend-guidati"
classes: wide
author_profile: false
lang: en
locale: en
tr: tradotto
tr_hash: 1s5tmwz
---
<p class="nv-lead">Two or three days with a guide, coach and hotel: Tuscia, Umbria, Naples, Ponza.</p>

<div class="nv-grid">
{% assign items = site.tour | where: "cat", "weekend-guidati" | where: "lang", page.lang | sort: "ordine" %}
{% for t in items %}{% include tour-card.html t=t %}{% endfor %}
</div>

<p class="nv-nota">Cannot find the right date or destination? <a href="{% include url-ref.html ref="contatti" %}">Write to us</a>: if there are enough requests we open a new departure. <a href="{% include url-ref.html ref="tour" %}">All categories</a>.</p>
