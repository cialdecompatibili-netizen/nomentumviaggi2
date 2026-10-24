---
layout: single
title: "Gite guidate in giornata"
permalink: /tour/gite-guidate/
description: "Gite guidate di un giorno da Roma e Mentana in pullman con guida turistica: Pompei, Orvieto, Civita di Bagnoregio, Tivoli."
ref: "cat-gite-guidate"
classes: wide
author_profile: false
---
<p class="nv-lead">Un giorno in pullman con guida: Pompei, Orvieto, Tivoli, Castelli Romani, Tuscia.</p>

<div class="nv-grid">
{% assign items = site.tour | where: "cat", "gite-guidate" | where: "lang", page.lang | sort: "ordine" %}
{% for t in items %}{% include tour-card.html t=t %}{% endfor %}
</div>

<p class="nv-nota">Non trovi la data o la meta giusta? <a href="{% include url-ref.html ref="contatti" %}">Scrivici</a>: se ci sono abbastanza richieste apriamo una nuova partenza. <a href="{% include url-ref.html ref="tour" %}">Tutte le categorie</a>.</p>
