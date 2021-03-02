# Arduino 4.1 - Utilizing the L298N Motor Controller
## The L298N motor controller is a great way to use DC motors in conjunction with a programmable board like the Arduino UNO.  It allows us to utilize very basic coding techniques without any additional libraries.  It supports power supplies from 5V to 25V.  This example utilizes a 9V battery but a battery pack with 5 AA batteries is sufficient as well.
---

### Step One: Build the Circuit

Build your circuit according to this diagram:

![](https://github.com/WHS-Robotics-Classes/4-1_Utilizing_the_L298N_Motor_Controller/blob/main/Arduino%20Lab%203.1%20-%20Utilizing%20the%20L298N%20Motor%20Controller%20(1).png?raw=true)

### Step Two: Write the Code

Review concepts of digital and analog (PWM) control systems from previous labs.  Be sure that you are able to control LEDs with the `digitalWrite()` and `analogWrite()` commands.  Once you are confident with that, move on.

Concept Overview:  If we can make a light turn on and off we can control the direction of the motor.  For example, to control the direction of motor A in the figure above we would turn on pin ENA and turn off pin ENB using `digitalWrite()`.  To reverse the motor you reverse the commands.  To control the speed of that motor we would use the `analogWrite()` command with pin ENB.  Once we have this concept down, we can control the motors’ speed and direction.

**Write three different sketches.  Each should do the following:**
1. Start motor B at full speed for five seconds and then stop.
2. Make motor A ramp up speed from fully stopped to full speed over the course of five seconds and then ramp back down to fully stopped over the course of five seconds.
3. Make both motors do the following: 
    - Run at half speed for three seconds.
    - Stop motor A completely and run motor B on full for two seconds.
    - Run motor A in reverse and motor B forward, both on full speed, for two seconds.
    - Stop both motors.

### Step Three: Debug and Submit

Make sure your prototype behaves the same way as the demo in class. **Make three new files and commit them to this repository on GitHub**. Name them as follows:
    - 4.1-L298N-1
    - 4.1-L298N-2
    - 4.1-L298n-3
