---
layout: default
title: "Project 1: EMS Station"
---

# Project 1: EMS Station
## What you were asked to build:
What we were supposed to build was an EMS Station, a project that has a traffic light, a garage door, and an alarm playing when an emergency comes in. We were supposed to build and design a garage and a traffic light.
## What the EMS Station is supposed to do:
The EMS Station is supposed to have a traffic light and a garage respond to an alarm, opening it for the firetruck and then closing it after as well as the sprite reacting to which costume it needs to have for the specific emergency.
## What real-world problem the system represents:
The system represents a real fire truck having to quickly cross traffic during an emergency, the traffic light makes sure the fire truck can get in and out safely.
## What the finished system should accomplish:
The finished system should allow the garage door to open when the alarm sounds, and then close shortly after the truck leaves. It should have the traffic light flashing for the garage as well.



## How you planned your project:

<img width="620" height="341" alt="Screenshot 2026-10-22 4 18 48 PM" src="https://github.com/user-attachments/assets/635d7d14-ac93-4c16-9509-a08ea9756ba5" />
At first, I wanted the garage door to open like in the sketch above, but during the design, I realized a different way of opening it and decided to change it to open directly up instead.


## Design decisions
The traffic light was 3D printed into a stand up every day traffic light.
The garage door works by using a position servo to have the door open vertically, when the alarm plays, the sound goes to the position servo, giving the code to move it and make the garage door open and close.
How I made the servo connect to the garage door was use a screw to put into the cardboard garage door, and then I put the screw into the position servo, which allowed the servo to move the garage.
I placed the sound sensor next to the sensor which connects to the computer.
I also placed the light sensor near the sensor.




## Build process

<img width="1239" height="600" alt="image" src="https://github.com/user-attachments/assets/9b086bd4-0ba4-40d3-9a3c-7f213e63be98" />

The code process here had a problem, the sprite would not change into the costume after interacting with the places on the stage.

<img width="475" height="354" alt="image" src="https://github.com/user-attachments/assets/577b80f6-7911-4c9c-bf7e-990a0286efa8" />

After fixing the code, the project allowed the sprite to change into the correct costumes after interacting with the places on the stage.

<img width="475" height="354" alt="image" src="https://github.com/user-attachments/assets/42757886-009d-4f42-912c-5a6c79f6076c" />
<img width="475" height="354" alt="image" src="https://github.com/user-attachments/assets/4383cbc5-f44e-411d-af69-92400e2643f7" />
More examples of the costumes working.

<img width="657" height="556" alt="image" src="https://github.com/user-attachments/assets/7c31fb51-41b0-409e-b533-ce7435f228c4" />

This is the finished code after trial and error.





## Code
<img width="457" height="213" alt="image" src="https://github.com/user-attachments/assets/148d58de-8646-4a1c-9b70-7ef0f70113e5" />
<img width="557" height="246" alt="image" src="https://github.com/user-attachments/assets/08b1978e-64ee-44d9-a737-ef7df7b2e2f7" />
<img width="457" height="201" alt="image" src="https://github.com/user-attachments/assets/ead566c4-7d06-4618-aaee-c187c677e08b" />

The code above allows the sprite to change into a specific costume after touching a specific area on the stage.
For example, after Alonzo touches the fire, its costume changes into "AlonzoHose".

<img width="348" height="147" alt="image" src="https://github.com/user-attachments/assets/30889c17-b4eb-4c5b-81d6-03af1746c859" />

After an emergency sounds, an alarm plays out until the until is met, as shown above.

<img width="315" height="147" alt="image" src="https://github.com/user-attachments/assets/783bc7bf-4831-43c6-ae0b-7df4802509cb" />

When the if statement is met, the position servo moves the specific direction, which here is -90 degrees.

<img width="357" height="257" alt="image" src="https://github.com/user-attachments/assets/a8cf453d-297b-4da9-896e-48fb53aba8de" />

When the alarm plays, the LED lights turn on, flashing every 1 second.

<img width="235" height="166" alt="image" src="https://github.com/user-attachments/assets/8944213b-a3b5-42bc-87fc-45cbf23f380d" />

Alonzo, the sprite, resets, which means it goes back to the center and removes any unorignal costume, going back to the normal one.




## Snap! EMS Station project link:
https://snap.berkeley.edu/snap/snap.html#present:Username=analeyah&ProjectName=EMS%20Project%20-%20New%20Starter%20Code%204%2024

## How the system works
The computer recieves the information when the code begins to run, when an emergency happens, the sound sensors sound as well as the light sensor. When an emergency has occurred, the computer uses to code to know what to do. Since the code is written to play a sound when "emergency" happens, the computer does exactly that. The code is also written for the garage door and traffic light, the position servo acts as the movement for the garage door in the actual design, so when a condition is met, the computer runs the expected code, as well as the same for the traffic light. The system controls the costumes, the sound, the position servo, LEDS.

When an emergency occurs, the code for the sound plays out first, to the traffic light switching to the right color, to Alonzo touching a specific area and changing into a specific costume, to the garage door opening, and then when the alarm stops, the garage closes again, going back to no alarm and the traffic light back to normal.





## Testing and debugging
Two problems that occured during my project were Alonzo not changing into the costumes even after the condition was met and then the garage door not opening correctly after using the position servo.

## What happened?
For the code with the costumes and Alonzo, when Alonzo touched "Medical" or "Fire", the costume did not change into the correct one and instead stayed the same. For the garage door, after putting in a screw into the cardboard and placing the position servo where I thought would work, the cardboard did not open up.

## What was causing it?
I believe what was causing Alonzo to not change into the correct costume was where the code was located, in the stage and not in the places, "Medical" or "Fire". I believe what was causing the garage door to not open correctly was where the position servo was located with the cardboard.

## What tests and changes happened?
For Alonzo, I changed where the code was and put it into the correct place, for the garage door, I tried out different places where the position servo was.

## What happened after the change?
For Alonzo, my solution worked out after a few trial and errors, for the garage door, I could not figure it out after many tries.

## What was learned?
I learned for future references, to make sure to check where a specific code is happening so I can fix it and to test multiple solutions, seeing what works and what does not work.







## Final product:
[Screen recording 2026-10-22 5.18.45 PM.webm](https://github.com/user-attachments/assets/1cbf7b81-82fc-4936-9c01-713b452deedd)












