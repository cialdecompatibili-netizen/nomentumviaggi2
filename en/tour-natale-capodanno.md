---
layout: single
title: "Christmas, markets and festivities"
permalink: /en/tours/christmas-markets-and-festivities/
description: "Christmas markets, lights and nativity scenes by coach, as a day trip or a weekend."
ref: "cat-natale-capodanno"
classes: wide
author_profile: false
lang: en
locale: en
tr: tradotto
tr_hash: 16k3ccd
---
<p class="nv-lead">Christmas markets, lights and nativity scenes by coach, as a day trip or a weekend.</p>

<div class="nv-grid">
{% assign items = site.tour | where: "cat", "natale-capodanno" | where: "lang", page.lang | sort: "ordine" %}
{% for t in items %}{% include tour-card.html t=t %}{% endfor %}
</div>

<p class="nv-nota">Cannot find the right date or destination? <a href="{% include url-ref.html ref="contatti" %}">Write to us</a>: if there are enough requests we open a new departure. <a href="{% include url-ref.html ref="tour" %}">All categories</a>.</p>
