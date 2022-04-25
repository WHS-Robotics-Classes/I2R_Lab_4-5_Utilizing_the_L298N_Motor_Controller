# Arduino 4.1 - Utilizing the L298N Motor Controller
## The L298N motor controller is a great way to use DC motors in conjunction with a programmable board like the Arduino UNO.  It allows us to utilize very basic coding techniques without any additional libraries.  It supports power supplies from 5V to 25V. 
---

### Step One: Build the Circuit

Build your circuit according to this schematic (**Note: This shows how to wire up two motors while you will only be using one**):

![](https://github.com/WHS-Robotics-Classes/4-1_Utilizing_the_L298N_Motor_Controller/blob/main/4.1-L298N_Wiring.PNG?raw=true)

### Step Two: Write the Code

Review concepts of digital and analog (PWM) control systems from previous labs.  Be sure that you are able to control LEDs with the `digitalWrite()` and `analogWrite()` commands.  Once you are confident with that, move on.

Concept Overview:  If we can make a light turn on and off we can control the direction of the motor.  For example, to control the direction of motor A in the figure above we would turn on pin IN1 and turn off pin IN2 using `digitalWrite()`.  To reverse the motor you reverse the commands.  To control the speed of that motor we would use the `analogWrite()` command with pin ENA.  Once we have this concept down, we can control the motors’ speed and direction.

**Write three different sketches.  Each should do the following:**
1. Start yout motor at full speed for five seconds and then stop.
2. Make the motor ramp up speed from fully stopped to full speed over the course of five seconds and then ramp back down to fully stopped over the course of five seconds.
3. Make the motor do the following: 
    - Run at half speed for three seconds.
    - Stop completely for two seconds.
    - Run the motor in reverse on full speed, for two seconds.
    - Stop the motor.

### Step Three: Debug and Submit

Make sure your prototype behaves the same way as the demo in class. *Make three new files and commit them to this repository on GitHub*. Name them as follows:

    - 4.1-L298N-1.ino
    - 4.1-L298N-2.ino
    - 4.1-L298n-3.ino
