---
title: mHealth Reader
---

<p class="lead">Volunteers use mobile communication devices, such as mobile phones, computers, and digital services to facilitate access to health services and information.</p>



___



##### Contents

- [Introduction](#introduction)
- [The Mobile Data Mindset](#the-mobile-data-mindset)
- [Mobile Data Collection Questions](#mobile-data-collection-questions)
- [Platforms and Apps](#platforms-and-apps)
- [Going Forward](#going-forward)



___



# Introduction

Mobile health initiatives have been shown to strengthen the demand for health services, improve the ability of health workers to deliver those services, and strengthen health system capacity.

”Delivering vital health messages via mobile phones to new and expectant mothers enrolled in the MAMA Bangladesh program resulted in higher facility births (57%) among program participants compared to the national average (29%).

# Volunteer Projects

{% for page in site.pages %}
{% if page.program-areas contains 'mhealth' %}  
### [{{ page.title }}]({{page.url}})
{{ page.summary }}
{% endif %}
{% endfor %}