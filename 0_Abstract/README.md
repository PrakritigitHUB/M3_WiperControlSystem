## PROJECT NAME
### Wiper Control System


## BRIEF ABOUT THE PROJECT
*  A wiper is a necessary component that cleans raindrops or any other liquid off the vehicle's windscreen. 
* Manual wiper activation and the operation of bringing up the wiper is difficult to manage. As a result, this method is proposed to address such issues. 

## PROJECT AIM
* The project's goals are to improve automobiles systems functioning by giving automated wiping system, to enhance the system by including a sensor and an actuator, and to create a simple software that would completely work with the system the framework.
* This proposed wiper system's principle is comparable to those of other existing conventional wipers.

## REQUIREMENTS AND WORKING
* In this project, the STM32F4xx-discovery board is used to illustrate an automobile wiper control system. 
* Most automobile wipers are controlled by a DC motor, however because the STM32F4xx-discovery lacks a motor, using LEDs this application is designed. 
* The STM32F4xx-discovery board has four LEDs and a Push Button. The colours of these LEDs are orange, green, red, and blue. A current limiting resistor connects four user LEDs to the PD12, PD13, PD14, and PD15 pins of PORTD on the Discovery board. To make a push button work with the STM32F407VG microcontroller, the GPIO pins are set as digital input pins.
* Its working is like if you push and hold the user button for two seconds (when the ignition key is positioned at the ACC),the Red LED illuminates. Furthermore, the LEDs flicker, indicating that the wipers are turned on and are moving.
