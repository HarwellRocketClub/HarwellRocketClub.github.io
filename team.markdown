---
layout: page
title: The Team
permalink: /team/
---

{% include team_style.html %}
{% for team in site.teams %}
# {{ team }}
    {% include team.html team=team %}
{% endfor %}
