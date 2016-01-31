---
title: Climate Change Education Reader
---

<p class="lead">Volunteers leverage ICTs as fundamental for monitoring climate change, mitigating and adapting to its effects and assisting in the transition towards green communities.</p>



___



##### Contents

- [Introduction](#introduction)
- [Readings](#readings)



___



# Introduction




# Volunteer Projects

{% for page in site.pages %}
{% if page.program-areas contains 'climate-change-education' %}  
### [{{ page.title }}]({{page.url}})
{{ page.summary }}
{% endif %}
{% endfor %}