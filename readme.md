# 3-D Snake... but polished


## Description and Exigence

The basic framework of this project came from the undercity hackathon, where me and my teammates were able to scrapyard a prototype to work. This project is the same project but refined, adding a PCB to better manage wires and audio to better communicate to the user when the snake dies. Some minor software improvements have also been made (such as re-working the moving mechanism when the snake reaches the top pannel). 

Here's a pic of our prototype:
![IMG_5328](https://github.com/user-attachments/assets/f38b1276-57ad-4c49-a899-73a823bae593)


## Schematic and PCB

During prototyping, one of the hardest parts of the design was making sure all the gpio pins stayed in place! So, I made a pcb to help with wiring. 

<img width="500" height="573" alt="Screenshot 2025-07-16 at 4 08 24 PM" src="https://github.com/user-attachments/assets/8e604619-3b86-4e49-b289-991c301e1c87" />

<img width="500" height="617" alt="Screenshot 2025-07-16 at 4 08 44 PM" src="https://github.com/user-attachments/assets/9b5f5f1f-e551-4443-a649-25884fae1b33" />


<img width="500" height="420" alt="Screenshot 2025-07-16 at 4 09 05 PM" src="https://github.com/user-attachments/assets/aa128006-a42d-425d-9ec1-5804bb26757a" />


Here's the full wirings with the raspberry pi:
<img width="500" height="565" alt="Screenshot 2025-07-16 at 4 35 08 PM" src="https://github.com/user-attachments/assets/20c4acb2-331b-4110-9940-eb0f55616083" />




## Firmware

This project is coded in circuitpython to run on a raspberry pi pico. Most of the firmware was written at the hackathon, including the snake's game engine and wrapping mechanisms. With my improvements, a audio mechanism was added, playing a sound when the game is played and a death "game over" sound. Additionally, the joystick movements was revised, however, its effacaciy will only be able to be tested once I build it and get to callibrate the joystick.

## CAD

Here it is! It's pretty bare-bones because I want access to all the gpio and other pins for debugging. 

<img width="2732" height="2048" alt="full case together" src="https://github.com/user-attachments/assets/614c26f3-fb0c-445a-87ab-3c6acbf13f3e" />


Here's what the game will look like with the prototype cad we made at undercity! 

![IMG_5337](https://github.com/user-attachments/assets/3fcd43cb-fff2-459a-b5db-3cb28e87e822)



## BOM


                                                                                                                                                                                                                                                                                             |




