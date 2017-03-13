---
layout: default
title:  "Backlog"
---

# The Backlog
Here's ideas, research, and progress.

{% for log in site.backlog %}
  <h2>
    <a href="{{ log.url }}">{{ log.title }}</a>
  </h2>
{% endfor %}

## Hourglass Watch
Though I've gone the microcontroller route, the circuit seems so simple that it could potentially be made with simple electronic components.
Like a button and flip-flop under a XOR gate governing a timing circuit.
Only problem is communicating with the display. Perhaps, an array of LEDs could be a substitute.

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
Flat filesystem filtered using a voice interface.
"Show me everything from last week's project"

Idea: EVERYTHING IS A SYMLINK.

## Replace my laptop keyboard with a superior version
Current keyboard for N240BU Clevo keyboard: CVM14C23US-4301. Can't get any datasheets on it.
These laptop ribbon cables potentially transmit the raw matrix data from the keyboard.
* Getting a thinkpad keyboard and translating the signals properly.
* Creating a low-profile keyboard.
    - Attach to the empty usb header.

## Correlation between typing speed and intelligence
## Truffle generation system

# MonetizeAP
Replace advertisement with your own advertisement links when acting as access point.
Even better and more illegal: hijack wireless traffic and inject your advertisement into links.
Replace amazon links with your referral link.
