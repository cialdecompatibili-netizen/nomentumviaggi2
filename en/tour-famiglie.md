---
layout: single
title: "Families and children"
permalink: /en/tours/families-and-children/
description: "Child-friendly tours: games, treasure hunts and a relaxed pace."
ref: "cat-famiglie"
classes: wide
author_profile: false
lang: en
locale: en
tr: tradotto
tr_hash: rgcrh1
---
<p class="nv-lead">Child-friendly tours: games, treasure hunts and a relaxed pace.</p>

<div class="nv-grid">
{% assign items = site.tour | where: "cat", "famiglie" | where: "lang", page.lang | sort: "ordine" %}
{% for t in items %}{% include tour-card.html t=t %}{% endfor %}
</div>

<p class="nv-nota">Cannot find the right date or destination? <a href="{% include url-ref.html ref="contatti" %}">Write to us</a>: if there are enough requests we open a new departure. <a href="{% include url-ref.html ref="tour" %}">All categories</a>.</p>
