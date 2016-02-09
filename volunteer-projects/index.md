---
title: Volunteer Projects
layout: post
---

<ul>
{% for project in site.volunteer-projects %}
<li><a href="{{ baseurl }}/volunteer-projects/#{{ project.slug }}">{{ project.title }}</a></li>
{% endfor %}
<li><a href="{{ baseurl }}/volunteer-projects/#other-projects">Other Projects</a></li>
</ul>

___

{% for project in site.volunteer-projects %}{% unless project.slug == "other-projects" %}
<h3 id="{{ project.slug }}">{{ project.title}}</h3>
<em>{{ project.country }}</em> — {% for y in project.year %}<em>{{ y }}</em>{% unless forloop.last %}, {% endunless %}{% endfor %}
{% endunless %}
{{ project.content }}
<hr />
{% endfor %}

{% for project in site.volunteer-projects %}{% if project.slug == "other-projects" %}
<h3 id="{{ project.slug }}">{{ project.title}}</h3>
{{ project.content }}
{% endif %}
{% endfor %}