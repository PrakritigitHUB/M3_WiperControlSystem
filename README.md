# M3_WiperControlSystem

The concept of this wiper system is similar to other conventional wipers, yet this system will be upgraded to an automatic control system by using a controller. When water hits a dedicated sensor located on the windscreen, it triggers the wiper motor to move. It is not detected by sensor, the wiper will automatically stop. This will help the driver to give more concentration and reduce the car accident probability.

## Folder Structure
|FOLDER|DESCRIPTION|
|:-----|:----------|
|0_Abstract|Brief on project|
|1_Requirements|Documents detailing requirements|
|2_Design|Structural and Behavioural UML diagrams|
|3_Implementation|All the code is written here|
|4_TestPlan|Documents with test plans and outputs|
|5_Report|Generated Report|
|6_Others|All the images and diagrams|

## Working principle
* Assume that the automobile is the microcontroller. 
* If the push button is long pressed , the first led (red) will turn on. Hence, the engine starts.
* Clicking the push button again, the wiper will start, and the second led (blue) will turn on, moving at a desired rate. 
* If the button is clicked again, the third led (green) will turn on, and the wiper's speed will be increased in comparison to the previous one. 
* With the fourth press,  the fourth led (orange) will turn on, and the wiper speed will be increased in accordance with the previous one. 
* The microcontroller (vehicle) is turned off after the fifth press which would a long press.

## Advantages:
* Cost-effective
* It is quite simple to use.
* less energy is consumed.
* extremely simple to install.
* Individual rain sensors are fairly inexpensive.


## Disadvantages:
* When water falls squarely on the rain sensor, the mechanism activates.
* The entire system cost rises when more components are required.
* Rain sensors must make a decision within a few minutes to avoid erroneous detection of rain.

## Output
### user button and hold it for two seconds, ENGINE ON STATE

![alt text](https://github.com/PrakritigitHUB/M3_WiperControlSystem/blob/main/6_Output/ENGINE%20ON.png)

### WIPER SPEED LOW 

![alt text](https://github.com/PrakritigitHUB/M3_WiperControlSystem/blob/main/6_Output/WIND%20SPEED%20LOW.png)

### WIPER SPEED MEDIUM

![alt text](https://github.com/PrakritigitHUB/M3_WiperControlSystem/blob/main/6_Output/WIND%20SPEED%20MED.png)
### WIPER SPEED IS HIGH

![alt text](https://github.com/PrakritigitHUB/M3_WiperControlSystem/blob/main/6_Output/WIND%20SPEED%20HIGH.png)

### user button is pressed and held for 2 seconds, Engine off state
![alt text](https://github.com/PrakritigitHUB/M3_WiperControlSystem/blob/main/6_Output/ENGINE%20OFF.png)



##  Code Badges
[![Build-Linux](https://github.com/PrakritigitHUB/M3_WiperControlSystem/actions/workflows/Build%20on%20Linux.yml/badge.svg)](https://github.com/PrakritigitHUB/M3_WiperControlSystem/actions/workflows/Build%20on%20Linux.yml)

[![Cppcheck Analysis](https://github.com/PrakritigitHUB/M3_WiperControlSystem/actions/workflows/Cppcheck%20Analyse.yml/badge.svg)](https://github.com/PrakritigitHUB/M3_WiperControlSystem/actions/workflows/Cppcheck%20Analyse.yml)

[![Codacy Badge](https://app.codacy.com/project/badge/Grade/df976efff818448c8b1cd2a98b6bdc3b)](https://www.codacy.com/gh/PrakritigitHUB/M3_WiperControlSystem/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=PrakritigitHUB/M3_WiperControlSystem&amp;utm_campaign=Badge_Grade)

![Code Score](https://api.codiga.io/project/33440/score/svg)

![Code Grade](https://api.codiga.io/project/33440/status/svg)
