---
title: Mobile Communications
permalink: mobile-communications/
---

<p class="lead">Volunteers use mobile messaging platforms such as SMS or (short-message texting services) to amplify the reach of their projects, to be more inclusive, and to offer timely updates to their community.</p>



___



## Resources and Toolkits

- [Mobile Communications Resources](/mobile-communications/resources/)



___



# Overview

SMS and mobile phones can improve the productivity of projects, help farmers access markets and value chains, and improve the delivery of services.


# Volunteer Projects

{% for project in site.volunteer-projects %}
{% if project.program-areas contains 'mobile-communication' %}
#### [{{ project.title }}]({{project.url}})
{{ project.summary }}
{% endif %}
{% endfor %}
