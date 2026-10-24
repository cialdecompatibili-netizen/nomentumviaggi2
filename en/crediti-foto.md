---
layout: single
title: "Photo credits"
permalink: /en/photo-credits/
description: "Authors and licences of the photographs used on the site, from Wikimedia Commons."
ref: crediti-foto
author_profile: false
sitemap: false
lang: en
locale: en
tr: tradotto
tr_hash: 1kqnwm9
---

The tour photographs are taken from Wikimedia Commons and used under the licences indicated.

{% for c in site.data.crediti %}- **{{ c[1].titolo }}**, {{ c[1].autore }}, licence {{ c[1].licenza }} ([source]({{ c[1].url }}))
{% endfor %}
