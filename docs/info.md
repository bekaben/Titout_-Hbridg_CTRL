<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works
<p align="justify>
This logic circuit controls the H-bridge for a DC motor. The Dir input logical pin controls the rotation direction. The En digital input is used to shut down or turn on the motor.
  </p>
<br>
<img alt="H-Bridge general structure" src="./hbridge.jpg" width=500 height=500>
<br>
## How to test

En = OFF, En = 1 ON
Dir=0: Left; Dir=1: Right, but this depends on how you have wired your motor.

## External hardware

4 Transistors and 4 diodes selected depending on motor size and supported current.
