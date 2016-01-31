---
title: Appropriate Technology Reader
---

<p class="lead">Volunteers employ methods that are recognized as encompassing technological choice and application that are generally small-scale, decentralized, labor-intensive, energy-efficient, environmentally sound, and locally controlled.</p>



___



## Table of Contents

- [Introduction](#introduction)
- [Servers and Local Wifi](#servers-and-local-wifi)
- [Computer Kits](#computer-kits)
- [Presentation and Multimedia](#presentation-and-multimedia)
- [Networking and Telecommunications](#networking-and-telecommunications)
- [Power and Electricity](#power-and-electricity)
- [Appropriate Technology](#appropriate-technology)



___



### Servers and Local Wifi

- [WNDW - Wireless Network in Developing World](http://wndw.net/) -- Practical guide to designing and building wireless networks in local communities, enhancing lives through improved communication, access to information for educational, social and economic growth.

- [LibraryBox](http://librarybox.us/) -- Open source, portable digital file distribution tool based on inexpensive hardware that enables delivery of educational, healthcare, and other vital information to individuals off the grid.

- [Pirate Box](http://piratebox.cc/) -- PirateBox is a DIY anonymous offline file-sharing and communications system built with free software and inexpensive off-the-shelf hardware.

- [LudoBox](http://leschiensdelenfer.org/la-ludobox/ludobox-fr/) -- An offline device to share games released under free licenses. Built from PirateBox and LibraryBox.

- [Outernet (Lantern)](https://www.outernet.is/en/) -- Public library device broadcast from satellite.

- [BRCK](http://www.brck.com/) -- The go anywhere, do anything, self-powered, mobile WiFi device.




### Computer Kits

- [Particle](https://www.particle.io/) -- Full stack solution for cloud connected devices. Spark Photon is a microcontroller with wifi module. Spark Electron is a variant that connects to a cellular network. Spark OS adds REST API to the devices. This simplifies the entry to IoT and building your own connected devices.

- [Kano Raspberry Pi Kit](http://www.kano.me/) -- Kano is a computer anyone can make. Our mission is to give young people – and the young at heart – a simple, fun way to make and play with technology, and take control of the world around them.


### Presentation and Multimedia

- [One Mobile Laptop Per Trainer](http://www.ompt.org/) -- OMPT enables the most under-served communities in the world to lift themselves out of poverty by gaining access to knowledge that can transform their lives.



### Networking and Telecommunications

- [Mesh Potato](http://villagetelco.org/mesh-potato/) -- An easy-to-use, scalable, standards-based, wireless local, DIY, telephone company toolkit.



### Power and Electricity


- [Waka Waka](http://us.waka-waka.com/) -- Solar charger.


# Volunteer Projects

{% for page in site.pages %}
{% if page.program-areas contains 'appropriate-technology' %}  
### [{{ page.title }}]({{page.url}})
{{ page.summary }}
{% endif %}
{% endfor %}



