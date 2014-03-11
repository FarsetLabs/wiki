Contents
--------

-   [1 Background](#Background)
    -   [1.1 Justification](#Justification)
-   [2 Implementation](#Implementation)
-   [3 Notes](#Notes)

Background
==========

The SpaceAPI was [born](https://hackerspaces.nl/spaceapi/) in the Netherlands, and now [lives on github](https://github.com/SpaceApi).

It exposes information such as:

-   Open/Closed State
-   Location
-   Webcam Feeds
-   Contact Details
-   Sensor data

and more, from a simple JSON API.

Justification
-------------

The Farset Labs SpaceAPI server was built to solve the problem of multiple occupancy on the K8055 interface board, that had been the centre of the space's [open/closed notification system](http://www.andrewbolster.info/blog/2012/04/k8055-usb-python-twitter-irc-space-indicator-as-a-os-service/).

This system, internally called on differentoccasions Farbot, or Titania, communicated over Twitter and IRC as well as exposing a SpaceAPI json responder for any [enabled](http://hackerspaces.me) services.

When it was decided to integrate the door control from the planned Access Control System into the same service, it quickly became clear that Titania was getting too big and too ugly, and it would be beneficial to decompose the problem into different application.

But these applications wouldn't be able to talk to the k8055 at the same time, so there would have to be ANOTHER application sitting on top of the board, providing a unified API access point.

Implementation
==============

The Farset Labs Space API is built on top of the Flask micro-framework, and using a customised version of the authdigest plugin to provide for persistent file-based authentication database.

[GitHub](http://github.com/FarsetLabs/SpaceAPI)

Not only have we produced the api service (running on [farbot.unit1.farsetlabs.org.uk](http://unit1.farsetlabs.org.uk/spaceapi/)), but there is also a simple python client libary that can be used to play with the service from anywhere in the world.

Notes
=====

-   [Interspace Federated Auth system](http://spacefed.net/wiki/index.php/SpaceFED)
-   [Intro and spec of SpaceApi](http://hackerspaces.nl/spaceapi/)
-   [SpaceAPI Github](https://github.com/SpaceApi/SpaceApi) - Currently shit, but gmc is a busy man
-   [ACKspace SpaceAPI Setup](http://ackspace.nl/wiki/SpaceAPI)
