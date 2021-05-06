---
layout: post
title:  "Deciding the design of our drone"
date:   2021-05-06
categories: preparing for build
author: christine
---

Armed with some knowledge about different components of the drone we made some fundamental decisions on how to move forward.

#### Build from scratch
Fundamentally we have decided to do everything from scratch as much as possible. This was Alexey's idea and I'm kind of just rolling with it at this point. This means a much slower time to delivery, but also we will (hopefully) know more about what it really takes to make something that can fly. 


#### The flight controller
We decided to start with making the flight controller and just play around with the controls first. We wanted to design our own arduino based flight controller so that we can do some programming and apply the flight control algorithms ourselves. After some sleuthing, we decided to get the [arduino one](https://store.arduino.cc/arduino-uno-rev3) as it has been used in previous drone projects, has a good number of input/output channels (14) and is affordable (20 euro). We also purchased a [prototyping board](https://store.arduino.cc/proto-shield-rev3-uno-size) (10euro). 

#### Sensors

Sensors are necessary for a more smooth flight. We opted to buy an [inertial measurement unit (IMU)](https://www.vanallesenmeer.nl/9-Degrees-of-Freedom-IMU-Breakout-LSM9DS1-Sparkfun-13284) which contains a gyroscope (detects angular changes of drone) and an accelerometer (measures acceleration). This helps with keeping the drone stable in flight. In addition we bought a [barometer](https://www.vanallesenmeer.nl/Barometric-Pressure-Sensor-Breakout-MPL115A1-Sparkfun-09721) (pressure sensor) to tell us the altitude of the drone. We decided not to purchase a GPS or a compass at this moment as these are expensive and can be added later. 


#### Build own frame 
Alexey is currently looking into the making our own carbon fiber frame, instead of just buying an already available one. This would require also buying the material, and getting it 3d printed somewhere in Amsterdam. Let's see if that's possible!


#### Overall Purchases 

|  Item | Purpose  | Source  |
|---|---|---|---|---|
| arduino uno  |  flight controller |  [arduino store](https://store.arduino.cc/arduino-uno-rev3)  | 
| proto shield | prototyping board | [arduino store](https://store.arduino.cc/arduino-uno-rev3) | 
| IMU  | positional sensors   | [vanallesenmeer (dutch store)](https://store.arduino.cc/proto-shield-rev3-uno-size)|  
| barometer  | pressure sensor |  [vanallesenmeer (dutch store)](https://www.vanallesenmeer.nl/Barometric-Pressure-Sensor-Breakout-MPL115A1-Sparkfun-09721)   |  

#### Next up

We'll be waiting for our purchases to arrive so we can play with the arduino. Excited!
