---
title: Radio and Mass Media
permalink: radio-and-mass-media/
---

<p class="lead">Volunteers amplify the reach of their programs through broadcast technologies, leveraging their reach, affordability, and attention to local communities. teach English, personal hygiene, environmental lessons, and to promote civic dialogue.</p>



___



## Resources and Toolkits

- [Radio and Mass Media Resources](/radio-and-mass-media/resources/)



___



# Overview

Radio shows have been used to help volunteers share new musical genres with their host communities, This focus on sustainability allows community members to take over the radio station when the volunteer leaves. This helps to increase the long-term sustainability of these kinds of development projects. As well, the auditory nature of radio helps community residents, many who are illiterate, to gain important access to the information on the radio, without the necessity of reading.



# Volunteer Projects

{% for project in site.volunteer-projects %}
{% if project.program-areas contains 'radio-and-mass-media' %}
#### [{{ project.title }}]({{project.url}})
{{ project.summary }}
{% endif %}
{% endfor %}