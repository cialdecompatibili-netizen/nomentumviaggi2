---
layout: single
title: "Weekend e viaggi guidati"
permalink: /tour/weekend-guidati/
description: "Weekend e viaggi guidati da Roma e Mentana: pullman, hotel e guida turistica per 2 o 3 giorni in Tuscia, Umbria, Campania e Ponza."
ref: "cat-weekend-guidati"
classes: wide
author_profile: false
---
<p class="nv-lead">Due o tre giorni con guida, pullman e hotel: Tuscia, Umbria, Napoli, Ponza.</p>

<div class="nv-grid">
{% assign items = site.tour | where: "cat", "weekend-guidati" | where: "lang", page.lang | sort: "ordine" %}
{% for t in items %}{% include tour-card.html t=t %}{% endfor %}
</div>

<p class="nv-nota">Non trovi la data o la meta giusta? <a href="{% include url-ref.html ref="contatti" %}">Scrivici</a>: se ci sono abbastanza richieste apriamo una nuova partenza. <a href="{% include url-ref.html ref="tour" %}">Tutte le categorie</a>.</p>
