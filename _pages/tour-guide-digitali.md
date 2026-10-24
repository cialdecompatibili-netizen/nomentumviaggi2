---
layout: single
title: "Guide e itinerari digitali"
permalink: /tour/guide-digitali/
description: "Guide PDF e itinerari digitali con mappa per Roma e il Lazio, da usare in autonomia."
ref: "cat-guide-digitali"
classes: wide
author_profile: false
---
<p class="nv-lead">Itinerari con mappa da scaricare: Roma, borghi, laghi, mare e neve.</p>

<div class="nv-grid">
{% assign items = site.tour | where: "cat", "guide-digitali" | where: "lang", page.lang | sort: "ordine" %}
{% for t in items %}{% include tour-card.html t=t %}{% endfor %}
</div>

<p class="nv-nota">Non trovi la data o la meta giusta? <a href="{% include url-ref.html ref="contatti" %}">Scrivici</a>: se ci sono abbastanza richieste apriamo una nuova partenza. <a href="{% include url-ref.html ref="tour" %}">Tutte le categorie</a>.</p>
