---
layout: portfolio_entry
title: Summer UROP 2016
image: /img/folder-name/image-name.png
---

Building a landing platform for a drone ontop of an ATRV

### The Constraints

#### The Test Drone: AR.Drone 2
The MERS lab has an abundance of the AR.Drone 2 from teaching a class. Additionally, the lab also has a large supply of batteries, so continuous testing can be carried out. However, the nicest feature from working with the drone is the availability of [ardrone_autonomy](http://ardrone-autonomy.readthedocs.io/en/latest/), a ROS driver for the AR. Drone 2. The framework allows me to control, access the camera, and pull data from the drones with ROS.

#### The

### Autonomous Landing
This was arguably one of the most important step in the entire process even though it had nothing to do with the design of the platform. Its importance comes from the fact that without an accurate and precise landing algorithm the landing platform will never be able to latch onto the drone. Without the drone being able to land accurately within at least +- 5 inches, there was no design that could accommodate for the drone.

#### Tag detection

##### Slightly Hardware Modification
For AR. Drone 2.0, it is only possible to receive the 
##### Onboard detection
The built in detection of the AR.Drone 2 is really bad. Firstly, it was almost impossible to find an image of the detected tags on AR.Drone's website or clear specifications on how the detection works in its documentations. I could only find the needed tags, the roundel tag, in a third party [website](http://www.playsheep.de/drone/downloads.html). Secondly, the detection only works if the tag is perpendicularly facing the camera. Any slight deviation in the viewing angle will not trigger the detection. This is fatal for our purpose because the  

More Content.
