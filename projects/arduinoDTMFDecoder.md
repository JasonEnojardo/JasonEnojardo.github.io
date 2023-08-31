---
layout: project
type: project
image: img/Arduino-DTMF-Decoder/Arduino-Logo-2.png
title: "DTMF Decoder Arduino"
date: 2022
published: true
labels:
  - Arduino
  - C
summary: "This device uses a DTMF Deconder to turn on speakers."
---

<img class="img-fluid" src="..img/Arduino-DTMF-Decoder/Arduino-MT8870-Schematic.jpg">

  The purpose of this project was to make a replacement componet for the speaker systems in the fire stations because the compnent in place is not being produced anymore and it was the only one of its type that fit the speaker system we were using. So in the event that this particular device stopped working there would be a replacement part. This project was given to me and so I set out trying to figure out what parts I'd needed to make this work. First I asked how the current device works and it works by recieving combinations of dial tones frequencies which is read by the device and when the right combination is recived it triggers the stations speakers to turn on. Luckly for me there was an attachment that could be hooked up to an Arduino. The attachment is called the MT8870 and it worked by retriving the sound frequency through a 3.5mm jack which goes through the decoder chip and lights up leds built on the board in binary. So for example if a 1 dial tone was recived it'd display 0001.

  The intersting thing I learned from this project is what is contained in a dial tone frequency and how the MT8870 is able to decode it. For instance the number 5 would be 0101 in binary. In order to properly output this the device is taking the frequency and breaking it down to 0's and 1's. So what I mean is in the number 5 dial tone, it is made up of 0 and 1 translated in the frequency. So the device reads the first bit, which would read a 0 and then it would have to shift that bit to the left by 1 to recieve the next bit 1, and continue until the tone is finished. So that's how were left with 0101.

  
