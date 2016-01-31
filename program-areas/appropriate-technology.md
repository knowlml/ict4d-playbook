---
title: Appropriate Technology
---

<p class="lead">Volunteers employ methods that are recognized as encompassing technological choice and application that are generally small-scale, decentralized, labor-intensive, energy-efficient, environmentally sound, and locally controlled.</p>



___



## Table of Contents

- [Introduction](#introduction)
- [Volunteer Projects](#volunteer-projects)



___



# Volunteer Projects

{% for page in site.pages %}
{% if page.program-areas contains 'appropriate-technology' %}  
#### [{{ page.title }}]({{page.url}})
{{ page.summary }}
{% endif %}
{% endfor %}



