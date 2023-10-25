# Smart Blind Walking Stick: AI-Powered Object Detection and Navigation Assistance System

# Abstract:

The "Smart Blind Walking Stick" is an innovative assistive device designed to enhance the mobility and safety of visually impaired individuals. Leveraging the power of AI computer vision, embedded systems, and IoT technology, this project aims to provide real-time object detection and navigation assistance to blind individuals.

The core components of this system include an ESP32CAM module with a camera positioned at the front of the walking stick. The camera captures images of the environment in front of the user, and these images are processed using the YOLO  object detection algorithm. When the user moves with the walking stick, the camera continuously captures images and analyzes them for potential obstacles or objects.

In the event of an obstacle or object detection, the system responds by activating a vibration motor integrated into the handle of the walking stick. This tactile feedback provides immediate notification to the user, helping them navigate safely around obstacles. Moreover, the system offers an additional layer of interaction through a button on the walking stick. When pressed, this button triggers a Bluetooth headset to convey auditory information about the detected object, which is simultaneously displayed on a mobile app on the user's smartphone.

This project combines cutting-edge AI technologies, embedded systems, and IoT connectivity to empower visually impaired individuals with real-time information about their surroundings. By enhancing their situational awareness and offering both tactile and auditory feedback, the "Smart Blind Walking Stick" aims to improve the independence and safety of blind individuals as they navigate the world around them.


## Tools Used:

- ESP32CAM Module: The ESP32CAM module is a hardware component used as the core of the system. It combines the ESP32 microcontroller with a camera module, enabling image capture and processing.

- Camera: The camera is an integral hardware component attached to the walking stick. It captures images of the environment in front of the user.

- Vibration Motor: The vibration motor is a hardware component integrated into the handle of the walking stick. It provides tactile feedback to the user when an obstacle is detected.

- Bluetooth Headset: A Bluetooth headset is used for conveying auditory information to the user about the detected object. This provides an additional layer of interaction,it connects to android phone.

- Button: A button is placed on the walking stick as an input device. When pressed, it triggers the Bluetooth headset to convey auditory information.

- Mobile App: A mobile application is used to display information about detected objects on the user's smartphone.

  ### Hardware used
  - ESP32CAM
  - SPST Push button
  - 16*2 lcd
  - vibration Motor
  - I2c Serial to Parellel Conerter for LCD
  - ESP8266
    

## Software Used:

- AI Computer Vision: You mentioned using AI computer vision, which is a software technology that involves the use of machine learning and deep learning algorithms for object detection in images or video streams. In this case, you specifically mentioned the YOLO (You Only Look Once) object detection algorithm.

- Embedded Systems Software: The ESP32CAM module requires firmware or software to control its operations, including image capture and processing. This would involve embedded systems programming mainly embedded-c.

- IoT Technology: To facilitate communication and data exchange between the walking stick and the user's smartphone, you would likely use IoT (Internet of Things) technology. This could include IoT communication protocols and software development for data transmission here we are using Firebase as a real time database.

- Mobile App Development: The mobile app on the user's smartphone would require mobile app development software, such as Android Studio or MIT appinventor.
  
- Additional Programming: we are writing a python  code to integrate all these components, manage sensor data, and control the system's operations.

 ### Softwares
  - Arduino IDE
  - Pychrm

### Languuage used
- Embedded-c
- Python
    
