---
layout: post
title: "Dancing Biped Robot"
author: "Arnold Ying"
categories: project
image: dancingRobot1.png
---

## Source code: Unavailable
I made a dancing biped robot!

# Dancing Robot?
In one of my second year computer engineering course at UBC, CPEN 291, I had to 
make a dancing biped robot as one of my assignment. This was a fun little funky 
project that helped us gain familiarity working with microcontrollers (ItsyBitsy)
and interfacing differnt sensors and I/O components (sonar, keypad, RGB lights..) 
with the microcontroller. The professors provided a 3D printed robot chassis for 
us to house all the components in. 

## What it does
Using the Google Cloud Firebase API, we upload course info through our extension, which then parses for courses and assignments, and any deadlines and tasks with which they are associated. We then display a dynamic to-do list which allows the client to see what tasks they have left. If the deadline is approaching soon, a reminder text will be sent to the client, preventing their procrastination, so that they never miss a beat.

## How we built it
**Front End:**
We used a combination of HTML, CSS, and Javascript to make a friendly interface that can also send desktop notifications. It lists tasks based on deadlines for each course and allows for completed tasks to be removed from the to-do list and archived in our database.
**Back End:**
Google Cloud's Firestore API (Firebase) to take data from course websites and create tasks with deadlines for the client automatically.
Use of the Google Cloud Natural Language API was attempted, but will likely be used in future iterations to simplify the parsing of websites and allow for the added functionality we envision in the future, as stated in the "What's next" section below.

## Challenges we ran into
Almost every step of the way, we were challenged by software and languages that are practically new to us, so I think what we can take away from this experience is our team's determination to overcome these challenges and the professional way in which we self delegated tasks for an orderly development culture.

## Accomplishments that we're proud of
We are proud to have created a solution to a problem that many in our cohort face on a daily basis. Now that we are starting on the path to self-organization, we may better address larger and larger social issues in the Hackathon's to come.

## What we learned
We learned a great deal about plugin development and database polling, which we hope will lead us down the path of further improvement as we continue learning continuously.  

## What's next for Assignment Scheduler
We are looking at adding functionality to show empty rooms for studying based on when courses take place. Additionally, we are looking at using the Natural Language API from Google Cloud to interpret assignment descriptions to create a rubric of deliverables based on their overall salience to the document.
