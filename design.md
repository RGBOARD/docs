---
title: Design
layout: home
nav_order: 2
---
<img src="assets/images/spinny.gif" alt="gif img of RGBoard">
# Designing an RGBoard
You can build this system however you want — and sometimes that freedom can feel like chaos. 
The version we’re showing here uses just two panels. Why? Because that was enough for our capstone project.
We actually considered going with a 2×2 layout, but in the end we saved money, time, and our sanity by sticking 
with a simpler 2×1 setup.

## Things to do prior to choosing parts and quantity
- Read the READMEs in the [rpi-rgb-led-matrix](https://github.com/hzeller/rpi-rgb-led-matrix).
If you're about to make a mistake, is likely they did first and wrote about it. For example, 
don't get a Raspberry Pi 5 when the library states that is only supported up to the Raspberry Pi 4.
- We got our panels from [Adafruit](https://www.adafruit.com/). Check their inventory for panels and 
see which ones you like best for your RGBoard. Make sure is the ones with two IDC connectors in the back.
- The panels can draw up to 4 amps each! When you add them up, your power supply system has to grow in
size and cost. 

## 1. Get a Raspberry Pi compatible with rpi-rgb-led-matrix
This computer is the central part of your computer. Get yourself a good amount of RAM
to have enough room for your programs that make up the whole system.