**Home Network Infrastructure Overview:**

I implemented and managed a robust home network infrastructure using a hierarchical topology to ensure efficient data flow and connectivity throughout my residence.

**Core Layer:**
- Employed a TP-Link ER605 V2 Wired Gigabit VPN Router as the central gateway for internet connectivity, facilitating secure remote access with VPN technology.

**Distribution Layer:**
- Deployed a TP-Link TL-SG116E 16 Port Gigabit Switch to manage home network traffic effectively, utilizing advanced features such as QoS, VLANs, and LAG for optimized performance and segmentation.

**Access Layer:**
- Integrated an AMD Ryzen 7 5700U Mini PC as a high-performance workstation and server, hosting a variety of applications and services, thus enhancing network functionality.
- Set up both Linux Ubuntu Server and Windows 2019 AD Server for crucial home services, including file sharing, web applications, user authentication, and policy management.

**Wireless Connectivity:**
- Configured TP-Link AX1800 WiFi 6 Router (Archer AX21) to provide stable and fast wireless access throughout the house, supporting WiFi 6 technology for enhanced connectivity.

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

**Key Activities:**
- Designed and set up the home network infrastructure to optimize for personal performance, security, and scalability needs.
- Performed routine maintenance and monitoring to ensure network reliability and performance in my home environment.
- Troubleshot and resolved network issues independently, maintaining optimal network uptime and functionality.
- Leveraged my technical expertise to continually refine and enhance the network setup to meet my evolving home usage requirements.




