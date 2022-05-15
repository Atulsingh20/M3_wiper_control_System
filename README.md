## Code Quality & Code Grade
![Code Quality Score](https://api.codiga.io/project/33567/score/svg) ![Code Grade](https://api.codiga.io/project/33567/status/svg) ![Codacy Badge]([![Codacy Badge](https://app.codacy.com/project/badge/Grade/3c69e6b9cc8941468784ec8efa6dfea6)](https://www.codacy.com/gh/Atulsingh20/M3_wiper_controller/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=Atulsingh20/M3_wiper_controller&amp;utm_campaign=Badge_Grade)) [![Codacy Security Scan](https://github.com/Atulsingh20/M2_CAR_TEMPERATURE_CONTROL/actions/workflows/codacy.yml/badge.svg)](https://github.com/Atulsingh20/M2_CAR_TEMPERATURE_CONTROL/actions/workflows/codacy.yml)

# CAR TEMPERATURE CONTROL
\# M3_wiper_control_System
# INTRODUCTION
The automotive industry has spent the last two decades vigorously researching ways to use modern computing and electronic improvements in the development of vehicle safety, dependability, and entertainment technology. With a growing number of distractions, automated rain-sensing wiper systems become an even more tempting feature, as they attempt to reduce the amount of time the driver has take his or her hands off the wheel. Most classic systems can operate at both intermittent and variable speeds. The typical wiper system, on the other hand, necessitates constant driver attention when altering the wiper speed. Traditional windshield wiper speed changes with the passage of time and the speed of the vehicle. Because manual wiper adjustment diverts the driver's attention, it may be a direct cause of accidents. 
# OBJECTIVE OF THE PROJECT
* Windshield wipers may be a little component of your vehicle, but they have a significant impact on your driving and overall safety.
* At the touch of a button, they remove rain, snow, dirt, pollen, frost, and other debris fast and smoothly!
* The wiper arms are moved across the windshield by the windshield wiper motor. The metal or hard plastic arms pull a thin rubber (or silicone) blade over the windshield to clean water from the lens, allowing you to see the road better.
* Wiper blades break, rip, and lose their flexibility and functionality with time. Wipers are harmed by a variety of factors, including road grit, bird droppings, severe temperatures, and UV light.
# BASIC COMPONENT OF WIPER CONTROLLER
## HARDWARE
* STM32F407
* LED (GREEN,RED,BLUE,ORANGE)
* SWITCH/ PUSH BUTTON
## SOFTWARE
* STM32 SOFTWARE DEVLOPMENT TOOL
* QEMU
#  FUNCTIONALITY
* When the ignition is on and the button/ switch is pressed for 2 sec the system is activated 
* The Red colour LED start glowing and indicate the system is in active .
* The diffrent coloue of LED i.e Green , Orange, Blue is used to indicate the speed of wiper .
* The  Wiper Moving at 1 H,2Hz,3Hz.
* while the button is pressed again for 2 sec than the Red lED stop glowing and indicate that the system is off.
# SIMULATION
Driving a vehicle is complicated in harsh weather condition without using glass wiper system. Controlling the wiper speed based on the change in weather condition is one of the research area in automotive industries now a day. Recently, the wiper speed is adjusted manually controlled by the driver. Dc motors are used to drive the wiper system based on feed forward techniques. In this paper a separately excited Dc motor is designed and controlled using robust control method to improve the feed forward wiper system performance.
# Test Case
### Table
| Test ID | Description | Exp I/P| Exp O/P|Test case
| --- | --- | --- | ---- |-----|
| T_01 |Ignition key at ACC |User button is pressed & held for 2 sec| Red Led is ON |Pass|
| T_02| Wiper is ON| User button is Pressed | Blue,Green & Orange led is ON |Pass|
| T_03 | Wiper is OFF|  User button is Pressed| Blue,Green & Orange led is OFF |Pass|
| T_04|Igintion key at lock |User button is pressed & held for 2 se| Red Led is OFF|Pass|\
