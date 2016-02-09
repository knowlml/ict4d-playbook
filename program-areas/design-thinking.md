---
title: Design Thinking
permalink: design-thinking/
---

<p class="lead">Volunteers use design thinking and promote creative capacity-building to respond to the challenges of their host communities and counterparts. They investigate the needs, context, and assets of their environment and use cooperative problem-solving to build towards sustainable solutions.</p>

Volunteer activities include:

- Using design thinking and creative capacticy building (CCB) to supplement PACA (Participatory Analysis for Community Actions)
- Conduct CCB for 


___



## Resources and Toolkits

- [Design Thinking Resources](/design-thinking/resources/)



___



# Overview

Design thinking is a way of approaching problem-solving in a way that puts people first. Peace Corps Volunteers are trained to listen to their communities, to facilitate problem-solving, and to help act as agents of change within their service.

Volunteers start (and end) their service from a foundation of empathy and cooperative understanding. It is this framing that has allowed the Peace Corps Volunteers to consistently and effectively carry out our mission of ‘promoting world peace and friendship through community-based development and grassroots understanding.’

Design thinking isn’t simply about crafting a design solution to a user-centered problem. It’s about ensuring that we are bringing all of the ideas, approaches, perspectives and priorities to bear on a recognized need or challenge.



# Volunteer Projects

{% for project in site.volunteer-projects %}
{% if project.program-areas contains 'design-thinking' %}
#### [{{ project.title }}]({{project.url}})
{{ project.summary }}
{% endif %}
{% endfor %}

