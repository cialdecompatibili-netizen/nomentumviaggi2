---
layout: single
title: "Rome: guided walking tours"
permalink: /en/tours/rome-guided-walking-tours/
description: "Colosseum, Vatican, catacombs and neighbourhoods with a guide, in a small group."
ref: "cat-roma-tour-guidati"
classes: wide
author_profile: false
lang: en
locale: en
tr: tradotto
tr_hash: o9ouq1
---
<p class="nv-lead">Colosseum, Vatican, catacombs and neighbourhoods with a guide, in a small group.</p>

<div class="nv-grid">
{% assign items = site.tour | where: "cat", "roma-tour-guidati" | where: "lang", page.lang | sort: "ordine" %}
{% for t in items %}{% include tour-card.html t=t %}{% endfor %}
</div>

<p class="nv-nota">Cannot find the right date or destination? <a href="{% include url-ref.html ref="contatti" %}">Write to us</a>: if there are enough requests we open a new departure. <a href="{% include url-ref.html ref="tour" %}">All categories</a>.</p>
