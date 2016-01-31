---
title: Radio and Mass Media Reader
---

<p class="lead">Volunteers amplify the reach of their programs through broadcast technologies, leveraging their reach, affordability, and attention to local communities. teach English, personal hygiene, environmental lessons, and to promote civic dialogue.</p>



___



## Table of Contents

- [Introduction](#introduction)
- [Volunteer Projects](#volunteer-projects)



___

# Introduction

Radio shows have been used to help volunteers share new musical genres with their host communities, This focus on sustainability allows community members to take over the radio station when the volunteer leaves. This helps to increase the long-term sustainability of these kinds of development projects. As well, the auditory nature of radio helps community residents, many who are illiterate, to gain important access to the information on the radio, without the necessity of reading.


# Volunteer Projects

{% for page in site.pages %}
{% if page.program-areas contains 'radio-and-mass-media' %}  
### [{{ page.title }}]({{page.url}})
{{ page.summary }}
{% endif %}
{% endfor %}