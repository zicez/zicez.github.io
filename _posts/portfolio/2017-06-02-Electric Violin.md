---
layout: article
title: Electric Violin
categories: portfolio
share: false
image:
    feature: violin/3.jpg
    teaser: violin/3.jpg
---
Converting my acoustic violin into an electric violin. 

#### High Level Design
There are a couple of different methods to convert an acoustic instrument to an electric instrument. For this project, I built an magnetic pickup. This is the same technology that enabled the electric guitar. 

The magnetic pickup is composed of a magnet and a coil. The pickup is placed underneath the strings of a violin. It’s important to make sure that the strings are magnetically permeable i.e. steel and not gut core. As the string vibrates to make sound, a small current is induced in the string as it moves in the magnetic field of the magnet. The small induced current generates its own magnetic field. This generated field produces a voltage in the coil. As the string moves to make sound, a copy of that movement is generated as a changing voltage within the coil.

<img width="1604" alt="bridge_1" src="/images/violin/pickup.jpg">

#### Building the pickup
The frame of the pickup is made from laser cut acrylic and steel threaded standoffs. I had access to free acrylic, and the steel standoffs were cheaper. 

|<img width="1604" alt="lasercut" src="/images/violin/lasercut.jpg">|<img width="1604" alt="" src="/images/violin/standoff.jpg">|

For the sound to be captured equally on each of the violin string, we need to ensure the magnet can place an equal magnetic field at each of the violin string. However, on a violin, each string has an unequal height to the body of the violin, so a simple bar magnet placed underneath the strings will not work.

To solve this issue, ￼four threaded standoffs are placed on top of a bar magnet. Each standoff is spaced out similarly to how the strings are spaced out. A bolt is inserted into each of the standoff. It’s important that the standoffs and the bolts are magnetically permeable. The inserted bolt can adjust its own height by screwing down and up the standoff. With this setup, we can transmit the magnetic field from the bar magnet up through the standoffs and bolt. Since the bolt is height adjustable, we can ensure that an equal magnetic field is produced at each string.

<img alt="adjustable" src="images/violin/standoff_adjust.png">

<img alt="adjustable" src="images/violin/adjustable_height.png">



#### Images

| | |
|:-------------------------:|:-------------------------:|
|<img width="1604" alt="bridge_1" src="/images/maslab/1.jpg">|<img width="1604" alt="bridge_2" src="/images/maslab/2.jpg">|

|<img width="1604" alt="bridge_3" src="/images/maslab/3.jpg">|<img width="1604" alt="bridge_4" src="/images/maslab/4.jpg">|