---
layout: page
title: The Team
permalink: /team/
---

{% include team_style.html %}
{% for team in site.teams %}
# {{ team }}
{% for project in site.categories.project %}
{% if project.title == team %}
{{ project.excerpt }}
{% endif %}
{% endfor %}
    {% include team.html team=team %}
{% endfor %}
