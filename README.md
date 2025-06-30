# IOT-SECURITY-SYSTEM

COMPANY : CODTECH IT SOLUTIONS

NAME : KOMPELLA KIRANMAYI

INTERN ID : CTO4DF1700

DOMAIN : INTERNET OF THINGS

DURATION : 4 WEEKS

MENTOR : NELLA SANTOSH KUMAR

DESCRIPTION:

✅ Overview:
This simple IoT-based security system uses an LDR (Light Dependent Resistor) sensor to detect any sudden change in light intensity, such as someone entering a room or covering the sensor. The system responds by lighting up LEDs, which simulate an alert mechanism. It is implemented and simulated using Tinkercad, a web-based circuit and Arduino simulation platform.

🧰 Components Used:
Arduino Uno R3:

The microcontroller board used to process the LDR readings and control the LEDs.

Breadboard:

Used for building the circuit without soldering, allowing easy connections among components.

LDR (Light Dependent Resistor):

A sensor that changes resistance based on the surrounding light intensity.

Acts as the primary intrusion detector.

Two LEDs (Red and Orange):

Visual indicators of alert/warning when intrusion is detected.

Resistors:

1 x 10kΩ resistor: Connected in series with the LDR to create a voltage divider.

2 x 220Ω resistors: Connected in series with the LEDs to limit current and prevent burning out.

Jumper Wires:

Used to connect the Arduino pins to the breadboard components.

💻 Software Used:
Tinkercad Circuits (by Autodesk)
A free, browser-based platform used to simulate Arduino-based electronics.
Link: https://www.tinkercad.com

Features used:

Circuit simulation

Arduino code editor

Serial monitor for sensor value debugging

🔌 Circuit Connections:
✅ LDR Sensor Setup:
One leg of the LDR is connected to 5V (positive rail).

The other leg of the LDR is connected to analog pin A0 of Arduino and to one end of a 10kΩ resistor.

The other end of the resistor is connected to GND.

This forms a voltage divider, enabling the Arduino to read variable voltages based on light intensity.

✅ LEDs:
Red LED:

Anode (long leg) → Pin 7 on Arduino

Cathode (short leg) → Connected to GND through a 220Ω resistor

Orange LED:

Anode (long leg) → Pin 8 on Arduino

Cathode (short leg) → Connected to GND through a 220Ω resistor

✅ Power Connections:
Breadboard’s positive rail → 5V pin on Arduino

Breadboard’s ground rail → GND pin on Arduino

🧠 Working Principle:
The Arduino constantly reads the analog input from the LDR (pin A0).

If the light level drops below a threshold, it indicates that something is blocking the light (e.g., someone passing by or entering).

As a result, the system activates both LEDs as a form of visual alert.

When normal light is restored, the LEDs turn off.

📈 Use Case Applications:
Home security lighting

Light-sensitive alarms

Intruder detection systems

IoT smart room automation

Museum/art gallery protective lighting systems

OUTPUT PICTURE 
