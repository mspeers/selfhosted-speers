# Holidays Light System

I wanted to create automated Christmas light system that include little hard and software. Currently use both Christmas and Halloween.

This project is to document what I did and to step to recreate what I have done. 

## Videos:
2022 Christmas Light Show:

[![2022 Christmas Light Show](https://img.youtube.com/vi/laKFfjLhqhQ/0.jpg)](https://youtu.be/laKFfjLhqhQ "2022 Christmas Light Show")

2022 Halloween Light Show:

[![2022 Halloween Light Show](https://img.youtube.com/vi/AcGbxJbV51w/0.jpg)](https://youtu.be/AcGbxJbV51w "2022 Halloween Light Show")

My System 3rd version:

## Items:
- Pi 4b, Power for PI 
- 8 port relay
- FM (car Radio), power wire
- Outdoor speaker,  power for outdoor speaker mirc usb (UBS1), block.
- Box:
  - Box - I used wood
  - outlet 8 wire box
  - 4 outlets
- Wire:
  - audio split
  - audio extender (to connect outdoor speaker)
  - Core to connect 
  - Long 12 gauge wire to connect all the relay and 



## Wiring:

### This diagram of the wiring:
![Light Show Wiring](./pictures/ligth-show-wiring.png)

Real Pictures:

### Outlet Box:
![Outlet Box](./pictures/outlet-box.jpg)
Outlet box was easyer part has not much changes over time. I number then so in software I can have on outlet on all times. Allows for lazer lights on. They do not work with power being on / off fast. 

8 Channel Relay:![8 Channel Relay](./pictures/relay-connect.jpg)
One hardest part. I found out that wires were pulling out trying to get all the wires together in small area


## Software: 

- Lightshow PI at https://bitbucket.org/togiles/lightshowpi/src/master/
  Interface: ![interface](./pictures/lightshowpi-interface.png)
- Raspberry OS 32:


### Setup:
 [Setup Guide](./setupguide.md)
