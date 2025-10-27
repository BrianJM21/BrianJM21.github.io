---
layout: page
permalink: /repositories/
title: Repositorios
description: En esta sección encontrarás una referencia directa a mi cuenta de GitHub así como a los repositorios de los proyectos que conforman mi portafolio de aplicaciones.
nav: true
nav_order: 3
---

## Usuario en GitHub.

{% if site.data.repositories.github_users %}
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for user in site.data.repositories.github_users %}
    {% include repository/repo_user.html username=user %}
  {% endfor %}
</div>
{% endif %}

---

## Repositorios en GitHub.

{% if site.data.repositories.github_repos %}
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.github_repos %}
    {% include repository/repo.html repository=repo %}
  {% endfor %}
</div>
{% endif %}
