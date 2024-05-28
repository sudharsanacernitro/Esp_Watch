<h1>ESP8266 Internet-Connected Watch</h1>
This project involves creating a watch using the ESP8266 microcontroller, an LCD screen, and retrieving time from the internet. This README file provides step-by-step instructions to set up the hardware, software, and run the project.<br>
Table of Contents<br>
Hardware Requirements<br>
Software Requirements<br>
Circuit Diagram<br>
Installation<br>
Configuration<br>
Running the Project<br>
Troubleshooting<br>
Contributing<br>
License<br>
<h2>Hardware Requirements</h2>
ESP8266 microcontroller (e.g., NodeMCU, Wemos D1 Mini)<br>
LCD screen (e.g., 16x2 or 20x4 with I2C module)<br>
Breadboard and jumper wires<br>
USB cable for programming the ESP8266<br>
Software Requirements<br>
Arduino IDE (latest version)<br>
ESP8266 board library for Arduino IDE<br>
Libraries: Wire.h, LiquidCrystal_I2C.h, NTPClient.h, WiFi.h<br>
<h2>Circuit Diagram</h2>
Connect the hardware components as follows:<br>
ESP8266 to LCD Screen (with I2C Module):<br>
VCC to 3.3V<br>
GND to GND<br>
SDA to D2 (GPIO 4)<br>
SCL to D1 (GPIO 5)<br>
Ensure the connections are secure and the power supply is adequate.<br>
<h2>Installation</h2>
<h3>Set up Arduino IDE:</h3>h3>
Install the latest version of Arduino IDE from the official website.<br>
Add the ESP8266 board to Arduino IDE by going to File -> Preferences -> Additional Board Manager URLs and adding: http://arduino.esp8266.com/stable/package_esp8266com_index.json.<br>
Go to Tools -> Board -> Board Manager, search for ESP8266, and install it.<br>
<h2>Install required libraries:</h2>
Go to Sketch -> Include Library -> Manage Libraries.<br>
Search for and install the following libraries:<br>
ESP8266WiFi<br>
NTPClient<br>
Wire<br>
LiquidCrystal_I2C<br>
