### Network Topology Overview

The topology consists of a **core layer** with the TP-Link ER605 Router for internet connectivity and security functions, a **distribution layer** with the TP-Link TL-SG116E Switch to manage traffic between devices, and an **access layer** where the end devices, including the Mini PC, servers, and WiFi access, are connected.

#### Core Layer

1. **TP-Link ER605 V2 Wired Gigabit VPN Router**:
   - This router acts as the gateway to the internet. It handles external traffic from and to the network through up to 3 WAN connections for load balancing or failover. It's also responsible for VPN connections, ensuring secure remote access.

#### Distribution Layer

2. **TP-Link TL-SG116E 16 Port Gigabit Switch**:
   - The switch serves as the central hub for all wired network communications. It connects to the router and distributes network traffic to all devices in the network. It supports advanced features like QoS, VLANs, IGMP, and LAG for traffic management and network segmentation.

#### Access Layer

3. **AMD Ryzen 7 5700U Mini PC**:
   - This high-performance PC can be used as a workstation or a server for specific applications. It connects to the switch for network access.

4. **Linux Ubuntu Server**:
   - This server can host various services such as file sharing, web applications, or database services. It connects to the switch, allowing it to serve clients within the network or on the internet through the router.

5. **Windows 2019 AD Server**:
   - Essential for managing domain services, user authentication, and policy enforcement in a Windows environment. It connects to the switch for network access and to manage authentication and policies for devices and users.

6. **TP-Link AX1800 WiFi 6 Router (Archer AX21)**:
   - Provides wireless access to the network for mobile devices and laptops. It connects to the switch, allowing WiFi devices to access resources within the local network and the internet. This router supports WiFi 6 for improved bandwidth and efficiency.

#### Visual Representation

```
Internet
   |
Xfinity WiFi Router (ISP provided)
   | (in bridge mode)
TP-Link ER605 V2 Wired Gigabit VPN Router
   |
   |--- TP-Link AX1800 WiFi 6 Router (Archer AX21) -- Wireless Network
           |                  |                 |
           |                  |                 |
           |                  |                 |
        Wireless          Wireless          Wireless
       Devices (*)       AMD Ryzen 7         Other Wireless
                         5700U Mini PC        Devices
                             |
                        Windows 11 Pro (Hyper V)
                             |
                   -----------------------
                   |                     |
                 Ubuntu Server             Windows Server 2019 AD
```

