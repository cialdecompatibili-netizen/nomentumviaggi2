---
layout: single
title: "Pilgrimages and religious tourism"
permalink: /en/tours/pilgrimages-and-religious-tourism/
description: "Assisi, Cascia, Loreto: days and weekends with a guide and moments of prayer."
ref: "cat-pellegrinaggi"
classes: wide
author_profile: false
lang: en
locale: en
tr: tradotto
tr_hash: 1adh6o8
---
<p class="nv-lead">Assisi, Cascia, Loreto: days and weekends with a guide and moments of prayer.</p>

<div class="nv-grid">
{% assign items = site.tour | where: "cat", "pellegrinaggi" | where: "lang", page.lang | sort: "ordine" %}
{% for t in items %}{% include tour-card.html t=t %}{% endfor %}
</div>

<p class="nv-nota">Cannot find the right date or destination? <a href="{% include url-ref.html ref="contatti" %}">Write to us</a>: if there are enough requests we open a new departure. <a href="{% include url-ref.html ref="tour" %}">All categories</a>.</p>
