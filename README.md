
# Digital Clock with Alarm, Timer, and Stopwatch
< **University Project – CIS 314: Digital Hardware**

This Arduino-based project functions as a digital clock that can set alarms, work as a timer, and operate as a stopwatch.  
It combines hardware and software to demonstrate practical digital system design.


##  Components
- Arduino Uno
- 16x2 LCD Display
- 4 Push Buttons
- Buzzer
- LED (red)
- Potentiometer
- Breadboard and jumper wires

##  Features
- Real-time digital clock display
- Alarm with buzzer
- Timer with red LED indicator
- Stopwatch function

##  Usage
1. **Set Time:** Press Btn1, use Btn3 to move, Btn2 to adjust, Btn1 to save.  
2. **Set Alarm:** Press Btn2, use Btn3 to move, Btn2 to adjust, Btn1 to save.  
3. **Set Timer:** Press Btn2, use Btn3 to move, Btn2 to adjust, Btn4 to start.  
4. **Stopwatch:** Press Btn4 to start or stop.

##  Arduino Code
The full source code for the project is included in this repository:  
[`Arduino_Code.ino`](Arduino_Code.ino)

###  Code Overview
The Arduino program controls the LCD, buttons, buzzer, and LED to create a digital clock with:
- Time display and real-time updates.
- Adjustable alarm using push buttons.
- Stopwatch and timer functionality.
- Visual and audio indicators for active timers.

The logic uses:
- `millis()` for timing.
- `digitalRead()` to capture button inputs.
- `digitalWrite()` to control LED and buzzer.
- `LiquidCrystal` library to manage the LCD display.


## Circuit Preview
![Digital Clock Circuit](Digital_Clock_Circuit.png)
## 📄 Circuit Schematic

For detailed wiring and electrical connections, refer to the schematic diagram below:  
[📘 View Full Schematic (PDF)](Schematic%20view.pdf)

##  View the Project on Tinkercad
You can view and simulate the full digital clock circuit here:  
[Open in Tinkercad](https://www.tinkercad.com/things/fTawpWQFh5H/editel?sharecode=Y6pAEXqw7V4FaRsp8ugJ0hJVsnu1YxpcR-qVieUP4kA)
