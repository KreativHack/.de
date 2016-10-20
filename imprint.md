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

## Bilder

Panorama von Kiel: [Jan Petersen](https://www.flickr.com/photos/witz-und-verstand/8933096589)

Karte des Open Data Hackathons: © OpenStreetMap contributors
