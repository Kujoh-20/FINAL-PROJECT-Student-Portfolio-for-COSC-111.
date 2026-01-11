# Laboratory Activity #4
## Working with Arduino Serial Connection

### Course
COSC 111 – Internet of Things

### Objective
The objective of this laboratory activity is to understand how Arduino communicates with a computer using Serial communication and how sensor data can be monitored and controlled through the Serial Monitor. This activity focuses on reading analog input values and using serial commands to control output behavior.

### Description
In this activity, a photoresistor is used to measure light intensity through an analog input pin. The Arduino reads the sensor value and converts it into a percentage to make the data easier to interpret. These values are continuously sent to the Serial Monitor for real-time observation.

When the light intensity reaches a defined threshold, an alert output begins to blink. The Serial Monitor is also used as an input interface, allowing the user to send a command to stop the blinking behavior. This demonstrates two-way Serial communication and shows how software-based control can be combined with sensor input in IoT systems.

### Tools / Technologies Used
- Arduino Uno or compatible Arduino board
- Arduino IDE
- Photoresistor (LDR)
- LED for alert indication
- Breadboard
- Resistors
- Jumper wires
- Arduino Serial Monitor

### Output
The expected output of this activity is a system that displays light intensity values in the Serial Monitor. When the brightness exceeds the set threshold, the alert LED blinks continuously. Sending the command "stop" through the Serial Monitor immediately turns off the alert, demonstrating interactive Serial control.

### Author
John Oniel Thomas Araque
