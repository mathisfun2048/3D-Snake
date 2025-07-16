---
title: "Snake 3D"
author: "Arya"
description: "A 3-D port of snake in the third dimension"
created_at: "2025-07-11"
---


# July 15

## 1AM -> 6AM (6 hours)

Started framing the implementation of the music software. Did not have the internet, so this process took a bit longer than normal. 

This is going to be added to the runtime firmware and does the following:

- adds death sound effect! This makes it easier for the user to know when they died
- adds music to make the game feel less boring
- the above point also helps mask the sound of the motor

This is code so I don't know what picutres to attach

<img width="97" height="188" alt="Screenshot 2025-07-16 at 6 19 04 PM" src="https://github.com/user-attachments/assets/4387171b-5b15-4630-83a0-73dd3e84d87a" />



# July 16

## 1AM -> 8AM (7 hours)

Thought a pcb would make this look more slick. 

During the processes, I found out that the code I wrote was pretty useless so I started from scratch. 

I researched differnt audio modules, and settled on a MAX98357 which integrates a digital to analog decoder and an amp. yay! With this, ill be able to plug my speaker directly into this module. 

For my speaker, I chose the lowest cost 8 ohm speaker haha


<img width="500" height="573" alt="Screenshot 2025-07-16 at 4 08 24 PM" src="https://github.com/user-attachments/assets/8e604619-3b86-4e49-b289-991c301e1c87" />

<img width="500" height="617" alt="Screenshot 2025-07-16 at 4 08 44 PM" src="https://github.com/user-attachments/assets/9b5f5f1f-e551-4443-a649-25884fae1b33" />


<img width="500" height="420" alt="Screenshot 2025-07-16 at 4 09 05 PM" src="https://github.com/user-attachments/assets/aa128006-a42d-425d-9ec1-5804bb26757a" />

## 3PM -> 5PM (2 hours)

polished the PCB and did a quick cad case to hold the compute box together. Left big openings so the wires can flow through. 

<img width="2732" height="2048" alt="full case together" src="https://github.com/user-attachments/assets/3ce42acf-db87-4513-90be-bf2cd0cf599b" />

## 5PM -> 6PM (1 hour)

Polished the code for audio.... hopefully it works!


<img width="1156" height="539" alt="Screenshot 2025-07-16 at 6 18 46 PM" src="https://github.com/user-attachments/assets/8a4ec67b-c185-4b6d-ba9c-f22d4d509999" />




