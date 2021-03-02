# Arduino 4.1 - Utilizing the L298N Motor Controller
## The L298N motor controller is a great way to use DC motors in conjunction with a programmable board like the Arduino UNO.  It allows us to utilize very basic coding techniques without any additional libraries.  It supports power supplies from 5V to 25V.  This example utilizes a 9V battery but a battery pack with 5 AA batteries is sufficient as well.
---

### Step One: Build the Circuit

Build your circuit according to this diagram:

![pulldown analog circuit](https://github.com/WHS-Robotics-Classes/3.55-Analog_Input/blob/main/Analog_Circuit.PNG?raw=true)

### Step Two: Write the Code

Before you start, review the Arduino Reference page on [`if()`](https://www.arduino.cc/reference/en/language/structure/control-structure/if/).  Also review what you did last week with `analogRead()` as you will need to use those concepts again.

1. Recycle your code from Lab 3.55 - Analog Input.  You will keep the structure that reads the alalog pin and add a conditional to it in the [Codebender IDE](https://edu.codebender.cc/class/1ajtp).
2. Modify the code so your sketch does the following:
    - Turn on the LED_BUILTIN light when the value of 512 or greater is received over pin A0 using `AnalogRead()`.
    - Turn it off otherwise.

Use the video below as a reference.

### Step Three: Debug and Submit

[![3.6_Video](http://img.youtube.com/vi/y0xzbV8Tw1U/0.jpg)](https://www.youtube.com/watch?v=y0xzbV8Tw1U "3.6-Conditionals I")

Make sure your prototype behaves the same way as the one in the video. As in the previous assignment, make a new file here on GitHub. Name it 3.6_Conditionals_I.ino and Commit it to the repository.
