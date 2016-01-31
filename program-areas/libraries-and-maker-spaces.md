---
title: Libraries and Maker Spaces
---

<p class="lead">Volunteers help to renovate, build, and support local libraries in their communities. These are spaces foster inclusivity, learning and education, creativity, problem solving, and a place for community engagement.</p>



___



## Table of Contents

- [Introduction](#introduction)
- [Volunteer Projects](#volunteer-projects)



___



# Introduction



# Volunteer Projects

{% for page in site.pages %}
{% if page.program-areas contains 'libraries-and-maker-spaces' %}  
#### [{{ page.title }}]({{page.url}})
{{ page.summary }}
{% endif %}
{% endfor %}


