# Laboratory Activity #6
## Working with Bidirectional Control Using Arduino and Python

### Course
COSC 111 – Internet of Things

### Objective
The objective of this laboratory activity is to understand and implement bidirectional communication between an Arduino and a Python program. This activity focuses on controlling LEDs using both physical buttons on the Arduino and keyboard commands from Python, demonstrating real-time two-way interaction between hardware and software.

### Description
In this activity, three LEDs (Red, Green, Blue) are connected to an Arduino and can be toggled either by pressing physical push buttons or by sending commands from a Python program via serial communication.  

The Arduino code reads the state of the push buttons and sends signals to the Python program when a button is pressed. The Python program listens for these signals and responds by sending commands back to the Arduino to toggle the corresponding LEDs. Users can also directly type commands (`1`, `2`, `3`) in the Python console to control the LEDs.

This setup demonstrates key IoT concepts such as:
- Reading digital inputs from sensors (push buttons)
- Controlling digital outputs (LEDs)
- Establishing serial communication between microcontroller and computer
- Implementing bidirectional control to synchronize hardware and software actions in real time

### Tools / Technologies Used
- Arduino Uno (or compatible board)
- Arduino IDE
- Red, Green, and Blue LEDs
- Resistors
- Breadboard
- Jumper wires
- Python 3.x
- PySerial library for Python serial communication
- USB cable for Arduino-PC connection

### Output
The system allows real-time LED control using both the Arduino buttons and Python console commands. Pressing a button on the Arduino will toggle the corresponding LED and send a signal to Python, while typing commands in Python will toggle the LEDs on the Arduino and print a confirmation message in the console.

### Author
John Oniel Thomas Araque
