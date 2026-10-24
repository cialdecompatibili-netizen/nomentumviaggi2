---
layout: single
title: "Groups, schools and companies"
permalink: /en/tours/groups-schools-and-companies/
description: "School trips, team building and outings for clubs and associations, on quote."
ref: "cat-gruppi-scuole-aziende"
classes: wide
author_profile: false
lang: en
locale: en
tr: tradotto
tr_hash: zf2i5z
---
<p class="nv-lead">School trips, team building and outings for clubs and associations, on quote.</p>

<div class="nv-grid">
{% assign items = site.tour | where: "cat", "gruppi-scuole-aziende" | where: "lang", page.lang | sort: "ordine" %}
{% for t in items %}{% include tour-card.html t=t %}{% endfor %}
</div>

<p class="nv-nota">Cannot find the right date or destination? <a href="{% include url-ref.html ref="contatti" %}">Write to us</a>: if there are enough requests we open a new departure. <a href="{% include url-ref.html ref="tour" %}">All categories</a>.</p>
