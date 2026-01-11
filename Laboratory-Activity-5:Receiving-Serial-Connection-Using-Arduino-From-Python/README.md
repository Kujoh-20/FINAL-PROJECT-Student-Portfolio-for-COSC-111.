# Laboratory Activity #5
## Working with Arduino and Python Serial Communication

### Course
COSC 111 – Internet of Things

### Objective
The objective of this laboratory activity is to understand how serial communication can be used to control hardware devices using both Arduino and Python. This activity focuses on sending and receiving serial commands to manipulate digital outputs in real time.

### Description
In this activity, an RGB LED is controlled through serial commands sent from a Python program to an Arduino. The Arduino code is modularized using a header file to manage LED behavior, while the main program listens for incoming serial commands and performs corresponding actions.

The Python program provides a text-based menu that allows the user to toggle individual LEDs, turn all LEDs on or off, and exit the program. Commands entered by the user are transmitted to the Arduino via serial communication. The Arduino processes these commands and responds with status messages, demonstrating two-way communication between software and hardware.

This activity highlights the integration of embedded systems with desktop applications, which is a fundamental concept in Internet of Things (IoT) development.

### Tools / Technologies Used
- Arduino Uno or compatible Arduino board
- Arduino IDE
- RGB LED
- Resistors
- Breadboard
- Jumper wires
- Python programming language
- PySerial library
- Serial communication (USB)

### Output
The expected output of this activity is an interactive LED control system. The user can control the RGB LED using keyboard commands from the Python program. The Arduino responds by toggling the selected LED(s) and displaying confirmation messages through the Serial Monitor and Python console.

### Author
John Oniel Thomas Araque
