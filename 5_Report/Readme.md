## Automatic burglar alert,cooling,Lighting and Drapes control system
## Introduction
This Project is an Automatic Burglar alert, Cooling, Lighting and Drapes Control system, 
(A.B.C.L.A.D.S) which will be useful for automatic lighting and cooling control system in home and when 
we are not in home we can activate Buglar alarm which will give a buzz noise alerting people around 
the home by buzzing noise when someone breaks the Door, When the user sets a required temperature 
and light intensity this system will automatically controls the Room temperature and Light intensity
## Features

• It shall show how much %of drapes are opened according to room light intensity

• It shall dim/increase light intensity according to room light intensity variation

• It shall change the speed of fan accordingly to the temperature of the room

• When we are not at home it shall be able to sense if door is closed or broken and shall turn on a buzzer
## State Of Art

The main focus point here is the controlling the Home without even touching a single button

• And also securing our home with a reliable Burglar system 

• Now this two features are combined and made into one product i.e. A.B.C.L.A.D.S

• As the world PACE-FORWARD our technology needs to catch up to the world
## 5 W's and 1 H

![5W1H Method](https://user-images.githubusercontent.com/101419044/164878187-0ffda158-d275-4ab5-b1f6-48d1f6bada41.png)

## Swot Analysis

![b4234c072df14c588b8ce6fee341c16c-0001](https://user-images.githubusercontent.com/101419044/164878393-06b4f979-03c3-4e29-a20a-217cb1c72d70.jpg)

## Requirements

## HIGH LEVEL REQUIREMENTS

| ID   | High Level Requirements                                                                              |
|------|------------------------------------------------------------------------------------------------------|
| HLR1 | It shall control Lights, Fan Automatically when user selects desired light intensity and Temperature |
| HLR2 | It shall control Drapes Automatically user selects desired light intensity                           |
| HLR3 | It shall Sound buzzer when door is open and people are not at home                                   |
| HLR4 | It shall display How much %of Lights         




## LOW LEVEL REQUIREMENTS

| ID     | LOW LEVEL REQUIREMENTS H1                                                                  | ID      | LOW LEVEL REQUIREMENTS H2                                                        |
|--------|--------------------------------------------------------------------------------------------|---------|----------------------------------------------------------------------------------|
| LLR1.1 | According to the values of LDR and User light intensity shall control the drapes poosition | LLR 2.1 | According to the values of LDR and user light Intensity shall control the lights |
| LLR1.2 | According to the values of Thermistor and user temeperature shall control speed of fan     | LLR 2.2 | Position of drapes shall be controlled by stepper Motor                          |












| ID     | LOW LEVEL REQUIREMENTS H3                                          | ID     |  LOW LEVEL REQUIREMENTS H4                                       |
|--------|--------------------------------------------------------------------|--------|------------------------------------------------------------------|
| LLR3.1 | The 555 Timer circuit shall send PWM signal to speaker             | LLR4.1 | It shall be able display the %of LED according to value of LDR   |
| LLR3.2 | The microcontroller shall active buzzer and turn off other systems | LLR4.2 | It shall be able to convert integer to % for displaying % of LED |
## Block diagram
![BlockDiagram](https://user-images.githubusercontent.com/101419044/164878445-ee3bef7f-203e-4ab0-abe7-7a2a8010e86e.png)
 
## Design
 
## Behavioural Diagram

High Level  Flow chart behavioural diagram

![HLFBD_without_BG](https://user-images.githubusercontent.com/101419044/164682945-fc0b1364-6246-4cd9-bac3-3a37cd5c345e.png)


Low Level Flow chart behavioural diagram


  ![LLFBD_without_BG](https://user-images.githubusercontent.com/101419044/164683428-14c64751-0a10-4bca-885a-628d94ca8987.png)

## Structural diagram
High Level UML Use case structural  diagram
  
![HL_UML_withour_BG](https://user-images.githubusercontent.com/101419044/164683519-5625de45-18b7-464b-9565-5e7a743c4a6d.png)

Low level UML use case structural diagram


![LL_UML_without_BG](https://user-images.githubusercontent.com/101419044/164683635-b594b264-739b-456d-bb8d-c1dba0863f5e.png)

## Assumptions
• The Drapes are fully open at start of the system

• Initial Room intensity is same through out the end of the code (200 lux or 150 lux or 100 lux or 50 lux 
or 0 lux), Since we cannot actually update LDR in real time

• Door sensor is replaced by push button, Since it also gives 0 or 1 values at output
## Applications
• The scope of this project is vast in the area of home automation

• Home security and when people want automatic home lighting and cooling system along with Intruder 
alert

• In factories and function halls

• In Schools and Collages to save energy
## Future add-ons
• The % of drapes open should be displayed on LCD

• SSD 1306 should instead of existing LCD

• Addition of Bluetooth module

• S.O.S to mobile in case of intruder 

• A.C instead of FAN

## Output

![AutomationMode (1)](https://user-images.githubusercontent.com/101419044/164878822-850d2aa3-23a9-4da7-b0c9-e1af3a23c68b.png)

![BurglarMode](https://user-images.githubusercontent.com/101419044/164878828-035a5fae-a2cd-4f35-9c47-4d7d0b0e3f0a.png)


