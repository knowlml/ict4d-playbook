---
title: Libraries and Maker Spaces
permalink: libraries-and-maker-spaces/
---

<p class="lead">Volunteers help to promote, build, renovate, and support local learning in their communities. These help to create spaces that foster inclusivity, learning and education, creativity, problem solving, and community engagement.</p>



___



## Resources and Toolkits

- [Libraries and Maker Spaces Resources](/libraries-and-maker-spaces/resources)


___



# Overview



# Volunteer Projects

{% for project in site.volunteer-projects %}
{% if project.program-areas contains 'libraries-and-maker-spaces' %}
#### [{{ project.title }}]({{project.url}})
{{ project.summary }}
{% endif %}
{% endfor %}