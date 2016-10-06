---
layout: page
navigation_title: Impressum
title: Impressum
permalink: /imprint/
---

Der KreativHack wird organisiert von:

{% for organizer in site.data.organisers %}
# [{{ organizer.name }}]({{ organizer.url }})

> {{ organizer.address }}
{% endfor %}
