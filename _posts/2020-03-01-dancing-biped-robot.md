---
layout: post
title: "Dancing Biped Robot"
author: "Arnold Ying"
categories: project
image: dancingRobot1.png
---

## Source code: Unavailable
##### I made a dancing biped robot!
##### This was made at UBC with my project course group: [Stella](https://stellawang.com), Amir, Rain, Parsa, Sanjeev and Manek!

# Dancing Robot?
In one of my second year computer engineering course at UBC, CPEN 291, I had to 
make a dancing biped robot as one of my assignment. This was a fun little funky 
project that helped us gain familiarity working with microcontrollers (ItsyBitsy)
and interfacing differnt sensors and I/O components (sonar, keypad, RGB lights..) 
with the microcontroller. It also help me gain a better understanding and familiarity
with Python. 

## What it does
There are many functionalities of the robot, all of which are listed and explained below:

- **Dance**  
The robot can perform 6 different dance moves:
    1. Waddle: The robot flaps its feet up and down similar to how a penguin waddles
    2. Pop-Step: The robot rotates its feet inwards and outwards in a pop and step sort of fashion, hence the name.
    3. Ballerina: The robot rotates its legs and performs a tip toe sort of action. The robot then proceeds to rotate and kick at the end.
    4. High-Knees: The robot brings its legs up and down one by one, similar to a high knees exercise.
    5. Excite: This move performs several kicks back to back, switching between the right and left legs.
    6. Shuffle: The robot performs a simple shuffle by turning its legs left and right several times.

- **Music**  
The robot can also play certain pre-programmed songs (even during dances) using the peizo-buzzer that we wired up:   
    1. The Anthem
    2. Mario: Super Mario Bros Theme Song
    3. Stranger Things: Stranger Things Theme Song
    4. All Star: All-Star by Smash Mouth Chorus
    5. Tetris: Classic Tetris Game Theme Song
    6. Fortnite: Fortnite Default Dance Song

- **Display**  
The robot has a small 1-inch LCD display that displays a menu that makes accessing the dances and music a lot easier

- **Keypad**  
The robot has a 6 key keypad that takes in user input, it requires a password to start! (hint: 1234)

- **Sonar**  
The robot has an ultrasonic sensor that detects walls and motion and stop any dance move if it detects an object too close

## How we built it
The professors provided a 3D printed robot chassis for us to house all the components in. We used 2 breadboards to house the 
wires for all the components of the robot. A detailed circuit schematic is below created using the Fritzing software.  
![alt text](https://arnoldying.github.io/assets/img/fritzing1.png "circuit schematics")

## Challenges we ran into
There were lots of wiring issues for interfacing with the ItsyBity, the microcontroller
that we use. Since we want to include as many feature as we can there weren't enough ports
on the ItsyBitsy for us to use.  

## Accomplishments that we're proud of


## What we learned


