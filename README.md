ABSTRACT 
The concept of this project is  to  allow  the  owners  of  fields  to  control  and  observe  the  growth of their plants in  their  farms. This is  achieved by using a  smart  platform of IoT  and  solenoid valves to  control the flow of water based  on the moisture of the soil and  gives real  time surveillance to  the  owners who stay far away from  the farms. This project also allows surveillance on the personnel and their crops so, as to not occur losses. It is easy to use for anyone  with a Smartphone and doesn’t require maintenance once set up.
The concept of this project is  to  allow  the  owners  of  fields  to  control  and  observe  the  growth of their 
plants in  their  farms. This is  achieved by using a  smart  platform of IoT  and  solenoid valves to  control 
the flow of water based  on the moisture of the soil and  gives real  time surveillance to  the  owners who 
stay far away from  the farms. This  project also allows surveillance on the personnel and their crops so 
as to  not occur losses. It is  easy to  use for anyone  with a Smartphone and doesn’t  require maintenance 
once set up.
The concept of this project is  to  allow  the  owners  of  fields  to  control  and  observe  the  growth of their 
plants in  their  farms. This is  achieved by using a  smart  platform of IoT  and  solenoid valves to  control 
the flow of water based  on the moisture of the soil and  gives real  time surveillance to  the  owners who 
stay far away from  the farms. This  project also allows surveillance on the personnel and their crops so 
as to  not occur losses. It is  easy to  use for anyone  with a Smartphone and doesn’t  require maintenance 
once set up. 

INTRODUCTION

 Irrigation is one method to supply water but in some cases, there will be lot of water wastage. Therefore, in this regard to save water and time we have proposed project titled automatic irrigation system using IoT. In this proposed system, we are using various sensors like temperature, humidity, soil moisture sensors, which senses the various parameters of the soil and based on soil moisture value land gets automatically irrigated by ON/OFF of the motor. These sensed parameters and motor status will be displayed on user android application.
The Internet of Things (IoT) is a technology where in a mobile device can be used to monitor the function of a device. The Internet of Things (IoT) is concerned with interconnecting communicating objects that are installed at different locations that are possibly distant from each other. Internet of Things (IoT) is a type of network technology, which senses the information from different sensors and makes anything to join the Internet to exchange information.
This project helps the farmers to irrigate the farmland in an efficient manner with automated irrigation system based on soil moisture. Time money also save by the farmer with the use of modern technique.

PRINCIPLE 
The whole project is based on ESP32 as the main brain of the system. All the sensors relays are interfaced with the ESP32 controller. The ESP32 is designed for low power IoT applications in mind. It’s high processing power with in-built Wi-Fi / Bluetooth and Deep Sleep Operating capabilities makes it ideal for most Portable IoT devices.
This soil moisture sensor module is used to detect the moisture of the soil. It measures the volumetric content of water inside the soil and gives us the moisture level as output. The module has both digital and analog outputs and a potentiometer to adjust the threshold level.
The DHT22 is a commonly used temperature and humidity sensor. The sensor comes with a dedicated NTC to measure temperature and an 8-bit microcontroller to output the values of temperature and humidity as serial data. The sensor is also factory calibrated and hence easy to interface with other microcontrollers. The sensor can measure temperature from -40°C to 80°C and humidity from 0% to 100% with an accuracy of ±1°C and ±1%. So if you are looking to measure in this range then this sensor might be the right choice for you.
The relay module is an electrically operated switch that allows you to turn on or off a circuit, using voltage and/or current much higher than a microcontroller could handle. There is no connection between the low voltage circuit operated by the microcontroller and the high power circuit. The relay protects each circuit from each other.
Water Solenoid Valve 12V.This is a normally closed 12 Volt Solenoid Valve perfect for controlling water flow. This is an ON-OFF type solenoid valve. This is normally used in solar water heaters. It is made of plastic and copper and can be detached to clean its filter.
Objective Of The Project
 The main objective of this project is to provide an automatic irrigation system thereby saving time, money & power of the farmer. 
The traditional farmland irrigation techniques require manual intervention. With the automated technology of irrigation, the human intervention can be minimized.
The only solution to this problem is smart agriculture by modernizing the current traditional methods of agriculture. Hence, the proposed method aims at making agriculture smart using automation and IoT technologies. Internet of Things (IoT) enables various applications crop growth monitoring and selection, irrigation decision support, etc. A Node-MCU based automatic irrigation IOT system is proposed to modernization and improves productivity of the crop. Main aim of this work to crop development at low quantity water consumption, In order to focus on water available to the plants at the required time, for that purpose most of the farmers waste lot time in the fields. An efficient management of water should be developed and the system circuit complexity to be reduced. The proposed system developed on the information sent from the sensors and estimate the quantity of water-needed .A two sensors are used to get the data to the base station the humidity and the temperature of the soil, the humidity, the temperature, and the duration of sunshine per day. The proposed systems based on these values and calculate the water quantity for irrigation is required. The major advantage the system is implementing of Precision Agriculture (PA) with cloud computing, that will optimize the usage of water fertilizers while maximizing the yield of the crops and also will help in analysing the weather conditions of the field.
	
CIRCUIT DIAGRAM

check -- > pcb.pdf


LIST OF COMPONENTS 
I.		Microcontroller node-MCU	1
II.		Temperature humidity sensor (DHT11)	1
III.		Soil moisture sensor	1
IV.		Motor pump DC-12V	1
V.		Motor driver L298	1
VI.		LED 	1
VII.		Mobile application (Blynk)	-
VIII.		Connecting wire	-

Pin connection of node-mcu & virtual pin of blynk App

DHT11 senser signal pin ----> D4 pin of node -mcu (input)
moter driver signal pin ---> D0 pin of node-mcu (output)
soil moisture sensor signal pin---> A0 in of node-mcu

Virtual Node (Blynk App)  
temprature                      ---> V1
humidity                        ---> V2
moisture                        ---> V3
Auto-control indicator LED      ---> V0
Button control for motor pump   ---> D0

