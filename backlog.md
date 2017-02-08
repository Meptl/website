---
layout: default
title:  "Backlog"
---

# The Backlog
Here's ideas, research, and progress.

## Point-to-point ethernet repeater using wireless technology
Two devices that extend ethernet communication wirelessly. Each device would have a female ethernet port and send all data received from this
port to the other device. Ideally, I should use a method of wireless communication that has a means of securing communication.

RONJA, AKA lasers.

### Bluetooth
HC-05, a common bluetooth module, uses Bluetooth 2.0+EDR which is limited to around 2.1 Mbit/s.
Look for Bluetooth 3.0+HS or the +HS qualifier. This has theoretical 24 Mbit/s. The technology initiates over bluetooth then creates
a communication channel through wifi. Neat. Keep in mind this would require both endpoints to have wifi/bluetooth chips.
Try to avoid Bluetooth 4.0+LE, LE stands for low-energy. It's likely these can just switch to high speed modes, but word around
the block is most 4.0 devices don't support high speed.

If I used bluetooth this could potentially be prototyped with arduinos. It would be a PoE arduino with a bluetooth module attached.
Bluetooth has the added benefit of secure communication.

I've been finding the PoE systems for arduinos difficult to find.
PoE may be limited to sub-Gigabit speeds on the arduino. A bit more research would need to be done on PoE spec.

## Hourglass Watch
### Trinket Prototype
I've created a prototype using the Adafruit Trinket, 128x32 OLED display, and 150MaH LiPo battery.
There was no system for charging the battery during use and no female JST socket on the Trinket (though I could've soldered one)
The circuit is in pen and paper.
I tried to simply solder a small form factor of my circuit but failed.

### ATTiny Prototype
I've purchased parts to directly utilize the ATTiny85 microcontroller which the Trinket uses.
While researching for the ATTiny prototype I discovered button cell batteries (CR2032). It has a rechargeable option.
But how to charge? See load sharing, I've bookmarked a page.

### PCB Prototype
Leave open 6 pins for a TC2030-ICD. This can be used to program the MCU.
Hopefully I can just robbery the display schematic and use it.

## Dynamic Box Generation System
All-in-one package for creating custom sized packages.
### 3D Approximation
Computer vision? Lasers?
### Minimum Bounding Box
### Box form schematic
### Folding algorithms for robotic arms

## DIY Laptop
Build a small form factor computer using the thin mini ITX motherboard form factor.
This is an old project that died off for a few reasons:
* Display specification is hard.
    - Each laptop manufacturer decides it wants it's own LVDS pinouts. Intel is trying a formal specification (insert relevant xkcd here)
    - The pin outs of my desired monitor and the connector on the motherboard were different.
      Creating a translation required exacting and numerous soldering which I failed at.
      Alternatively I could create an adapter PCB, but I'm not knowledgeable enough on the process.
* Rechargeable batteries are both terrifying and confusing.
* Seeing the form factor in real life, it's still a bit clunky.
* Niche area was filled.

## Chopsticks where the tips are a denser material than the back
I'm thinking box wood tip (high density) and a poplar backend (low density). I believe these are both non-toxic, but I don't have enough woodworking
experience to say whether the wood would "work".

## House made of doors

## LLVM to CSS 'assembler'
I heard around the block that CSS is turing complete.

## Glasses frames
Frames to replace my current glasses. Long story.

## A table that catches your cups
Initial plan was two IR breakline and some maths to determine resulting velocity, point of impact, etc.
CV with those lines for high speed cameras is another idea.
Also FMCW radar.
I think I might do an IR breakline prototype to get all the maths down. Here's me acting like this requires a PHD in physics.

## Parking spot detection using aerial drones

## Filesystem using voice

## Replace my laptop keyboard with a superior version
Current keyboard for N240BU Clevo keyboard: CVM14C23US-4301. Can't get any datasheets on it.
These laptop ribbon cables potentially transmit the raw matrix data from the keyboard.
* Getting a thinkpad keyboard and translating the signals properly.
* Creating a low-profile keyboard.
    - Attach to the empty usb header.

## Correlation between typing speed and intelligence
## Truffle generation system
