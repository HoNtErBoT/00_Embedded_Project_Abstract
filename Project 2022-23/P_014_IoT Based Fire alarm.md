# IoT Based Fire alarm
## Abstract
Fire alarm systems are essential in alerting people before fire engulfs their homes. However, fire alarm systems, today, require a lot of wiring and labor to be installed. This discourages users from installing them in their homes. Therefore, we are proposing an IoT based wireless fire alarm system that is easy to install. The proposed system is wireless sensor network that consists of several nodes distributed over the house. Each of these nodes consists of a microcontroller (ESP8266 node-MCU) connected to flame, Methane and Carbon Monoxide (CO) etc. sensors that continuously sense the surrounding environment to detect the presence of fire. The nodes create their own Wi-Fi network. These nodes communicate with a centralized node. Once fire is detected by a node, it sends a signal to a centralized node that is triggered to send an SMS to the fire department and the user, and alert the house by producing a local alarm. The user can also get information about the status. The sensing nodes create a mesh network and they are linked to the central node via a bridge node.<br><br>
![image](https://user-images.githubusercontent.com/109785046/216280405-1a81b15f-c316-44e7-984d-272b4d9feb9f.png)

## Block diagram
![IoT Based Fire alarm](https://user-images.githubusercontent.com/109785046/216280246-7d1ba7a5-e018-47ff-9fc4-c50376895975.png)
