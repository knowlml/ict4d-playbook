---
title: Climate Change Education
---

<p class="lead">Volunteers leverage ICTs as fundamental for monitoring climate change, mitigating and adapting to its effects and assisting in the transition towards green communities.</p>



___



## Table of Contents

- [Introduction](#introduction)
- [Volunteer Projects](#volunteer-projects)



___



# Introduction




# Volunteer Projects

{% for page in site.pages %}
{% if page.program-areas contains 'climate-change-education' %}  
#### [{{ page.title }}]({{page.url}})
{{ page.summary }}
{% endif %}
{% endfor %}