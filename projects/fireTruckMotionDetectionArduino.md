---
layout: project
type: project
image: img/Motion Detection Arduino.jpg
title: "Fire Truck Motion Detection Arduino"
date: 2022
published: true
labels:
  - Arduino
  - C
  - Powershell
summary: "This is a device that detects vehicular motion paired with an automated program to retrieve the data."
---

I don't know success just yet but when i do i'll sure update this.

Here is some code that illustrates how we measure success in our class:

```cpp
byte ADCRead(byte ch)
{
    word value;
    ADC1SC1 = ch;
    while (ADC1SC1_COCO != 1)
    {   // wait until ADC conversion is completed   
    }
    return ADC1RL;  // lower 8-bit value out of 10-bit data from the ADC
}
```
