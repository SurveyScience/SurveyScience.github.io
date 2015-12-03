---
layout: post
title:  "Taming the Firehose: Using ANTARES to Make Sense of the LSST Alert Stream (Tom Matheson)"
date:   2015-12-01 12:00:00 -0700
categories: jekyll update
---

[Taming the Firehose: Using ANTARES to Make Sense of the LSST Alert Stream](../../../../../../slides/Antares_Survey_Lunch.pdf)

One of the major science goals of LSST is study of time-domain astronomy.  Each image will be compared with a reference and alerts issued for any significant change in brightness or position.  There will be several million alerts per night, every night, for ten years.  Most of these will be variable stars and Solar System objects.  There will also be all of the transients you can imagine and some you haven’t.  Finding objects of interest in a timely manner is critical to exploit the time-domain aspect of LSST thoroughly.  Astronomers at NOAO and computer scientists at Arizona are developing a software infrastructure system to process these alerts.  The Arizona-NOAO Temporal Analysis and Response to Events System (ANTARES) is a prototype of an alert broker, an intermediary that adds value to alerts and distributes them to customers looking for specific events.  I’ll give an overview of the system, show the current status, and discuss where we intend to go with the project.


