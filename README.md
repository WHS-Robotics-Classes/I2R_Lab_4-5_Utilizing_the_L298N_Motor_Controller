# Arduino 3.6 - Conditionals I
## In this assignment you will take what you learned with analog sensors and combine it with `if()` and `else` to begin making decisions. 

### Conditionals allow our robotic systems to start making decisions.  This programming concept will accept an input, make a decision and actuate output.  Hence, this will be the first robot you have ever made in this class!
---

### Step One: Build the Circuit

Build your circuit according to this schematic (same as lab 3.55):

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
