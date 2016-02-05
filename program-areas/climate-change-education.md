---
title: Climate Change Education
permalink: climate-change-education/
---

<p class="lead">Volunteers use data visualization and ICTs to educate their communities about climate change. They assist in mitigating and adapting to its effects and assisting in the transition towards green communities.</p>



___



## Resources and Toolkits

- [Climate Change Education Resources](/climate-change-education/resources/)


___



# Overview




# Volunteer Projects

{% for project in site.volunteer-projects %}
{% if project.program-areas contains 'climate-change-education' %}
#### [{{ project.title }}]({{project.url}})
{{ project.summary }}
{% endif %}
{% endfor %}