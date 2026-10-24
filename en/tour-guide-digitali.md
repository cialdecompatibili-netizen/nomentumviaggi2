---
layout: single
title: "Digital guides and itineraries"
permalink: /en/tours/digital-guides-and-itineraries/
description: "Itineraries with a downloadable map: Rome, villages, lakes, sea and snow."
ref: "cat-guide-digitali"
classes: wide
author_profile: false
lang: en
locale: en
tr: tradotto
tr_hash: 1w4gst5
---
<p class="nv-lead">Itineraries with a downloadable map: Rome, villages, lakes, sea and snow.</p>

<div class="nv-grid">
{% assign items = site.tour | where: "cat", "guide-digitali" | where: "lang", page.lang | sort: "ordine" %}
{% for t in items %}{% include tour-card.html t=t %}{% endfor %}
</div>

<p class="nv-nota">Cannot find the right date or destination? <a href="{% include url-ref.html ref="contatti" %}">Write to us</a>: if there are enough requests we open a new departure. <a href="{% include url-ref.html ref="tour" %}">All categories</a>.</p>
