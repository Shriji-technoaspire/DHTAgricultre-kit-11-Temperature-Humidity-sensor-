# DHTAgricultre-kit-11-Temperature-Humidity-sensor-

♥♥Wiring://////////
Connect the wire, the DHT11 has 4 or 3 Pin includes VCC, Data, and Ground pin.

VCC Pin of DHT11 to 5V Pin of WeMos D1 Mini
Data Pin of DHT11 to D4 Pin of WeMos D1 Mini
GND Pin of DHT11 to GND Pin of WeMos D1 Mini

♥♥Set Up Blynk:///////////////
After download and installing the Blynk Apps from Google Play Store, you need to make your IoT project apps in Blynk. Here the steps.

Login to your Blynk App. If you don't have one, just create it, it's free
Create a new project, give your project a name, choose your device : WeMos D1 Mini, connetion type : WiFi
Then you will receive a notification about Auth Token, just select OK. Your Auth Token wil be sent to your Email
Then you see your workspace. Go to Widget Box, and select 'Gauge'. Select the Gauge Widget twice, the first one will be set as the Temperature gauge, the second one will be set as the Humidity gauge.
After two gauge selected, go to the gauge setting.

♥♥For the first gauge://///////////////
Name: Temperature
Input: Virtual, V0
Label: °C / °F
Reading Rate: 1 Sec

♥♥For the second gauge:///////////////////
Name: Humidity
Input: Virtual, V1
Label: RH
Reading Rate: 1 Sec

♥♥Code://///////////////////////
Paste the code that i've attached, and change the auth code in the program that i've attached with your own auth code (check your Email for your auth code).

