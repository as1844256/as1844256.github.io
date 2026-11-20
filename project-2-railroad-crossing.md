---
layout: default
title: "Project 2: Railroad Crossing"
---

# Project 2: Railroad Crossing
## Project Overview: What are you building, and what should it do?
We were supposed to build a crossing stop, one where it uses a position servo, cardboard, lights, distance sensors, sound sensors, and crossing data to stop traffic whenever a train passes or does not pass by, in which the cardboard is supposed to go up, the lights are supposed to flash, the data is supposed to be inputed into the crossing data, and the sound is supposed to play when the train does pass by.

## Planning & Design: Pictures of sketches, plans, and explanations of your design decisions.
<img width="640" alt="image" src="https://github.com/user-attachments/assets/ba36cb00-49e0-4b3c-9e08-433d726075bd" />
: When I started building the cardboard for the position servo so it could stop traffic whenever a train passed by, the cardboard was too wide, resulting in it not lifting up right and being too blocky. I fixed it after testing it out by cutting a side off, where it was now long instead of wide, and then it turned to the right way, which worked.

## Build Process: Pictures or videos showing your progress, with captions explaining what you did.
<img width="599" alt="image" src="https://github.com/user-attachments/assets/a9eebc2f-b480-408e-a417-6eb071aa25b3" /> 
: To get the actual crossing data started and working for the train, I had to code a working data collection that has the current date, time, and speed.

<img width="611" alt="image" src="https://github.com/user-attachments/assets/32286947-64ee-40ed-8d32-e9266484cd49" />
: Another example of the coded data collection.

<img width="599" alt="image" src="https://github.com/user-attachments/assets/09dc4f21-bcba-41f8-888f-87f9bec4acee" />
: While I was building, I also had to connect to distance sensor to the hummingbird input, which helps to sense where the cardboard was and further connects to what effect happens.

## Code: Screenshots of important Snap! code with explanations of how it works.
<img width="594" alt="image" src="https://github.com/user-attachments/assets/216c3807-b1bc-4050-941c-eb7665ad554c" />
: This code allowed the blocks inside of it to run whenever distance (the train) was sensed. When the train passes by and the distance is under 18, the position sensor gets to 0, allowing the cardboard to drop, the sounds to sensor, the lights to go on, and if the train does not pass by and the distance is over 18, the position sensor gets to 90, and stops everything else.


<img width="360" alt="image" src="https://github.com/user-attachments/assets/e247a3fd-fe09-4adb-bb06-855ce93f43f5" /> 
: This code, whenever the hummingbird board is connected, allows the distance number to be displayed on the program, which can help to see how far or close something is whenever you run into a problem, it is mainly used to detect the distance of the train whenever it is close, so that the cause and effect can happen.


## Snap! Project Link: A working link to your saved Snap! program.
https://snap.berkeley.edu/snap/snap.html#present:Username=analeyah&ProjectName=U2L2R%20Railroad%20Crossing

## How It Works: Explain the inputs (sensors), processing (code/decisions), and outputs (lights, servo, etc.), including the timetable.
: The input distance sensor is what makes the whole project work. It senses how close something is, and then can perform an action based on how close or how far away it is. When the train passes by, the distance sensor works as the "if" and "what". The code mainly consists of "if" blocks, notes, LED, and position servo. The "if" block processes information and then if that "if" is true, then it does the next action. The notes are a sound that plays whatever specific notes you want. The LED and position servo have lights change to different colors and move to a specific percentage. The timetable is also important, allowing information to be stored or taken away when an action is true, like the distance sensor sensing the train passing, and the time table putting that information in.

## Testing & Debugging:
: Two problems that came up were when the train passed by, the information would not go into the list. I tried to add the code into the other "if" instead of it being by itself and it finally added information into the list. Another problem that occured was when the LEDs would not flash. I fixed it by rearranging the code, adding "wait" blocks in between LED blocks.

## Final Product: Pictures and a demonstration video showing what your system does.
<img width="599" alt="image" src="https://github.com/user-attachments/assets/94d30eb7-9c94-4591-9940-eb5040d9a7b7" />

https://drive.google.com/file/d/1l_nht4oRg8Rpl7BeXPkUNUeeNH037vJM/view?usp=sharing


<video width="100%" controls>
  <source src="IMG_3631 (3).mov" type="video/mp4">
</video>

## Reflection:
: I learned how to import "if" statements with the distance sensor, which could add information when the train passed by. What was challenging was trying to create the list and trying to fix the information being put into the list after it would not do it multiple times.







