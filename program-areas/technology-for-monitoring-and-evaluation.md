---
title: Technology for Monitoring & Evaluation
---

<p class="lead">Volunteers use mobile technologies to more effectively monitor their project activities, collect feedback, evaluate their work, and scale their successes.</p>



___



## Table of Contents

- [Introduction](#introduction)
- [Volunteer Projects](#volunteer-projects)



___



# Introduction

Mobile data collection allows Peace Corps Volunteers to adopt a real-time, feedback-oriented, documented approach to their projects and activities. It enables our service to be oriented towards impact, and for our Volunteers to become better development professionals.



# Volunteer Projects

{% for page in site.pages %}
{% if page.program-areas contains 'technology-for-monitoring-and-evaluation' %}  
#### [{{ page.title }}]({{page.url}})
{{ page.summary }}
{% endif %}
{% endfor %}


