---
title: Media Production
permalink: media-production/
---

<p class="lead">Volunteers use digital audio photography and videography in order to act as storytellers and to engage the Third Goal of Peace Corps</p>



___



## Resources and Toolkits

- [Media Production Resources](/media-production/resources/)


___



# Overview



# Volunteer Projects

{% for project in site.volunteer-projects %}
{% if project.program-areas contains 'media-productions' %}
#### [{{ project.title }}]({{project.url}})
{{ project.summary }}
{% endif %}
{% endfor %}