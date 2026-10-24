---
layout: single
title: "Neve e inverno"
permalink: /tour/neve-inverno/
description: "Gite sulla neve da Roma e Mentana: Monte Livata, Terminillo, Campo Felice e Roccaraso, con pullman e accompagnatore."
ref: "cat-neve-inverno"
classes: wide
author_profile: false
---
<p class="nv-lead">Giornate e weekend sulla neve con accompagnatore: Livata, Terminillo, Abruzzo.</p>

<div class="nv-grid">
{% assign items = site.tour | where: "cat", "neve-inverno" | where: "lang", page.lang | sort: "ordine" %}
{% for t in items %}{% include tour-card.html t=t %}{% endfor %}
</div>

<p class="nv-nota">Non trovi la data o la meta giusta? <a href="{% include url-ref.html ref="contatti" %}">Scrivici</a>: se ci sono abbastanza richieste apriamo una nuova partenza. <a href="{% include url-ref.html ref="tour" %}">Tutte le categorie</a>.</p>
