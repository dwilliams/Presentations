:title: The Future of Embedded Systems and IoT in Smart Communities and Buildings
:author: Daniel Williams
:keywords: IoT, Embedded Systems
:skip-help: true
:css: presentation.css

Outline:

* Who am I?

* Obligatory what is IoT? (less about IoT and more about Types of IoT)

* Three types of IoT: Residential, Commercial, Industrial

* Residential IoT

  * Gimics and Gadgets

* Industrial IoT

  * New name for the things we've been doing for years

  * SCADA

* Commercial IoT

  * This is where the magic is happening

  * Future is systems and integrations, Islands are less than useless

  * All about solving problems

    * Reducing recurring operational costs

    * Making tenants more confortable

    * Monitoring the building for maintenance and security issues

  * Data is effectively useless, people want information

    * Simpleton's definitions of data vs information

    * Most people can't interpret sensor data

    * People want information that can be acted upon (e.g. adjust the temperatur to save a buck on the heating bill)

  * Integrations, bring different datas together to synthesize more insightful informations

    * Insert joke about marketing wank

    * Insert picture of Data and Lore

  * Local analysis and response is essential

    * Internet round trip make cloud take too long

    * Relying on internet/WAN technologies adds unneeded dependencies

    * Cloud good for logging, supplimental data and analysis

    * WAN connections OK for supplimental sensors

* Where are we going with all of this?

* Conclusions

  * IoT isn't going away.  It's just part of the internet.

  * Information synthesis is critical.

  * Interactions with other data sources is critical.

  * Bringing all of it together to for a system is the key.

* Questions?

  * I probably don't have the answers.

.. title:: The Future of Embedded Systems and IoT in Smart Communities and Buildings

.. footer::

  Daniel Williams, dwilliams@inovonics.com

----

:id: title-slide

The (not so distant) Future of
==============================

Embedded Systems and IoT in
===========================

Smart Communities and Buildings
===============================

by some guy working on an *IoT Project* or two

.. note::

  This is the title slide.  Smile.

----

:id: who-am-i

Who am I?
=========

Daniel Williams

Sr Systems Architect

Inovonics Wireless Corporation

dwilliams@inovonics.com

.. note::

  * I have a bit of a jaded view.

  * I work for a company that has been doing these kinds of things for 30+ years.

  * I've even tried making some of my own IoT wizbangs

    * Truth be told, still trying

----

:id: what-is-iot

Obligatory: What is IoT?
========================

The Internet of things (IoT) is the inter-networking of physical devices, vehicles (also referred to as "connected
devices" and "smart devices"), buildings, and other items embedded with electronics, software, sensors, actuators, and
network connectivity which enable these objects to collect and exchange data.

*Wikipedia*

.. note::

  * This is the internet, ladies and gentlemen

----

:id: types-of-iot

Types of IoT
============

* Residential

* Commercial

* Industrial

.. note::

  * There's a ton of overlap between these types.

----

:id: residential-iot

Residential IoT
===============

* Gimmicks

  * Padlocks & Bike locks

  * Tracking tags

  * Light switches

* Marketing

  * Alexa & Google Home

* DIY / Open Source

  * Too many to list

.. note::

  * Most of these devices have limited use.

  * There are systems like Iris and Samsung, but they try to force vendor lock-in and are still gimmicky

  * We'll touch on technical issues later in the presentation

    * similar to commercial IoT

----

:id: industrial-iot

Industial IoT
=============

* Already been done.

* Supervisory control and data acquisition (SCADA)

* Programmable Logic Controllers (PLCs)

----

.. image:: https://upload.wikimedia.org/wikipedia/commons/a/a3/Kontrollrom_Tyssedal.jpg
    :width: 800px

.. note::

  * Industrial controls were moving from this...

----

.. image:: https://upload.wikimedia.org/wikipedia/commons/0/03/Leitstand_2.jpg
    :width: 800px

.. note::

  * ...to this before the "IoT revolution".

----

:id: commercial-iot

Commercial IoT
==============

* Usually focused on Building Automation

  * High Volume Air Conditioning (HVAC)

    * Maintence Monitoring

    * Occupancy

  * Lighting

    * Maintence Monitoring

    * Occupancy

  * Utility Usage

    * Electricity

    * Water

    * Natural Gas / Steam

  * Security

    * Access Control

    * Property Monitoring

  * Etc.

.. note::

  * I'm just touching on a few biggies here, there's tons more.

  * This is where the magic is happening, lots of figuring out how to do it.

  * These system aren't integrated yet, but they should be.

----

:id: problem-solving-1

It's All About Solving Problems
===============================

* Locking up a bicycle: SOLVED (Roman Era, 500 BC – 300 AD)

* Turning lights on and off: SOLVED

* Adjusting the temperature: SOLVED

.. note::

  * The IoT bike lock did nothing but add complexity to an already solved problem.

  * IoT light switches added the ability for chinese script kiddies to turn your lights on and off too.

  * Thermostats were one of the earliest forms of automation, but didn't require the internet to do the job.

----

:id: problem-solving-2

It's All About Solving Problems
===============================

The problems that building operators want to solve:

* Reduce recurring operational costs

* Monitor their buildings for maintenance and security issues

* Provide better comfort and convenience to their tenants

.. note::

  * Being proactive with maintenance and security reduces one-time repair costs.

  * Better comfort and convenience means more money for rent and more reliable renters.

----

:id: data-is-useless

Data is Useless, We want Information
====================================

* Data is measured, collected and reported, and analyzed, whereupon it can be visualized using graphs, images or other
  analysis tools.  *wikipedia*

* Information is that which informs. In other words, it is the answer to a question of some kind. It is thus related to
  data and knowledge, as data represents values attributed to parameters, and knowledge signifies understanding of real
  things or abstract concepts.  *wikipedia*

* Sensor data is hard to analyze.

* People want recommendations on which settings to adjust and how much to adjust them.

.. note::

  * This is an incredibly important concept and most engineers (the people making the IoT bits) miss it.

  * Few people in this world can look and data and understand what's going on.  Fewer can do proper data analysis.

  * End users don't care about the process used to extract the recommations (which is the information) as long as it's
    accurate, efficient (e.g. doesn't require an entire server room to be maintained), and matches their desires.

----

:id: integrations-are-better

Integrations are Better
=======================

* Ingest data from multiple sensors

* Ingest information from multiple sources

* Bring different datas together to synthesize more insightful information

.. image:: https://images-na.ssl-images-amazon.com/images/M/MV5BMTc0MjgwMzQ4OV5BMl5BanBnXkFtZTgwODQ4MDAwMjE@._V1_SX1777_CR0,0,1777,999_AL_.jpg
    :width: 400px

* Present the information in a unified method.

.. note::

  * The verb ingest is used on purpose.

  * Don't forget the marketing wank joke.

  * The last point is important.  People don't want to access 17 different systems, they want everything on one place.

    * Smartphones are the perfect example of this.

----

:id: local-controllers

Local Controllers are Essential
===============================

* Internet round-trips take too long.

* Relying on internet & WAN technologies adds unneeded dependencies

* Who's going to support the servers when the supplier goes away?

* Cloud systems should be for long-term data and log storage, supplimental analysis horsepower

* Critical decisions must stay local to the system

.. note::

  * We (the ones making these devices) are the suppliers.  Look at Revolv (bought by Google Nest).

  * This is one of the biggest flaws in the residential market (too focused on vendor lock-in and recurring revenue)

  * No one wants a light that takes 30 seconds to turn on, or an HVAC system that stops working when the internet
    connection fails.

----

:id: where-are-we-going

Where are we going with all of this?
====================================

* The starship Enterprise (minus the warp drive)

.. image:: https://images-na.ssl-images-amazon.com/images/M/MV5BMjM3NzY1NzE0N15BMl5BanBnXkFtZTgwMjM0ODA1NTE@._V1_SX1777_CR0,0,1777,999_AL_.jpg
    :width: 400px

* Smart buildings will be able to reduce their operating costs.

* Smart buildings will be able to adjust their environments to occupancy and usage demands.

* Smart buildings will be able to call for help with maintenance and security issues.

* All of these will happen without human intervention.

----

:id: conclusions

Conclusions
===========

* IoT isn't going away and it's nothing new.  It's just part of the internet.

* Information synthesis is critical.

* Interactions with other data & information sources is critical.

* Bringing it all together into a unified system is the key.

* All of it comes together to all smart building and smart communities.

----

Questions?
==========
