## REQUIREMENT
The use of transportation vehicles has expanded dramatically over the world in recent years. As a result, it is critical to strengthen the safety features of automobiles. It is critical to conduct a survey and study to detail the automatic operated wiper in order to achieve and meet the above notion. Windshield Wipers are essential for ensuring the driver's safety while driving. As a result, the goal is to build a system that controls an automatic operated wiper that is controlled by an electronic sensor. We explore numerous sorts of sensors used in wiper automation in the research paper.

## Swot Analysis
 #### Advantage
 * Provide clear vision to driver in rainy season
 * Help to remove dust and water from wind shield
 * Easy to operate
 * 
 ### Disadvantage 
 * Regular maintaince required
 * changing of wiper quarterly
 * Not fully automatic
 

 
### 4'W and 1'H
##### What 
Wiper control system.
##### Where
It can be used in CAR for controlling the wiper.
##### When
It can be used when there is a need of wiper in the vehicles.
##### How
It work on stm3, Ignition key is attach to the stm32 and as we start stm32 is ready to work and follow the instructions of Key.

### Table no : High level Test plan
| Test ID | Description | Exp I/P| Exp O/P|Test case
| --- | --- | --- | ---- |-----|
| T_01 |Ignition key at ACC |User button is pressed & held for 2 sec| Red Led is ON |Pass|
| T_02| Wiper is ON| User button is Pressed | Blue,Green & Orange led is ON |Pass|
| T_03 | Wiper is OFF|  User button is Pressed| Blue,Green & Orange led is OFF |Pass|
| T_04|Igintion key at lock |User button is pressed & held for 2 se| Red Led is OFF|Pass|


### Table no : Low Level test plan
| Test ID | Description | I/P|  O/P|
| --- | --- | --- | ---- |
| L_01 |  user button press for 2 sec| red Led on| wiper on|
| L_02| single press the button|Blue,Green,Orange Led glow|Wiper Rotates at different Hz(2,4,&8)|
| L_03 |  user button press for 2 sec| red Led off wiper off|
