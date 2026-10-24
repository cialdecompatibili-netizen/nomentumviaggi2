---
layout: single
title: "Natale, mercatini e feste"
permalink: /tour/natale-capodanno/
description: "Mercatini di Natale in pullman da Roma e Mentana: Bolzano, Trento, Abruzzo e borghi del Lazio, in giornata o weekend."
ref: "cat-natale-capodanno"
classes: wide
author_profile: false
---
<p class="nv-lead">Mercatini di Natale, luminarie e presepi in pullman, in giornata o in weekend.</p>

<div class="nv-grid">
{% assign items = site.tour | where: "cat", "natale-capodanno" | where: "lang", page.lang | sort: "ordine" %}
{% for t in items %}{% include tour-card.html t=t %}{% endfor %}
</div>

<p class="nv-nota">Non trovi la data o la meta giusta? <a href="{% include url-ref.html ref="contatti" %}">Scrivici</a>: se ci sono abbastanza richieste apriamo una nuova partenza. <a href="{% include url-ref.html ref="tour" %}">Tutte le categorie</a>.</p>
