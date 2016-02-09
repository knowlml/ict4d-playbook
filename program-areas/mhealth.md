---
title: mHealth
permalink: mhealth/
---

<p class="lead">Volunteers use mobile communication devices, such as mobile phones, computers, and digital services to facilitate access to health services and information.</p>



___



## Resources and Toolkits

- [mHealth Resources](/mhealth/resources/)

___



# Overview

Mobile health initiatives have been shown to strengthen the demand for health services, improve the ability of health workers to deliver those services, and strengthen health system capacity.

”Delivering vital health messages via mobile phones to new and expectant mothers enrolled in the MAMA Bangladesh program resulted in higher facility births (57%) among program participants compared to the national average (29%).



# Volunteer Projects

{% for project in site.volunteer-projects %}
{% if project.program-areas contains 'mhealth' %}
#### [{{ project.title }}]({{project.url}})
{{ project.summary }}
{% endif %}
{% endfor %}