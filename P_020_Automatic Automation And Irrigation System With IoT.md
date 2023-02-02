# Automatic Automation And Irrigation System With IoT
## Abstract
In this project we are developing a device that can be able to control our home devices with the help of IoT Technology, With this technology we can control our home appliance from anywhere in the world, and also we can monitor and control irrigation in our garden to take care of our favourite plants. 
<br><br>
In this project we are using an ESP8266 12E module to control home devices and measure soil moisture level. After measuring soil moisture level we check the mode of our system if the system is in auto mode then the system automatically turn on the motor when the soil is dry here we use Google fire base for the communication between android app and our device.
## Block Diagram
![AUTOMATIC AUTOMATION AND IRRIGATION SYSTEM WITH (IoT)](https://user-images.githubusercontent.com/109785046/216288619-9bf8432a-5227-422c-88c2-58d61b37c9ec.png)
<br>
Our system can be used in agriculture field to help farmers with slight modifications One of the various problems faced by farmers in their day to day farming activities is the constant need to watch over-irrigation. Many times, the farmer must travel several kilometres to reach their fields and irrigation pumps. Hence, a huge amount of time and effort is expended daily in a farmer's life to irrigate the field when this time could be made use by the farmer at other farms such as animal husbandries which requires much more continuous observation and care. Through this paper, a project is proposed where a system is created to completely automate the process of irrigation such that none to minimal human intervention is required. We will collect data about the moisture in the soil and send information to start the water pump if the level goes below the threshold.
<br>
## Node MCU
![image](https://user-images.githubusercontent.com/109785046/216289018-9ac7ef90-8c85-48d2-9f67-9c315c8ed91c.png)
NodeMCU is a low-cost open source IoT platform. It initially included firmware which runs on the ESP8266 Wi-Fi SoC from Espressif Systems, and hardware which was based on the ESP-12 module. Later, support for the ESP32 32-bit MCU was added. The firmware uses the Lua scripting language. The firmware is based on the eLua project, and built on the Espressif Non-OS SDK for ESP8266. It uses many open source projects, such as lua-cjson and SPIFFS. Due to resource constraints, users need to select the modules relevant for their project and build a firmware tailored to their needs. Support for the 32-bit ESP32 has also been implemented.
<br><br>
The NodeMCU (Node MicroController Unit) is an open-source software and hardware development environment built around an inexpensive System-on-a-Chip (SoC) called the ESP8266. The ESP8266, designed and manufactured by Espressif Systems, contains the crucial elements of a computer: CPU, RAM, networking (WiFi), and even a modern operating system and SDK. That makes it an excellent choice for Internet of Things (IoT) projects of all kinds.
<br><br>
However, as a chip, the ESP8266 is also hard to access and use. You must solder wires, with the appropriate analog voltage, to its pins for the simplest tasks such as powering it on or sending a keystroke to the “computer” on the chip. You also have to program it in low-level machine instructions that can be interpreted by the chip hardware. This level of integration is not a problem using the ESP8266 as an embedded controller chip in mass-produced electronics. It is a huge burden for hobbyists, hackers, or students who want to experiment with it in their own IoT projects.
## Soil moisture sensor
![image](https://user-images.githubusercontent.com/109785046/216289327-3acf0bcf-b477-4d3b-b023-6b6a9d76dd57.png)

Efficient irrigation management can improve yields, grain quality, conserve water and energy, and reduce nutrient leaching. One of the easiest and most effective ways to improve irrigation efficiency is to implement soil sensor technology in irrigation scheduling. This article provides basic knowledge and practical recommendations for using soil moisture sensors for irrigation scheduling.<br><br>
Soil moisture sensors measure or estimate the amount of water in the soil. These sensors can be stationary or portables such as handheld probes. Stationary sensors are placed at the predetermined locations and depths in the field, whereas portable soil moisture probes can measure soil moisture at several locations.
<br><br>A better understanding of the basic principles, definitions, and terms behind the soil-water-plant relationship is essential to effectively utilize soil moisture sensors. For more information, see Basics of irrigation scheduling.

## 4-Channel Relay
![image](https://user-images.githubusercontent.com/109785046/216289808-5cd6574c-2e85-483e-9b54-2ece1c08d525.png)
<br>
  The relay is the device that open or closes the contacts to cause the operation of the other electric control. It detects the intolerable or undesirable condition with an assigned area and gives the commands to the circuit breaker to disconnect the affected area. Thus protects the system from damage.
## Working Principle of Relay
It works on the principle of an electromagnetic attraction. When the circuit of the relay senses the fault current, it energises the electromagnetic field which produces the temporary magnetic field.<br><br>
![image](https://user-images.githubusercontent.com/109785046/216290190-a653f0a9-2adf-4637-b0be-caee02c9f442.png)
<br><br>This magnetic field moves the relay armature for opening or closing the connections. The small power relay has only one contacts, and the high power relay has two contacts for opening the switch.
<br><br>The inner section of the relay is shown in the figure below. It has an iron core which is wound by a control coil. The power supply is given to the coil through the contacts of the load and the control switch. The current flows through the coil produces the magnetic field around it.
<br><br>Due to this magnetic field, the upper arm of the magnet attracts the lower arm. Hence close the circuit, which makes the current flow through the load. If the contact is already closed, then it moves oppositely and hence open the contacts.
## Pole and Throw
The pole and throws are the configurations of the relay, where the pole is the switch, and the throw is the number of connections. The single pole, the single throw is the simplest type of relay which has only one switch and only one possible connection. Similarly, the single pole double throw relay has a one switch and two possible connections.
## 16x2 LCD Display
![image](https://user-images.githubusercontent.com/109785046/216290655-8da284e7-aa70-433b-be48-69c6db20387f.png)
<br>An LCD (Liquid Crystal Display) screen is an electronic display module and has a wide range of applications. A 16x2 LCD display is very basic module and is very commonly used in various devices and circuits. A 16x2 LCD means it can display 16 characters per line and there are 2 such lines. In this LCD each character is displayed in 5x7 pixel matrix. The 16 x 2 intelligent alphanumeric dot matrix display is capable of displaying 224 different characters and symbols. This LCD has two registers, namely, Command and Data.
<br><br>Command register stores various commands given to the display. Data register stores data to be displayed. The process of controlling the display involves putting the data that form the image of what you want to display into the data registers, then putting instructions in the instruction register. In your arduino project Liquid Crystal Library simplifies this for you so you don't need to know the low-level instructions. Contrast of the display can be adjusted by adjusting the potentiometer to be connected across VEE pin.

|Pin No:|Name|Description|
|-------|----|-----------|
|1|	Ground/Source Pin	|This is a GND pin of display, used to connect the GND terminal of the microcontroller unit or power source.|
|2|	VCC/Source Pin |This is the voltage supply pin of the display, used to connect the supply pin of the power source.|
|3| V0/VEE/Control Pin	|Adjusts the contrast of the LCD.|
|4| Register Select|	This pin toggles among command or data register, used to connect a microcontroller unit pin and obtains either 0 or 1(0 = data mode, and 1 = command mode).|
|5| Read/Write/Control Pin	|This pin toggles the display among the read or writes operation, and it is connected to a microcontroller unit pin to get either 0 or 1 (0 = Write Operation, and 1 = Read Operation).|
|6|Enable/Control Pin	|This pin should be held high to execute Read/Write process, and it is connected to the microcontroller unit & constantly held high.|
|7| to 14	Data Pins |These pins are used to send data to the display. These pins are connected in two-wire modes like 4-wire mode and 8-wire mode. In 4-wire mode, only four pins are connected to the microcontroller unit like 0 to 3, whereas in 8-wire mode, 8-pins are connected to microcontroller unit like 0 to 7.|
|15|	+ve pin of the LED|	This pin is connected to +5V|
|16|	-ve pin of the LED|	This pin is connected to GND.|

