---
layout: single
title: "Terme e benessere"
permalink: /tour/terme-benessere/
description: "Gite alle terme da Roma e Mentana: Saturnia, Viterbo e Fiuggi, con pullman e accompagnatore."
ref: "cat-terme-benessere"
classes: wide
author_profile: false
---
<p class="nv-lead">Giornate alle terme libere e nei borghi termali, per rilassarsi.</p>

<div class="nv-grid">
{% assign items = site.tour | where: "cat", "terme-benessere" | where: "lang", page.lang | sort: "ordine" %}
{% for t in items %}{% include tour-card.html t=t %}{% endfor %}
</div>

<p class="nv-nota">Non trovi la data o la meta giusta? <a href="{% include url-ref.html ref="contatti" %}">Scrivici</a>: se ci sono abbastanza richieste apriamo una nuova partenza. <a href="{% include url-ref.html ref="tour" %}">Tutte le categorie</a>.</p>
