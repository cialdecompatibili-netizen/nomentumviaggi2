---
layout: single
title: "Food tour e corsi di cucina"
permalink: /tour/food-cucina/
description: "Food tour e corsi di cucina a Roma: mercato di Testaccio, pasta fatta a mano e birra artigianale con guida locale."
ref: "cat-food-cucina"
classes: wide
author_profile: false
---
<p class="nv-lead">Street food, mercati, birra artigianale e pasta fatta a mano a Roma.</p>

<div class="nv-grid">
{% assign items = site.tour | where: "cat", "food-cucina" | where: "lang", page.lang | sort: "ordine" %}
{% for t in items %}{% include tour-card.html t=t %}{% endfor %}
</div>

<p class="nv-nota">Non trovi la data o la meta giusta? <a href="{% include url-ref.html ref="contatti" %}">Scrivici</a>: se ci sono abbastanza richieste apriamo una nuova partenza. <a href="{% include url-ref.html ref="tour" %}">Tutte le categorie</a>.</p>
