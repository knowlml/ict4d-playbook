---
title: Digital Literacy
permalink: digital-literacy/
---

<p class="lead">Volunteers educate their communities on the use of digital tools, mobile phones, and computers; and more broadly they strive to narrow the economic and social inequality in the access to, use of, and/or impact of ICTs.</p>

Volunteer activities include:

- Basic computer skills in classrooms for students, youth, and adults.
- Intermediate computer and Internet literacy—operating systems, productivity software, web browsers, digital privacy and protection skills.
- Advanced digital literacy related to libraries and computer labs, media production, computer programming.
- Technology-oriented clubs and camps for youth that incorporate ICTs into life-skills, youth development, and other sectoral areas.



___



## Resources and Toolkits

- [Digital Literacy Resources](/digital-literacy/resources/)
- [Digital Literacy Lesson Plans](/toolkits/digital-literacy-lesson-plans/)



___



# Overview

All Volunteers are educators, across all sectors and in all countries.

We live in an increasingly digital world where communities (even remote ones) are often keenly aware of the potential benefits to be gained from skill sets associated with computers mobile phones, and the Internet. They are also aware of the risk associated with not being digitally literate for themselves and for their future generations.

<div class="note">

###### What is the Digital Divide?

The rapid diffusion of technologies around the world—of computers and mobile phones, of opportunities around tech-related jobs and careers, and of access to on-demand services and information—has not necessarily benefitted everyone.

The gulf between the technology ‘haves’ and ‘have nots’ has been called the ‘Digital Divide’ — the social and economic inequality that exists with regards to the access to, use of, or impact of ICTs.

The Digital Divide is not just the inequality between rich and poor countries — it is the gap in geography, in status, in generation , in race, and in gender. If there’s limited understanding about how it all works, these new users will likely miss out.

Our role is to act as catalysts to bridge this divide; to build on the existing historical and market forces that have led to the amazing diffusion of technology and innovation and ensure that it can benefit as many lives as possible.

</div>



# Volunteer Projects

{% for project in site.volunteer-projects %}
{% if project.program-areas contains 'digital-literacy' %}
#### [{{ project.title }}]({{project.url}})
{{ project.summary }}
{% endif %}
{% endfor %}

