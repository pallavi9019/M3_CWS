
# Requirements
## Introduction
Today’s car wipers are manual systems that work on the principle of manual switching. So here we propose an automatic wiper system that automatically switches ON on detecting rain and stops when rain stops. Our project brings forward this system to automate the wiper system having no need for manual intervention. For this purpose we use rain sensor along with microcontroller and driver IC to drive the wiper motor. Our system uses rain sensor to detect rain, this signal is then processed by microcontroller to take the desired action. The rain sensor works on the principle of using water for completing its circuit, so when rain falls on it it’s circuit gets completed and sends out a signal to the microcontroller.
## Research
  CAR WIPING SYSTEM
  
The source code is to be compiled in STMcubeIDED. This CAR WIPING SYSTEM in EMBEDDED C is not designed to run on the Turbo C versions. The source code for this mini project is around 1000 lines, so I didn’t want to display it here.
-------------------------------------------------------------------------------------------------

## Cost and Features
Our CAR WIPING SAYSTEM put learning. Your knowledge will be tested regarding a variety of objects. 


## Defining Our System
* According to WHO, more than 1.25 million people die every year because of road crashes and mostly in rainy seasons. People end up dying because of small mistakes. Here we have forwarded an attempt to reduce that number. The project is especially suited for car.
## SWOT ANALYSIS
![image](https://github.com/pallavi9019/M1_March_2022/blob/59e84a171d7bcf3bd502d74067d43659d4439241/1_Requirements/SWOT%20analysis/SWOT%20analysis%20(1).png)

# 4W&#39;s and 1&#39;H

 ## 4 W'S
 # WHAT IS WIPER SYSTEM
  Windscreen wipers are necessary for maintaining sufficient view for the driver, especially in modern high-speed cars.
 # WHY WIPER SYSTEM
   To keep the windscreen clean enough to give adequate view at all times.
 # WHEN SHOULD USE WIPER SYSTEM 
  The windshield wipers remove rain and snow from the windshield, while the headlights improve visibility at night.
 # WHO DISCOVERED WIPER SYSTEM
  Mark Anderson invented on 1902
   
  

# Detail requirements
## High Level Requirements:

| ID | Description | Status (Implemented/Future)
|:---:|:---:|:---:|
|HLR-1| User shall be able to select the different inputs the user need to get values when led blinks. |Implemented|
|HLR-2| System ask choice to continue. |Implemented|
|HLR-3| user shall be able to get different speed. |Implemented|
|HLR-4| user shall be able to get displayed values. |Implemented|
|HLR-5| user shall be able to get the history of the Car wiping system. |Future|


## REQUIRED COMPONENTS
 STM32 CUBE IDE
# COMPONENTS
  STM32F4O7VG MICROCONTROLLER BOARD
## DESCRIPTION
# STM32F407VG
 The STM32F407  Kit takes advantage of the high-performance STM32F407 microcontrollers' capabilities to make it simple for users to create audio-based applications. It comes with an ST-LINK embedded debug tool, an ST-MEMS digital accelerometer, a digital microphone, an audio DAC with integrated class D speaker driver, LEDs, pushbuttons, and a USB OTG micro-AB connector.Ethernet connectivity, an LCD display, and other features have been added to the STM32F4 DISCOVERY kit. The STM32F405xx and STM32F407xx families are built around the high-performance Arm® Cortex®-M4 32-bit RISC core, which runs at up to 168 MHz.
 # FEATURES OF STM32F407VG MICROCONTROLLER
  * In a LQFP100 package, the STM32F407VGT6 microcontroller has a 32-bit ARM Cortex-M4 with FPU core, 1-Mbyte Flash memory, and 192-Kbyte RAM.
  * On-board ST-LINK/V2 or ST-LINK/V2-A on STM32F4 DISCOVERY (old reference) or STM32F407G-DISC1 (new order code)
  * USB ST-LINK with three separate interfaces and re-enumeration capability.
  * Virtual Com port Debug port (with new order code only)
  * Large-scale storage (with new order code only)
  * Board power is supplied through USB or an external 5 V supply source.
  * 3 V and 5 V external application power supply
 # USES
  * This Microcontroller is utilised in printing and scanning machines ,heat ventilation, air conditioning, and security systems. 
  * This module can be found in a variety of household products.
 # WORKING PRINCIPLE
  Assume that the automobile is the microcontroller. If the button is hit, the first led (red) will turn on, Clicking again  the wiper will start, and the second led (blue) will turn on for a desired rate. If the button is pressed again, the third led (green) will turn on, and the wiper's speed will be increased in comparison to the previous one. The fourth press will turn on the fourth led (orange), and the wiper speed will be increased in accordance with the previous one. The microcontroller (vehicle) is turned off after the fifth click.

 

## BLOCK DIAGRAM
![image](https://user-images.githubusercontent.com/86293096/168312514-b4ee6ec3-75cc-402f-b1e7-7f81c41a5ab1.png)


## Flow chart
![image](https://user-images.githubusercontent.com/86293096/168312042-11b40882-521d-4521-b64c-5120ed348bff.png)



# TEST CASES and Corresponding Output

## High Level Test Cases
| Test ID | Description | Exp.i/p | Exp.o/p | Actual o/p | STATUS |
| --------|:------------|:--------|:--------|:-----------|:-------------|
| 1 | check if the BUTTTON is pressed  | program execution | Microcontroller/Engine starts | LED ON(RED)| PASS |
| 2 | check if the BUTTTON is pressed  | program execution | WIPER starts | LED ON(BLUE)| PASS |
| 3 | check if the BUTTTON is pressed  | program execution | WIPER starts | LED ON(GREEN)| PASS |
| 4 | check if the BUTTTON is pressed  | program execution | WIPER starts | LED ON(ORANGE)| PASS |
| 5 | check if the BUTTTON is pressed  | - | Microcontroller/Engine stops | LED TURNED OFF| PASS |









## Low Level Test Cases
| Test ID | Description | Exp.i/p | Exp.o/p | Actual o/p | STATUS |
| --------|:------------|:--------|:--------|:-----------|:-------------|
| 1 | check if the BUTTTON is pressed  | program execution | Microcontroller/Engine starts | LED ON(RED)| PASS |
| 2 | check if the BUTTTON is pressed again | program execution | WIPER starts and speed of wiper is slow | LED ON(BLUE)| PASS |
| 3 | check if the BUTTTON is pressed again | program execution | WIPER starts and speed of wiper is moderate | LED ON(GREEN)| PASS |
| 4 | check if the BUTTTON is pressed again | program execution | WIPER starts and speed of wiper is good | LED ON(ORANGE)| PASS |
| 5 | check if the BUTTTON is pressed again | - | Microcontroller/Engine stops | LED TURNED OFF| PASS |

![Screenshot (413)](https://user-images.githubusercontent.com/86293096/168319869-e9eee2a3-a03a-489a-9316-c9adf32006fa.png)
![Screenshot (410)](https://user-images.githubusercontent.com/86293096/168320000-7e847822-b850-4221-8258-1cc67e790126.png)
![Screenshot (412)](https://user-images.githubusercontent.com/86293096/168320056-9b1db7f5-331a-449c-8047-217ad0381432.png)
