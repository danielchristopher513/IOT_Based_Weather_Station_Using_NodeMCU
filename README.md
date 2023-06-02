# IOT_Based_Weather_Station_Using_NodeMCU
# IoT Weather Station with NodeMCU ESP8266
## The IoT Weather Station with NodeMCU ESP8266 is a project that demonstrates how to create a simple online weather station using the NodeMCU ESP8266 (Wemos D1) Wi-Fi development board. This project pulls weather data such as temperature, humidity, rain, and vibration and displays it on a local website connected to the NodeMCU.

## Components Required
To build the IoT Weather Station, you will need the following components:

+ NodeMCU ESP8266 board
+ DHT11 sensor for temperature and humidity
+ Rain sensor
+ Vibration sensor
+ Breadboard
+ Jumper wires
## Circuit Diagram
Below is the circuit diagram for creating the live weather station monitoring using NodeMCU. Refer to the figure below for the circuit layout.
![](https://github.com/danielchristopher513/IOT_Based_Weather_Station_Using_NodeMCU/blob/main/circuit_diagram.png)
## Displaying the Data on the Website
To display the weather data on the website, follow these steps:

+ Connect the NodeMCU ESP12e to your laptop and select the board and port correctly.
+ Click the upload button to upload the code to the NodeMCU.
+ Ensure that your laptop or smartphone shares the same Wi-Fi network as the NodeMCU.
+ After uploading the code, open the serial monitor and set the baud rate to 115200. You will see the IP address in the monitor.
+ Copy the IP address and paste it into your browser.
+ You will see a webpage in your browser that refreshes automatically every 10 seconds (you can change this time in the code).
