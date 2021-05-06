---
layout: post
title:  "Building blocks of a drone"
date:   2021-05-02
categories: preparing for build
author: christine
---

The first thing we did in our journey to build a drone was to read up on what it would require to build a drone. These articles are mentioned in a [previous blog post]({% post_url 2021-04-13-Planning %}). As I said in the [last blog post]({% post_url 2021-04-18-How-does-a-drone-work %}), a drone works by fulfilling three things: having a flight mechanism, a source of power, and a brain. Four if you include the body/frame. I'll go over these in detail here.

Things to keep in mind when making an unmanned aerial vehicle (UAV) aka drone: 

#### 1. It's size and the material for the frame

Bigger obviously means more pricy. Certain materials obviously will be more costly. **Carbon fiber** is a popular option due to it's light weight durability. Carbon fiber does come with a downside that it blocks radio frequency signals. Which can be accounted for. 

#### 2.  Getting it up in the air. 
The flight mechanism: motors, propellers, and controlling the speed

UAV's differ depending on the number of **rotors** (the part that spins). Quadcopter is the most popular with 4 rotors, but there are also tricopters (3 rotors) , hexacopters (6 rotors), and octocopers (8 rotors). More rotors naturally leads to more flight power, more storage capacity, and more redundancy. This comes at a higher price tag, and also requires a bigger battery.  

**Motors** converts electrical energy to mechanical energy that leads to spin. It does this by basically playing around with differences in magnetic fields. You might remember that opposite charges attract, and same charges repel. The two kinds of motors, brushed and brushless, exploit these magnetic properties in different ways to generate spin. The difference between the two can be found in [this video](https://www.youtube.com/watch?v=C1-klL3B9LU). In short brushed motors are cheaper & simpler but less efficient and not durable. Brushless are more expensive but more efficient and are therefore usually recommended. 

**Propellers** are the 'wings' which attach to the rotors to achieve altitude. These spin either clockwise or counterclockwise and come in different kinds of materials ( such as plastic) and sizes. Larger blades change velocity slower or, while smaller blades can easily change direction or speed.

#### 3. Powering it up

Everything needs energy, a UAV is no exception. As mentioned before, bigger drones require more energy, which means a bigger battery. It was surprising to me to find out that most drones last around than ten minutes in the air. Naturally, flight time is dependent on how much battery is available!

Keep in mind that the voltage of the battery need to match that of the rotors, since rotors will be needing to convert this energy to mechanical spin. 

#### 4. Drone control

Last but not least is the brain. The brain of a UAV is the **flight controller**. The flight controller does what it's name says: controls the flight. It tells the rotors how fast to spin and in which direction. It reads in sensory data from the surroundings & the drone (air pressure, angular position, acceleration). And it's where all the fun autonomous flight possibilities lie.  You can either buy a prepackaged flight controller or you can make your own from an arduino or rasberry pi!


#### Add ons

There are lots of other additional things you can add to your flight experience. A camera, goggles, a remote control, and so on. 