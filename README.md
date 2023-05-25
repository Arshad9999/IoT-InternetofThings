# IoT-InternetofThings

# Practical-1

## OBJECTIVE: To implement the types of topologies such as Star, Hub, Mesh and Bus  using Cisco  Packet Tracer

## Tools Used : Cisco Packet Tracer
Description: 
Cisco Packet Tracer is a network simulation tool developed by Cisco Systems. It is used for designing, configuring, and troubleshooting computer networks. The software allows users to create network topologies, add devices such as routers, switches, PCs, and servers, and simulate the flow of data packets between them.

Packet Tracer provides a virtual environment where users can experiment with different network configurations and protocols without the need for physical hardware. It includes a range of features and functions that enable users to configure and test network devices, set up virtual LANs, configure network security, and simulate network traffic.

## Types of Topologies:
In computer networking, a network topology refers to the physical or logical arrangement of devices, nodes, and links in a network. There are several types of network topologies, including:

Bus Topology: In this topology, all devices are connected to a common communication line, also known as a bus. The devices share the same communication channel, and messages sent by one device are received by all other devices on the network.

Star Topology: In this topology, all devices are connected to a central hub or switch, which acts as a central point of communication. The hub or switch receives messages from one device and then forwards them to the intended recipient.

Ring Topology: In this topology, all devices are connected in a circular or ring-like structure, with each device connected to the next and the last device connected to the first. Messages travel in a single direction around the ring until they reach their intended recipient.

Mesh Topology: In this topology, all devices are connected to every other device in the network. This topology provides redundancy and fault tolerance as there are multiple paths for data to travel from one device to another.

Tree Topology: In this topology, devices are arranged in a hierarchical structure, similar to a tree, with a root node at the top and branches below. The root node connects to a primary hub, which in turn connects to secondary hubs or switches, which connect to end devices.

Hybrid Topology: This topology combines two or more different types of topologies, such as a combination of bus and star topology, or a combination of mesh and tree topology, to create a customized network design that meets specific requirements.

<img width="514" alt="image" src="https://user-images.githubusercontent.com/93732499/220858954-3135aaf3-e521-41bb-90d9-091f79f83150.png">

# Practical-2

## OBJECTIVE: To implement the Wireless and Wired Networks and understand the OSI  layer model  using Cisco  Packet Tracer

## Wireless and Wired Networks: the OSI  layer model
Wireless and wired networks refer to two different types of computer networks based on the method of data transmission. Wired networks use physical cables, such as copper or fiber optic cables, to transmit data between devices, while wireless networks use radio waves to transmit data over the air.

Wireless networks have several advantages over wired networks, including greater mobility, easier installation and scalability, and lower cost of maintenance. However, they are also more susceptible to interference and security threats.

On the other hand, wired networks offer higher speeds, greater reliability, and more secure data transmission. However, they are also more expensive to install and maintain, and less flexible in terms of mobility.

The OSI (Open Systems Interconnection) layer model is a conceptual framework used to describe the functions and protocols of network communication. It consists of seven layers, each responsible for a specific aspect of network communication:

Physical Layer: This layer deals with the physical transmission of data over the network, such as electrical or optical signals.

Data Link Layer: This layer is responsible for establishing and maintaining a reliable link between two devices, and for detecting and correcting errors in data transmission.

Network Layer: This layer deals with routing data packets between different networks and devices, and provides services such as addressing and packet fragmentation.

Transport Layer: This layer ensures the reliable delivery of data between end-to-end applications, and provides services such as flow control and congestion avoidance.

Session Layer: This layer manages the communication sessions between applications, and provides services such as session establishment, maintenance, and termination.

Presentation Layer: This layer is responsible for the representation and encoding of data in a format that can be understood by applications, and provides services such as encryption and compression.

Application Layer: This layer provides services to end-user applications, such as file transfer, email, and web browsing.

# Practical-3

## OBJECTIVE: To implement the configuration of Routers , Switches and Hubs using Cisco  Packet Tracer

## Router
Routers are networking devices operating at layer 3 or a network layer of the OSI model. They are responsible for receiving, analysing, and forwarding data packets among the connected computer networks. When a data packet arrives, the router inspects the destination address, consults its routing tables to decide the optimal route and then transfers the packet along this route.
 
## Features of Routers
· A router is a layer 3 or network layer device.
· It connects different networks together and sends data packets from one network to another.
· A router can be used both in LANs (Local Area Networks) and WANs (Wide Area Networks).
· It transfers data in the form of IP packets. In order to transmit data, it uses IP address mentioned in the destination field of the IP packet.
· Routers have a routing table in it that is refreshed periodically according to the changes in the network. In order to transmit data packets, it consults the table and uses a routing protocol.
· In order to prepare or refresh the routing table, routers share information among each other.
· Routers provide protection against broadcast storms.
 
## Types of Routers
A variety of routers are available depending upon their usages. The main types of routers are −
· Wireless Router − They provide WiFi connection WiFi devices like laptops, smartphones etc. They can also provide standard Ethernet routing. For indoor connections, the range is 150 feet while its 300 feet for outdoor connections.
· Broadband Routers − They are used to connect to the Internet through telephone and to use voice over Internet Protocol (VoIP) technology for providing high-speed Internet access. They are configured and provided by the Internet Service Provider (ISP).
· Core Routers − They can route data packets within a given network, but cannot route the packets between the networks. They helps to link all devices within a network thus forming the backbone of network. It is used by ISP and communication interfaces.
 
## Switches
Switches are networking devices operating at layer 2 or a data link layer of the OSI model. They connect devices in a network and use packet switching to send, receive or forward data packets or data frames over the network.
A switch has many ports, to which computers are plugged in. When a data frame arrives at any port of a network switch, it examines the destination address, performs necessary checks and sends the frame to the corresponding device(s).It supports unicast, multicast as well as broadcast communications.
 
# Types of Switches
There are variety of switches that can be broadly categorised into 4 types −

· Unmanaged Switch − These are inexpensive switches commonly used in home networks and small businesses. They can be set up by simply plugging in to the network, after which they instantly start operating. When more devices needs to be added, more switches are simply added by this plug and play method. They are referred to as u managed since they do not require to be configured or monitored.
· Managed Switch − These are costly switches that are used in organisations with large and complex networks, since they can be customised to augment the functionalities of a standard switch. The augmented features may be QoS (Quality of Service) like higher security levels, better precision control and complete network management. Despite their cost, they are preferred in growing organisations due to their scalability and flexibility. Simple Network Management Protocol (SNMP) is used for configuring managed switches.
· LAN Switch − Local Area Network (LAN) switches connects devices in the internal LAN of an organisation. They are also referred as Ethernet switches or data switches. These switches are particularly helpful in reducing network congestion or bottlenecks. They allocate bandwidth in a manner so that there is no overlapping of data packets in a network.
· PoE Switch − Power over Ethernet (PoE) switches are used in PoE Gogabit Ethernets. PoE technology combine data and power transmission over the same cable so that devices connected to it can receive both electricity as well as data over the same line. PoE switches offer greater flexibility and simplifies the cabling connections.
 
## Hubs
A hub is a physical layer networking device which is used to connect multiple devices in a network. They are generally used to connect computers in a LAN.
A hub has many ports in it. A computer which intends to be connected to the network is plugged in to one of these ports. When a data frame arrives at a port, it is broadcast to every other port, without considering whether it is destined for a particular destination or not.

# Practical-4

## OBJECTIVE: To implement the Inter VLAN Routing using Cisco Packet Tracer

## The Inter VLAN Routing
A VLAN is a switched network that is logically segmented by function, project team, or application, without regard to the physical locations of the users. VLANs have the same attributes as physical LANs, but you can group end stations even if they are not physically located on the same LAN segment. Any switch port can belong to a VLAN, and unicast, broadcast, and multicast packets are forwarded and flooded only to end stations in the VLAN. Each VLAN is considered a logical network, and packets destined for stations that do not belong to the VLAN must be forwarded through a router or a switch supporting fallback bridging.
 
VLANs are often associated with IP subnetworks. For example, all the end stations in a particular IP subnet belong to the same VLAN. Interface VLAN membership on the switch is assigned manually on an interface-by-interface basis. When you assign switch interfaces to VLANs by using this method, it is known as interface-based, or static, VLAN membership. Traffic between VLANs must be routed or fallback bridged.
 
The switch supports VLANs in VTP client, server, and transparent modes. VLANs are identified by a number from 1 to 4094. VLAN IDs 1002 through 1005 are reserved for Token Ring and FDDI VLANs. VTP only learns normal-range VLANs, with VLAN IDs 1 to 1005; VLAN IDs greater than 1005 are extended-range VLANs and are not stored in the VLAN database. The switch must be in VTP transparent mode when you create VLAN IDs from 1006 to 4094. Although the switch supports a total of 255 (normal range and extended range) VLANs, the number of configured features affects the use of the switch hardware. The switch supports per-VLAN spanning-tree plus (PVST+) or rapid PVST+ with a maximum of 128 spanning-tree instances. One spanning-tree instance is allowed per VLAN. See the “Normal-Range VLAN Configuration Guidelines” section on page 12-5 for more information about the number of spanning-tree instances and the number of VLANs. The switch supports only IEEE 802.1Q trunking methods for sending VLAN traffic over Ethernet ports.
 
Configuring Normal-Range VLANs Normal-range VLANs are VLANs with VLAN IDs 1 to 1005. If the switch is in VTP server or VTP transparent mode, you can add, modify, or remove configurations for VLANs 2 to 1001 in the VLAN database. (VLAN IDs 1 and 1002 to 1005 are automatically created and cannot be removed.) Note When the switch is in VTP transparent mode, you can also create extended-range VLANs (VLANs with IDs from 1006 to 4094), but these VLANs are not saved in the VLAN database. 

# Practical-5

## OBJECTIVE: To implement the virtual private network  (VPN) using Cisco  Packet Tracer

## VPN
 A Virtual Private Network (VPN) connection allows users to access, send, and receive data to and from a private network by means of going through a public or shared network such as the Internet but still ensuring secure connections to an underlying network infrastructure to protect the private network and its resources.
A VPN tunnel establishes a private network that can send data securely using encryption and authentication. Corporate offices mostly use VPN connection since it is both useful and necessary to allow their employees to have access to their private network even if they are outside the office.
The VPN allows a remote host to act as if they were located on the same local network. The router supports 50 tunnels. The VPN Setup Wizard makes it possible to configure a secure connection for site-to-site IPSec tunnel. This feature makes the configuration simple and prevents complex settings and optional parameters. This way, anybody can set up the IPSec tunnel in a fast and efficient manner.

 
 
## Benefits of using a VPN connection
1.   Using a VPN connection helps protect confidential network data and resources.
2.   Provides convenience and accessibility for remote workers or corporate employees since they will be able to easily access the main office without having to be physically present and yet, still maintain the security of the private network and its resources.
3.   Communication using a VPN connection provides a higher level of security compared to other methods of remote communication. Advanced level of technology nowadays makes this possible, thus, protecting the private network from unauthorized access.
4.   Actual geographic locations of the users are protected and not exposed to the public or shared networks like the Internet.
5.   Adding new users or group of users to the network is easy since VPNs are very adjustable. It is possible to make the network grow without the need for additional new components or complicated configurations.

## Risks of using VPN connection
1.   Security risk due to misconfiguration. Since the design and implementation of a VPN can be complicated, it is necessary to entrust the task of configuring the connection to a highly knowledgeable and experienced professional in order to make sure that the security of the private network will not be compromised.
2.   Reliability. Since a VPN connection requires Internet connection, it is important to choose a provider that is proven and tested to provide excellent Internet service and guarantee minimal to no downtime.
3.   Scalability. If it comes to a situation that there is a need to add new infrastructure or set new configurations, technical issues may possibly arise due to incompatibility especially if it involves different products or vendors other than the ones you are already using.
4.   Security issues for mobile devices. Sometimes, when using mobile devices when initiating the VPN connection, security issues may arise especially when using wireless connection. Some unverified providers pose as “free VPN providers” and can even install malware on your computer. Due to this, it is possible to add more security measures to prevent such problems when using mobile devices.
5.   Slow connection speeds. If you are using a VPN client who provides free VPN service, it may be expected that your connection speed would slow down since these providers do not prioritize connection speeds.
The objective of this document is to show you how to configure VPN connection on the RV34x Series Router using the Setup Wizard.
 
# Practical-6

## OBJECTIVE: To implement the Temperature sensor interfacing using Arduino UNO

## Temperature Sensor - LM35:
The LM35 temperature sensor uses a solid-state technique to measure temperature. It utilizes the relationship between the voltage drop across its diode-connected transistor (Vbe) and the temperature. As the temperature increases, the Vbe decreases at a known rate. By amplifying this voltage change, we can generate an analog signal that is directly proportional to the temperature.
The LM35 is straightforward to use. Connect the left pin of the sensor to a power source (4V to 30V), and connect the right pin to ground (assuming the flat side of the sensor is facing you). The middle pin will output an analog voltage that is linearly proportional to the temperature in °C. This relationship is shown in the LM35's output voltage vs. temperature characteristic. It's important to note that the analog output voltage is independent of the power supply.
To convert the voltage output to temperature, we use the formula:
Temperature (°C) = Vout * 100
For example, if the voltage output is 0.5V, the corresponding temperature is 0.5 * 100 = 50 °C.
## Connecting the LM35 Temperature Sensor to Arduino UNO:
Interfacing the LM35 temperature sensor with an Arduino UNO is straightforward. You need to connect three pins: two for power and one for reading the sensor value.
1. Connect the LM35's positive voltage pin ('+Vs') to the 5V pin on the Arduino.
2. Connect the LM35's ground pin ('GND') to the ground (GND) pin on the Arduino.
3. Connect the LM35's Vout pin (analog output) to analog pin A0 on the Arduino.

# Practical-7

## OBJECTIVE: To implement the Pressure sensor interfacing using Arduino UNO

## Pressure Sensor - MPL3115A2:
The MPL3115A2 is a digital pressure sensor from Freescale that provides accurate pressure and temperature readings. It utilizes the I2C (Inter-Integrated Circuit) bus for data exchange with the Arduino.
I2C is a two-wire interface that allows multiple devices to be connected on the same bus, making it ideal for sensor communication. The MPL3115A2 sensor can be used in various applications, such as weather stations or altitude measurement systems.
To interface the MPL3115A2 pressure sensor with Arduino, you'll need to connect the sensor to the Arduino's I2C bus. The sensor communicates with the Arduino by sending and receiving data using the I2C protocol.
## Components Required:
1. Arduino Uno or Mega
2. MPL3115A2 Pressure Sensor
3. Connecting wires
4. Breadboard

# Practical-8

## OBJECTIVE: To implement the Light Sensor interfacing using Arduino UNO

## Light Sensor:
A light sensor, also known as a photoresistor or LDR (Light Dependent Resistor), is a component that changes its resistance based on the intensity of light falling on it. This property can be utilized to automatically control the lighting system in a room.
In this practical, we will interface a light sensor with Arduino UNO to control an LED based on the ambient light conditions. When the room gets dark, the LED will automatically turn on to eliminate the darkness.

## Steps:
1. Connect the 3.3V pin of Arduino to the positive rail and the ground pin to the negative rail of the breadboard.
Connections for LDR Sensor:
2. Place the LDR on the breadboard and connect a 10k ohm resistor to one of the legs of the LDR.
3. Connect the A0 pin of Arduino to the same column of the resistor and LDR. This will fetch the intensity of light from the LDR to the Arduino through the A0 pin.
4. Connect the other end of the resistor to the negative rail of the breadboard.
5. Connect the other end of the LDR to the positive rail of the breadboard.
Connections for LED:
6. Place the LED on the breadboard and connect the positive end of the LED to a 220 ohm resistor.
7. Connect the other end of the resistor to pin 13 of the Arduino.
8. Connect the negative end of the LED to the negative rail of the breadboard.

The setup is now ready. Now, load the following code into the Arduino IDE and upload it to the Arduino. Monitor the light intensity near the LDR and observe the LED behavior based on the ambient light conditions.


# Practical-9

## OBJECTIVE: To implement the LED blink using the Raspberry Pi

In this practical, we will build a simple LED circuit and make it controllable from the Raspberry Pi using the General-Purpose Input/Output (GPIO) pins. The GPIO pins on the Raspberry Pi allow us to interface with external devices, such as LEDs, sensors, and more.
## LED Circuit:
A basic LED circuit consists of an LED and a current-limiting resistor. The resistor is essential to limit the current flowing through the LED and prevent damage to both the LED and the Raspberry Pi. The resistor value is calculated based on the forward voltage (VF) and forward current (IF) specifications of the LED, as well as the output voltage of the Raspberry Pi.

## To implement the LED blink, follow these steps:
1. Gather the required components:
    * Raspberry Pi
    * USB cable
    * LED
    * Breadboard
    * SD card and adapter (minimum 4GB)
    * LAN cable
    * 50-ohm resistor
    * Jumper wires (2)
2. Design the LED circuit:
    * Connect the longer leg of the LED (anode) to one end of the 50-ohm resistor.
    * Connect the other end of the resistor to the GPIO pin on the Raspberry Pi (e.g., GPIO 18).
    * Connect the shorter leg of the LED (cathode) to the ground (GND) pin on the Raspberry Pi.
3. Connect the Raspberry Pi:
    * Power the Raspberry Pi using the USB cable and connect it to a power source.
    * Connect the LAN cable to the Raspberry Pi for network connectivity.
4. Prepare the Raspberry Pi:
    * Insert the SD card with the appropriate operating system (e.g., Raspbian) into the Raspberry Pi.
    * Connect a monitor, keyboard, and mouse to the Raspberry Pi if needed.
5. Write and run the code:
    * Open a code editor or IDE on the Raspberry Pi.
    * Import the RPi.GPIO library and necessary modules.
    * Set the GPIO mode and configure the GPIO pin (e.g., GPIO 18) as an output.
    * Use the GPIO.output() function to control the state of the GPIO pin and toggle the LED on and off.
    * Add a delay using the time.sleep() function to create the blinking effect.
    * Run the code and observe the LED blinking.

# Practical-10

## OBJECTIVE: To implement the Motion Sensor using the Raspberry Pi

In this project, we will learn how to interface a Passive Infrared (PIR) motion sensor with Raspberry Pi. The PIR sensor detects changes in infrared radiation emitted by a person, enabling us to create a motion detection alarm system as a DIY project.

PIR sensors, also known as IR motion sensors or pyroelectric sensors, detect infrared radiation emitted by living and non-living objects with a temperature greater than absolute zero. These emitted infrared radiations are not visible to humans, as their wavelength is greater than that of visible light.

The PIR sensor used in this project has three pins: VCC, DATA, and GND. Additionally, it has two potentiometers for adjusting the sensitivity and output timing of the sensor.

Components Required:

Raspberry Pi 3 Model B
PIR Sensor
5V Buzzer
Connecting wires
Mini breadboard
Power supply
Computer
Circuit Design:

Connect the VCC pin of the PIR motion sensor to the +5V pin of the Raspberry Pi.
Connect the GND pin of the PIR motion sensor to the GND pin of the Raspberry Pi.
Connect the DATA pin of the PIR motion sensor to GPIO 23 (Physical Pin 16) of the Raspberry Pi.
Connect one pin of the 5V buzzer to GPIO 24 (Physical Pin 18) of the Raspberry Pi.
Connect the other pin of the buzzer to GND.
