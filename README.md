# Eco-round

## Description

Our group as Eco-round are exploring the domain of sexual harassment. We are standing in the victims' perspective and trying to help female victims to cope with the negative effects brought by sexual harassment in entertainment places such as bars and clubs. Based on variety of research including academic papers and reports, interviews and observations, we come up with the idea of "Hug Pillow". And we manage to deploy three prototypes, which are:
1. Implementing heartbeat sensors by using Arduino to illustrate users' emotional statues.
2. Implementing different vibration patterns and pressures according to users' heartbeat by using vibration motors on Arduino.
3. Testing and deciding the physical appearance  of our pillow.

## Table of Content
* Eco-round
  * [Home](https://github.com/deco3500-2018/Eco-round/wiki)
  * [Project Proposal](https://github.com/deco3500-2018/Eco-round/wiki/Proposal)
  * [Design Process Overview](https://github.com/deco3500-2018/Eco-round/wiki/Design-Process-Overview)
  * [Poster & Promotional materials](https://github.com/deco3500-2018/Eco-round/wiki/Poster-&-Promotional-Materials)
* Stand-ups
  * [Before Week 7](https://github.com/deco3500-2018/Eco-round/wiki/Ongoing-Document---Before-Week-7)
  * [Week 9 Stand-up](https://github.com/deco3500-2018/Eco-round/wiki/Ongoing-Document---Week-9-Stand-up)
  * [Week 11 Stand-up](https://github.com/deco3500-2018/Eco-round/wiki/Ongoing-Document-Week-11-Stand-up-2-Prototype-1)
* Prototypes
  * [Prototype 1](https://github.com/deco3500-2018/Eco-round/wiki/Ongoing-Document-Week-11-Stand-up-2-Prototype-1)
  * [Prorotype 2](https://github.com/deco3500-2018/Eco-round/wiki/Ongoing-Document-Prototype-2)
  * [Prototype 3](https://github.com/deco3500-2018/Eco-round/wiki/Ongoing-Document-Prototype-3)
 
 ## Prototype Instruction
1. Heartbeat detecting using Arduino
 We achieved this by using a pulse sensor as illustrated below.
 
 ![pulse sensor](https://user-images.githubusercontent.com/42561134/47600231-48713000-da01-11e8-99ed-3bacd8b658a9.PNG)
 
 For connecting it to Arduino board:
 "S" on pulse sensor connect to "A0" on Arduino;
 "+" on pulse sensor connect to "5V" on Arduino;
 "-" on pulse sensor connect to "GND" on Arduino.
 
 ![heartbeat](https://user-images.githubusercontent.com/42561134/47600253-97b76080-da01-11e8-81d6-c78e984be1b1.PNG)
 
2. Vibration deployment
 We implemented this function by using the DRV2605L motor driver, which includes 117 basic pre-coded vibration modes. The following     image is the driver that we use.
 
 ![vib1](https://user-images.githubusercontent.com/42561134/47600276-0eecf480-da02-11e8-8543-f5d275c0af57.PNG)
 
 For connecting it to Arduino board:
 Connect Vin to the power supply with 5V;
 Connect GND to power ground;
 Connect the SCL pin to A5;
 Connect the SDA pin to A4;
 
 ![vib2](https://user-images.githubusercontent.com/42561134/47600277-0f858b00-da02-11e8-852f-a8ae75b4fffd.PNG)
 
