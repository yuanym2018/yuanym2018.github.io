---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume

---

{% include base_path %}

Education
======

* MSc in Textile Engineering (01/2024 - present)

	* Wilson College of Textiles, North Carolina State University

	* Research topic: Wearable Energy Harvestor, Ionotronics, etc.

	* Supervisor: Prof. Thomas B.H. Schroeder

		

* BSc in Microelectronics Science and Engineering (09/2018 - 07/2022t)

	* School of Microelectronics, Southern University of Science and Technology
	* Research topic: Ionotronic Pressure Sensor
	* Supervisor: Prof. Min Wang

Work experience
======

* Research Assistant (07/2022 - 12/2023)
	* Department of Mechanics and Aerospace Engineering, Southern University of Science and Technology
	* Research topic: Ionotronic Pressure Sensor
	* Supervisor: Prof. Canhui Yang


Skills
======

* Basic Programming (now usually use Python and MATLAB)

* Necessary Software for Research

	* Illustrator and 3ds Max for beautiful figures in paper
	* Origin Pro for data processing and plotting

* Basic Circuit Theory (almost forgotten, only go refering to the textbook if needed)

	-"But, wait, isn't your major in microelectronics?"

	-Well, if I learn well in electronics, then why don't I stay in this major instead of changing it to textile?

* Using Arduino

	-I know what you wanna ask. Well, firstly for wearable elctronics research, it is necessary to use a controller for the device demonstration. Secondly, for students that major in electronics, Arduino is like a toy of kids, and they always think that using MCUs like MSP430, STM32 or others is the coolest and most elegant choice. If they are not able to use these MCUs (like me), they are too ashamed to say that they are major in electronics.

Publications
======

  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>


Talks
======

  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>


Teaching
======

  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

