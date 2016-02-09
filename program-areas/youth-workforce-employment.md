---
title: Youth Workforce Employment
permalink: youth-workforce-employment/
---

<p class="lead">Volunteers use ICTs to facilitate easier access to education, share knowledge and information more broadly, provide better and more opportunities for learning outcomes, and to connect youth and employers.</p>




___



## Resources and Toolkits

- [Youth Workforce Employment Resources](#youth-workforce-employment/resources/)


___



# Overview

“In the developing world, it’s hard to find good information about jobs: resources are scarce and social connections are limited. Mobile job matching services mean that youth and employers can be linked anytime and anywhere - even in areas without internet.” - Jacob Korenblum, President and CEO, Souktel



# Volunteer Projects

{% for project in site.volunteer-projects %}
{% if project.program-areas contains 'youth-workforce-employment' %}
#### [{{ project.title }}]({{project.url}})
{{ project.summary }}
{% endif %}
{% endfor %}