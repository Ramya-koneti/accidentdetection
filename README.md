# accidentdetection
This project is an accident detection system using Arduino Uno, ADXL335 accelerometer, GPS, and GSM modules. It detects sudden accelerations indicative of accidents, retrieves the vehicle's location via GPS, and sends an SMS alert with the location details to emergency contacts using the GSM module. 
<br>
<h1>Components</h1>
<p>Arduino Uno: The main microcontroller that coordinates the system's operations.<br>
ADXL335 Accelerometer: Detects sudden changes in acceleration which may indicate an accident.<br>
GPS Module: Provides the geographical location of the vehicle.<br>
GSM Module: Sends alert messages to predefined emergency contacts with the location details.</p><br>
<h1>How it Works </h1>
<p>Acceleration Monitoring: The ADXL335 accelerometer continuously monitors the vehicle's acceleration.<br>
Accident Detection: When a sudden change in acceleration is detected, indicative of an accident, the system triggers an alert.<br>
Location Retrieval: The GPS module retrieves the current location of the vehicle.<br>
Alert Messaging: The GSM module sends an SMS alert to predefined emergency contacts, including the GPS coordinates of the accident location.</p><br>
<h1>Installation and Setup</h1>
<p>Hardware Setup: Connect the Arduino Uno, ADXL335, GPS module, and GSM module according to the provided schematics.<br>
Software Setup: Upload the Arduino sketch from the src directory to the Arduino Uno.<br>
Configuration: Configure the emergency contact numbers and other parameters in the Arduino sketch.</p>
