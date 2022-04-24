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
