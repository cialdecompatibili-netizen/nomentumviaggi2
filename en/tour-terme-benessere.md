---
layout: single
title: "Spa and wellness"
permalink: /en/tours/spa-and-wellness/
description: "Days at free hot springs and in spa villages, to relax."
ref: "cat-terme-benessere"
classes: wide
author_profile: false
lang: en
locale: en
tr: tradotto
tr_hash: 1w8tosx
---
<p class="nv-lead">Days at free hot springs and in spa villages, to relax.</p>

<div class="nv-grid">
{% assign items = site.tour | where: "cat", "terme-benessere" | where: "lang", page.lang | sort: "ordine" %}
{% for t in items %}{% include tour-card.html t=t %}{% endfor %}
</div>

<p class="nv-nota">Cannot find the right date or destination? <a href="{% include url-ref.html ref="contatti" %}">Write to us</a>: if there are enough requests we open a new departure. <a href="{% include url-ref.html ref="tour" %}">All categories</a>.</p>
