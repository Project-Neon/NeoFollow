# Sloth
The Neon's Line Follower Robot of 2017
<div style="align=middle"><img src ="https://github.com/Project-Neon/Sloth/blob/master/Media/Sloth.png" /></div>
<p align="center";> <b>The <strike>slowest</strike> fastest line follower in the ice age.</b> </p>

# Parts of the puzzle
* `Firmware`: Is the main firmware that controls all the functions of the robot.
* `Software`: Is telemetry software for data acquisition from the robot.
* `Eletronics`: This keeps all the information about the electronics for the line following robot ‘NoFollow’.
* `Mechanics`: Contains the STL files of the robot design.

## Firmware
The firmware project was based on the [mbed](https://developer.mbed.org/) development platform and was developed in the [Atom Text Editor](https://atom.io/) equipped with the [Platformio Extension](http://docs.platformio.org/en/latest/ide/atom.html).

### Firmware parts overview
* `main`: Controls all functions of the robot.
* `lineReader`: Read the outside sensors and check the conditions.
* `Motor`: Library for control the power and direction of the motors.
* `PID`: Configures PID control on the angular velocity of the robot.
* `QEI`: Libary for read the magnetic encoders. Available [here](https://developer.mbed.org/cookbook/QEI)
* `QTRSensors`: Library for read the line sensors. Available [here](https://developer.mbed.org/users/phillippsm/code/PololuQTRSensors/).


## Eletronics
The eletronic board was developed in the [Circuit Maker](https://circuitmaker.com/), a PCB Design Freeware. Project available [here](https://circuitmaker.com/Projects/Details/Neon-Project/NeoFollow).

### Bill of materials
| Qtd | Item | Buy | US$ |
|-----|------|-----|-----|
| 1 | ARM mbed NXP LPC1768 Development Board | [World](https://www.pololu.com/product/2150) | 49.00 | 
| 1 | QTR-8A Reflectance Sensor Array | [World](https://www.pololu.com/product/960) | 9.95 | 
| 1 | TB6612FNG Dual Motor Driver Carrier | [World](https://www.pololu.com/product/713) | 4.95 | 
| 1 | Bluetooth Module HC-05 | [World](https://www.robocore.net/loja/produtos/modulo-bluetooth-hc-05.html) | 12.30 | 
| 2 | 30:1 Micro Metal Gearmotor HP 6V with Extended Motor Shaft | [World](https://www.pololu.com/product/2212) | 16.95 | 
| 1 | Magnetic Encoder Pair Kit for Micro Metal Gearmotors | [World](https://www.pololu.com/product/3081) | 8.95 | 
| 1 | Profuse 2S 7.4V 850 Mah LiPo Battery | [World](http://www.jsumo.com/profuse-2s-74v-850-mah-lipo-battery) | 13.50 | 


## Mecanichs
The mechanics project was developed in the [Fusion 360](https://www.autodesk.com/products/fusion-360/overview), a 3D CAD/CAM Software free for students. Project available [here](http://a360.co/2tWd5yP).

### 3D Printed Parts
| Qtd | Item | 
|-----|------|
| 1 | Chassis |
| 4 | Motor Support |
| 2 | Ball Caster Holder |
| 3 | Spacer |
| 1 | PCB Support |

### Bill of materials
| Qtd | Item | Buy | US$ |
|-----|------|-----|-----|
| 1 | Atom Wheel 37x34mm Pair | [World](http://www.jsumo.com/atom-wheel-37x34mm-pair) | 19.50 | 
| 1 | Mini Plastic Caster Wheel Pair | [World](http://www.jsumo.com/mini-plastic-caster-wheel-pair) | 1.40 | 


## Software
Only a concept.


# Contributors
* [Gustavo Silva de Paula](https://github.com/Gustavo-dPaula)
* [Marcelo Farias](https://github.com/MarceloFariaz)
