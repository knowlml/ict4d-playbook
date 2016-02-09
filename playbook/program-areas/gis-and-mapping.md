---
title: GIS and Mapping
permalink: gis-and-mapping/
---

<p class="lead">Volunteers use geospatial information systems (GIS) and mapping approaches to assist in community assessments, participatory analysis, and sector-specific projects.</p>

Volunteer activities include:

- Track and improve upon projects and progress with local communities.
- Record geospatial data associated with field surveys and project activities.
- Using maps as a reporting feature as part of any project (Volunteer or community-led).
- Contributing to global open-source datasets and maps like [OpenStreetMap](https://www.openstreetmap.org/#map=5/51.500/-0.100).



___



## Resources and Toolkits

- [GIS and Mapping Resources](/gis-and-mapping/resources/)
- [Field Guide to GIS](/toolkits/field-guide-to-gis/)



___



# Overview

Understanding and analzying geospatial data and maps lead to a more holistic view of the world around us, our projects, and our efforts that help us to assess, report, and improve our impact as Peace Corps Volunteers.

GIS is reshaping the way we consider, carry out and evaluate international development initiatives. Organizations use digital maps to understand a variety of development-related issues: critical outbreaks and health other issues; the monitoring of natural disasters and emergency risk management; distribution of food programs and products; and drawing attention to issues of human rights abuses, corruption, and social welfare.

Here are a couple of examples where Volunteers can use GIS:

- **Community Maps**. Creating a local map of landmarks, resources and livelihoods together with a community is a [primary component in the Peace Corps' approach to community development](http://files.peacecorps.gov/multimedia/pdf/library/GED5_pacatools.pdf), PACA (Participatory Analysis, Community Action). Using open-source software and data from OpenStreetMap and projects like [OSM-on-Paper](http://wiki.openstreetmap.org/wiki/OSM_on_Paper) help enable this approach.

- **Community-building**. Painting [world maps](http://www.peacecorps.gov/media/forpress/news/1536/) has been a popular activity that Volunteers have engaged with local youth and communities for many years.

- **OpenStreetMap**. Volunteers and staff contribute to projects like [OpenStreetMap](http://www.openstreetmap.org/) and the [Humanitarian OSM team](http://wiki.openstreetmap.org/wiki/Humanitarian_OSM_Team) to assist in using open data to benefit humanitarian aid and economic development (the recent [West Africa Ebola project](http://wiki.openstreetmap.org/wiki/2014_West_Africa_Ebola_Response) is a terrific example of this).



# Volunteer Projects

{% for project in site.volunteer-projects %}
{% if project.program-areas contains 'gis-and-mapping' %}
#### [{{ project.title }}]({{project.url}})
{{ project.summary }}
{% endif %}
{% endfor %}