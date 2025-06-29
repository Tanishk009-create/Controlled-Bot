# Controlled Bot

This is an Arduino based project using  **L298N motor driver logic**, which allows directional movement through PWM and digital signals. Motors are powered using the ENA and ENB PWM pins.

# Requirements
Arduino Uno/Nano/MEGA
<br>
L298N Motor Driver (or equivalent)
<br>
2 DC Motors
<br>
External power supply (for motors)
<br>
Arduino IDE or compatible environment

# Uploading the Code
Connect your Arduino to your computer.
Open Arduino IDE.
Paste the code into a new sketch.
Select the correct Board and COM Port.
Click Upload.

# Notes
The values 255 for left motor are 100 for right motor are the author's local values obtained after calibration for forward movement. Individual need to calibrate the values themselves.
<br>
The delay defined in the loop function is also obtained by try and error for different values of delay. The values which give a perfect left or right 90 and turnaround are then taken into account. 
