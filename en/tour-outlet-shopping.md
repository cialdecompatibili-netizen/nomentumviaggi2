---
layout: single
title: "Outlets and shopping"
permalink: /en/tours/outlets-and-shopping/
description: "Coaches to the outlets near Rome, with no parking worries."
ref: "cat-outlet-shopping"
classes: wide
author_profile: false
lang: en
locale: en
tr: tradotto
tr_hash: 19h2x4p
---
<p class="nv-lead">Coaches to the outlets near Rome, with no parking worries.</p>

<div class="nv-grid">
{% assign items = site.tour | where: "cat", "outlet-shopping" | where: "lang", page.lang | sort: "ordine" %}
{% for t in items %}{% include tour-card.html t=t %}{% endfor %}
</div>

<p class="nv-nota">Cannot find the right date or destination? <a href="{% include url-ref.html ref="contatti" %}">Write to us</a>: if there are enough requests we open a new departure. <a href="{% include url-ref.html ref="tour" %}">All categories</a>.</p>
