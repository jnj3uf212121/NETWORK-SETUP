**Network Infrastructure Overview:**

Implemented and managed a robust network infrastructure featuring a hierarchical topology, ensuring efficient data flow and connectivity across all layers.

**Core Layer:**
- Utilized TP-Link ER605 V2 Wired Gigabit VPN Router as the central gateway for internet connectivity and secure remote access via VPN technology.

**Distribution Layer:**
- Deployed TP-Link TL-SG116E 16 Port Gigabit Switch to efficiently manage network traffic, incorporating advanced features such as QoS, VLANs, and LAG for optimized performance and segmentation.

**Access Layer:**
- Integrated AMD Ryzen 7 5700U Mini PC as a high-performance workstation and server for diverse applications, enhancing network accessibility and functionality.
- Leveraged Linux Ubuntu Server and Windows 2019 AD Server for hosting critical services, including file sharing, web applications, user authentication, and policy enforcement.

**Wireless Connectivity:**
- Established wireless access points using TP-Link AX1800 WiFi 6 Router (Archer AX21), ensuring seamless connectivity for mobile devices and laptops with support for WiFi 6 technology.

**Visual Representation:**

```
Internet
   |
Xfinity WiFi Router (ISP provided)
   | (in bridge mode)
TP-Link ER605 V2 Wired Gigabit VPN Router
   |
   |--- TP-Link TL-SG116E 16 Port Gigabit Switch
   |               |                |
   |               |                |
   |               |                |
   |            Wired             Wired
   |         Devices (*)       AMD Ryzen 7         
   |                             5700U Mini PC        
   |                             |
   |                         Windows 11 Pro (Hyper V)
   |                             |
   |                   -----------------------
   |                   |                     |
   |                 Ubuntu Server             Windows Server 2019 AD
   |                   |                     |
   |            Other Wired Devices        Other Wired Devices
   |            
   |--- TP-Link AX1800 WiFi 6 Router (Archer AX21) -- Wireless Network
           |                  |                 |
           |                  |                 |
           |                  |                 |
        Wireless          Wireless          Wireless
       Devices (*)       AMD Ryzen 7         Other Wireless
                         5700U Mini PC        Devices

```


**Key Responsibilities:**
- Conceptualized and configured the network architecture to align with organizational objectives for performance, security, and scalability.
- Conducted routine maintenance and monitoring activities to uphold network uptime and reliability.
- Collaborated closely with cross-functional teams to swiftly troubleshoot and resolve network issues, minimizing disruptions to operational workflows.
- Offered expert technical support and guidance to optimize network performance and adapt to evolving business requirements.

