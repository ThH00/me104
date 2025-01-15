---
layout: page
title: Calendar (Honein)
nav_exclude: false 
# nav_order: 2
# parent: none
permalink: /calendar-honein/
description: Listing of course modules and topics.
---

# Calendar - Theresa Honein (Section 1 & 5)

{% for module in site.modules_honein %}
{{ module }}
{% endfor %}