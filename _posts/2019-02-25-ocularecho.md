---
layout: post
title:  "Ocular Echo"
date:   2019-02-25
excerpt: "Ocular Echo: A hackathon project to aid the visually impaired"
project: true
tag:
comments: false
---

## Overview

This is our entry for Cutie Hack IV, the annual hackathon at University of California, Riverside.

This prototype aims to assist in the navigation of the visually impaired. Unlike normal guide canes, the Ocular Echo detects obstacles above waist level. This helps prevent collisions with certain objects, like cars. A normal guide cane would go underneath the car, giving the user false information. 

To solve this we came up with the idea of using ultrasonic sensors paired with vibration motors. The concept is the user would possibly wear or hold these sensors. As the user got close to an object, the sensors would react appropriately by vibrating more intensely depending on the distance to the object. A variable beep would accompany the vibrations, giving the user audio feedback as well.

We successfully presented and demoed our project in front of a panel of judges and our peers. In our presentation, we made the case that this technology can be scaled down to be more portable. In due time, we could see the sensors become part of clothing, such as a jacket covered in these sensors. 

## Implementation 

For our project, we have the device split into two separate systems. The original idea was to have one unit power both sensors, but due to limited options in regards to parts, we created two separate systems that can be mounted in various ways. Our project is not a replacement to assistive canes, but rather as an additional toolset for the visual impaired.

With the proper modules, we could have more accurate sensors that would provide feedback on environmental obstacles.

<figure class="half">
    <a href="/assets/img/ocularecho/OCE2.jpg"><img src="/assets/img/ocularecho/OCE2.jpg"></a>
    <a href="/assets/img/ocularecho/OCE3.jpg"><img src="/assets/img/ocularecho/OCE3.jpg"></a>
    <figcaption>Caption describing these two images.</figcaption>
</figure>

#### Design

The project is made up of:
* Arduino
* 2 motors
* 2 proximity sensors
* 2 Speakers
* Transistors and wires
* Cardboard
* Duct tape

The Arduino handles the input from the proximity sensors. It detects objects in a 30-degree cone. Once it detects something, the motor pulses to provide haptic feedback. The speaker begins to emit a sound that increases in frequency, giving the user a sense of how far the object is.

Our design is rudimentary and based on a collection of scavenged parts, but with refinement, we can improve the product to be lighter and more user-friendly. 

You can check out the code [here](https://github.com/mzeml/Ocular-Echo), if you're interested 


## Special Thanks to My Teammates!
**Huzaifah Simjee** - hsimj001@ucr.edu
**Steven Fan** -  sfan008@ucr.edu