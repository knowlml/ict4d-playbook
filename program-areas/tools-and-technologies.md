---
title: Tools and Technologies
permalink: tools-and-technologies/
---

<p class="lead">Volunteers use and promote tools and technologies in applications that are locally relevant, sustainable, cost-effective, and environmentally sound.</p>



___



## Resources and Toolkits

- [Tools and Technologies Resources](/tools-and-technologies/resources/)



___



# Overview


# Volunteer Projects

{% for project in site.volunteer-projects %}
{% if project.program-areas contains 'tools-and-technologies' %}
#### [{{ project.title }}]({{project.url}})
{{ project.summary }}
{% endif %}
{% endfor %}
