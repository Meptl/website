---
layout: default
title:  "Point-to-Point Ethernet Repeater using Wireless Technology"
---

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
