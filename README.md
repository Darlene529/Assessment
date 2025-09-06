# Room Automation System – Remote Monitoring using Cisco Packet Tracer

## Aim
To design and implement a room automation system using Cisco Packet Tracer that enables **remote monitoring and automatic control** of electrical appliances, specifically a **fan** and a **room lamp**, by integrating IoT devices, servers, and networking components. The system aims to demonstrate how IoT technology can bring **convenience, energy efficiency, and security** into smart living spaces.  

---

## Problem Statement
Traditional electrical appliances are usually controlled manually using physical switches. This method has several drawbacks:  

- Manual operation is inconvenient as the user must be physically present.  
- Devices may remain ON unnecessarily, leading to energy wastage.  
- No provision exists for remote monitoring and control.  
- Scaling up to include multiple devices becomes complex.  

This project proposes an **IoT-based automation system** that allows appliances to be controlled remotely from a client laptop, using a **server-based architecture** integrated with IoT devices.  

---

## Scope of the Solution
The scope of the project covers the following:  

1. Remote control and monitoring of a fan and lamp via a client device.  
2. Automatic switching of appliances using IoT server-defined rules.  
3. Secure IoT integration with a wireless router (SSID: `Home`, WPA2 security) and RADIUS server.  
4. Scalable design for adding more IoT devices such as AC, lights, or sensors.  
5. Validation of the design through Cisco Packet Tracer before physical deployment.  

---

## Required Components

### Hardware (Simulated in Cisco Packet Tracer)
- Laptop/PC (Client)  
- IoT Fan  
- IoT Lamp  
- Wireless Router  
- Ethernet Switch (MSW)  
- IoT & RADIUS Server  

### Software
- Cisco Packet Tracer (for simulation of IoT network and appliances)  
- Arduino IDE (optional, for future real-world deployment)  

---

## Simulated Circuit

1. **Server Configuration**
   - Static IP: `192.168.0.10`  
   - IoT services enabled for device management  
   - RADIUS server activated for secure access  
   - User credentials created for authentication  

2. **Switch (MSW)**
   - Central device for wired LAN connections  
   - Connects server, router, and client laptop  

3. **Wireless Router**
   - SSID set to `Home`  
   - WPA2 password configured for security  
   - DHCP enabled for automatic IP assignment  

4. **Client Laptop**
   - Connected via switch (LAN) or Wi-Fi  
   - Used to access IoT server through Packet Tracer IoT application  
   - Provides interface to control fan and lamp remotely  

5. **IoT Devices (Fan & Lamp)**
   - Connected wirelessly to router  
   - Registered with IoT server  
   - Assigned IP addresses (static or DHCP)  
   - Default state set to OFF  

---

## Results

- The client laptop successfully switched the IoT Fan and Lamp **ON and OFF** remotely.  
- All devices communicated seamlessly with the server and router.  
- Security was ensured using WPA2 and RADIUS authentication.  
- Automation rules in the server enabled conditional responses for appliances.  
- The system design supports scalability for additional IoT devices.  
- Simulation verified that the system is feasible and ready for physical deployment.  
