INTRODUCTION
The Smart Crop Recommendation System is an IoT-based project that helps in analyzing environmental conditions such as soil moisture, gas levels, temperature, and humidity to assist in recommending suitable crops. This system utilizes multiple sensors alongwith an Arduino Uno microcontroller to collect real-time data and display it on an 16X2 LCD display.

OBJECTIVES
1.Monitor soil moisture levels in real time

2.Detect harmful gases in the environment

3.Display real-time data on LCD

4.Recommend suitable crops based on environmental conditions

COMPONENTS USED
Component	Description
Arduino Uno	Microcontroller board
MQ-2 Gas Sensor	Detects gas levels
Soil Moisture Sensor	Measures soil moisture
16x2 LCD Display	Displays output
Breadboard	Circuit building platform
Jumper Wires	Connections
LED	System status indicator
MACHINE LEARNING MODEL
Algorithm Used: Random Forest

Input Features
Soil Moisture
Gas Levels
Temperature
Humidity
Output
Recommended Crop
Model Description
The Random Forest algorithm is used to analyze sensor data and predict the most suitable crop.
It works by combining multiple decision trees to improve accuracy and reduce overfitting. Algorithm Used: Random Forest

CIRCUIT CONNECTIONS
Component	Arduino Pin
MQ-2 Analog Output	A0
Soil Moisture Sensor	A1
LCD RS	D12
LCD Enable	D11
LCD Data Pins	D3, D4, D5, D6
LED	D7
All components share a common GND and power supply

WORKING PRINCIPLE
The Soil Moisture Sensor measures the water content in the soil.

The MQ-2 Gas Sensor detects the presence of gases in the environment.

The collected data is sent to the Arduino Uno microcontroller.

The Arduino processes the sensor data and displays it on the 16x2 LCD.

The sensor readings are used as input for the Machine Learning model.

The Random Forest algorithm analyzes the data and predicts the most suitable crop.

The final crop recommendation is generated.

LED acts as an indicator for system status.

FEATURES
1.Real-time data monitoring

2.IoT + Machine Learning integration

3.Accurate crop recommendation

4.Low-cost and efficient system

APPLICATIONS
1.Smart agriculture

2.Precision farming

3.Decision support system for farmers

