---
title: Youth Workforce Employment
---

<p class="lead">Volunteers use ICTs in extending training to more individuals at lower cost, providing a means to more broadly disseminate replicable and customizable content, providing opportunities for better learning outcomes, and enabling connections among youth and employers.</p>



___



## Table of Contents

- [Introduction](#introduction)
- [Volunteer Projects](#volunteer-projects)



___



# Introduction

“In the developing world, it’s hard to find good information about jobs: resources are scarce and social connections are limited. Mobile job matching services mean that youth and employers can be linked anytime and anywhere - even in areas without internet.” - Jacob Korenblum, President and CEO, Souktel



# Volunteer Projects

{% for page in site.pages %}
{% if page.program-areas contains 'youth-workforce-employment' %}  
#### [{{ page.title }}]({{page.url}})
{{ page.summary }}
{% endif %}
{% endfor %}


