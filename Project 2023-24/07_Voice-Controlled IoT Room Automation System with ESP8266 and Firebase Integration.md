# Voice-Controlled IoT Room Automation System with ESP8266 and Firebase Integration

### Abstract:

This project aims to create an innovative Voice-Controlled IoT Room Automation System using widely available components such as the ESP8266 microcontroller, a 5V 4-channel relay module, and Google Firebase for remote data storage. The system is designed to enable users to control home appliances with voice commands through a dedicated Android application, providing a seamless and convenient smart home experience.

The core of the system relies on the ESP8266, a versatile and cost-effective Wi-Fi-enabled microcontroller, acting as the bridge between the user's voice commands and the physical home appliances. To interface with the relay module, 2N2222 transistors are employed, serving as switches to control the high-power devices securely. Additionally, a 5V regulator (7805) ensures a stable power supply for the ESP8266 and the relay module, while a 9V regulator (7809) powers other components.

The Android application serves as the user interface, incorporating voice recognition capabilities. Upon recognizing voice commands, the application sends corresponding instructions to Google Firebase, a cloud-based database. The ESP8266, in turn, fetches these commands from the database, interpreting them to trigger the appropriate signals for the 2N2222 transistors. Consequently, the transistors control the 4-channel relay, allowing users to remotely manage their home appliances.

The integration of Firebase as the central database adds a layer of accessibility, enabling users to control their home devices from anywhere in the world. The use of IoT technology facilitates real-time communication between the Android application and the ESP8266, transforming ordinary appliances into smart, voice-responsive devices. This project showcases the potential of combining readily available hardware components with cloud-based solutions to create an intelligent and user-friendly home automation system.

## Project Budget Plan for Voice-Controlled IoT Room Automation System (in Indian Rupees)

### Hardware Components:
---------------------
ESP8266 Microcontroller: ₹400 x 1 units = ₹400
5V 4-Channel Relay Module: ₹300 x 1 units = ₹300
2N2222 Transistors: ₹30 x 4 units = ₹120
7805 Voltage Regulator: ₹16 x 3 units = ₹48
7809 Voltage Regulator: ₹12 x 2 unit = ₹24
Miscellaneous Components (wires, connectors, PCB, Casing, Power supplay): ₹1,900
Total Hardware Cost: ₹2,792


### Software and Development:
--------------------------
Android Application Development: ₹_____ (Please Check rate of android developer)
Firebase Subscription (Starter Plan): ₹0/month  = ₹0
Embedded Systems Programming (if outsourcing): ₹5,000
Total Software and Development Cost: ₹5000+Android developer charge

### Testing and Prototyping:
-------------------------
Prototyping Boards and Materials: ₹600
Testing Tools and Equipment: ₹1,000
Total Testing and Prototyping Cost: ₹1,600

### Contingency:
------------
Unforeseen Expenses (10% of total budget): ₹----
Total Contingency: ₹-----
