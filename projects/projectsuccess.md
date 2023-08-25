---
layout: project
type: project
image: img/micromouse/micromouse-square.jpg
title: "Project Success"
date: 2023-08-24
published: true
labels:
  - JavaScript
  - Arduino
  - React
summary: "Project success is how i pass my classes. It is inteded to guide those for educational success."
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
