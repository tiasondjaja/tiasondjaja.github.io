---
layout: page
title: Computational Projects
permalink: /projects
---

{% for project in site.projects %}
{% if project.status != 'draft' %}
+ [ **{{ project.name }}** ]( {{ project.url }})<br>&nbsp; <span style="color:#2B547E">[{{ project.tag | downcase}}]</span>

	{{project.short_description}} / [arxiv]( {{project.arxiv}} ) / [github]( {{ project.github}} )
{% endif %}
{% endfor %}
