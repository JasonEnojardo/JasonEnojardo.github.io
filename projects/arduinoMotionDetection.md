---
layout: project
type: project
image: img/arduinoMotionDetection/Arduino-Logo.png
title: "Fire Truck Motion Detection Arduino"
date: 2022
published: true
labels:
  - Arduino
  - C
  - Powershell
summary: "This is a device that detects vehicular motion paired with an automated program to retrieve the data."
---

<img class="img-fluid" src="..img/arduinoMotionDetection/Arduino-GY-521-Schematic.png">
img/arduinoMotionDetection/My-Arduino-Motion-Detection-Device.jpg

  The idea behind this project started out with finding a way to make sure firefighters are leaving the station within the 2-minute timeframe they are told they have once they receive the dispatch alarm for an incident. Currently there is already a tracking system in place on the trucks but the issue with that is their locations are updated on a timer rather than if they were driving. So, the solution we came up with was to use and accelerometer hooked to an Arduino that sent a signal to the COM port on the laptop. The accelerometer we choose to use was the GY-521. So, after coming up with this idea I was tasked to create the device and program it does what we wanted and create the automated program that collected the data produced.

  This was a relatively simple project as the Arduino IDE has a header file, I could download to handle the GY-521 and all outputs of an Arduino are sent to the COM port of the computer. All I had to do was use the provided functions to initialize, loop the accelerometer and output anything that came from it. Also wiring the GY-521 was simple because it just needed to be hooked to power, ground, TX, and RX pins. At first, I thought it was that simple, but I had issues with getting it to work as intended because sometimes it wouldn't even detect any movement. Even though I tried tweaking the sensitivity values of the sensor nothing I did really improved the issue I was having. Although it wasn't a complete loss as it worked most of the time and yielded good results.

  The other portion of this project was to create a program that ran all the time just waiting to read whatever came through on the COM port connected to the Arduino and take the data and upload it to a text file and along with the name of the vehicle. So, I had to do 2 major things here, 1, I had to have the program go through some system files and open a text file and parse through it to retrieve the name of the vehicle, and 2, take the data which consisted of the time and movement speed and upload both onto a text file located on our server. This program was made using Powershell but prior to that I had tried making it in DOS BATCH, then a regular script, and then in Python. Ultimately, I choose to use Powershell because it integrated easier on the machines since they were all windows devices and if I had used python, I would need to install a compiler on 50 to 100+ machines. Unfortunate I cannot upload  the code for both the Arduino and automated program to upload here but I don’t as it's on my work computer.

  This was a wonderful learning experience for me because this was the biggest Arduino project I've ever worked on and there were so many intricate parts that I had to figure out how to make them work together. I learned how to use many different languages that I never had learned about prior to this project. I also learned how important it is to communicate updates with your boss along with asking for help when you don't know something, and have your coworkers check your code and ask if there are better efficient ways to code what you have.

