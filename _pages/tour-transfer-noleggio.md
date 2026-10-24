---
layout: single
title: "Transfer e noleggio pullman"
permalink: /tour/transfer-noleggio/
description: "Transfer da Fiumicino e Ciampino e noleggio pullman con conducente da Mentana, per gruppi e turisti."
ref: "cat-transfer-noleggio"
classes: wide
author_profile: false
---
<p class="nv-lead">Transfer dagli aeroporti e noleggio di pullman con conducente, su preventivo.</p>

<div class="nv-grid">
{% assign items = site.tour | where: "cat", "transfer-noleggio" | where: "lang", page.lang | sort: "ordine" %}
{% for t in items %}{% include tour-card.html t=t %}{% endfor %}
</div>

<p class="nv-nota">Non trovi la data o la meta giusta? <a href="{% include url-ref.html ref="contatti" %}">Scrivici</a>: se ci sono abbastanza richieste apriamo una nuova partenza. <a href="{% include url-ref.html ref="tour" %}">Tutte le categorie</a>.</p>
