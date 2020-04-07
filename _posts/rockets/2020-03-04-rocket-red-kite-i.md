---
layout: post
title: Red Kite I
category: rocket
excerpt_separator: <!-- more -->
---

The seconds rocket launch! Dual deployment etc.

<!-- more -->

Our second rocket. Drogue and main deployed...

### Linked projects:
{% for project in site.categories.project %}
{% if page.tags contains project.title %}
[{{ project.title }}]({{ project.url }})
{% endif %}
{% endfor %}