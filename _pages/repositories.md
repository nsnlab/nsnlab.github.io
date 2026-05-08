---
layout: page
permalink: /repositories/
title: code
description:
nav: true
nav_order: 5
---

Our code and resources are hosted on GitHub. Visit the [NSN Lab repositories](https://github.com/orgs/nsnlab/repositories) to explore our tasks, questionnaires, pre-processing pipelines, and ongoing projects.

{% if site.data.repositories.github_repos %}

## GitHub Repositories

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.github_repos %}
    {% include repository/repo.liquid repository=repo %}
  {% endfor %}
</div>
{% endif %}
