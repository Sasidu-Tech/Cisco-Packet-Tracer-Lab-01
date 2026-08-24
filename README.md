🌐 Cisco Packet Tracer – Practical Lab 01

This repository contains my Cisco Packet Tracer Practical Lab 01, focused on basic LAN setup, PC configuration, Router and Switch configuration, connectivity testing, and packet observation.

🎯 Objectives

- Create a basic LAN network topology
- Configure PCs with IP addresses
- Configure a network switch
- Configure a router interface
- Test connectivity using the "ping" command
- Observe packet transmission using Simulation Mode

🛠️ Tools & Technologies

- Cisco Packet Tracer
- PCs
- Cisco Router
- Cisco Switch
- Ethernet connections
- IPv4 Addressing
- ICMP / Ping

🌐 Network Configuration

Example IP addressing:

Device| IP Address| Subnet Mask
PC 1| "192.168.1.10"| "255.255.255.0"
PC 2| "192.168.1.11"| "255.255.255.0"
Router| "192.168.1.1"| "255.255.255.0"
Switch| "192.168.1.2"| "255.255.255.0"

🔧 Practical Tasks

1. Create LAN

Created a basic LAN topology by connecting PCs, a switch, and a router using Ethernet cables.

2. Configure PCs

Configured IPv4 addresses and subnet masks on the connected PCs.

3. Configure Switch

Performed basic switch configuration and configured the management interface.

4. Configure Router

Configured the router interface with an IPv4 address and enabled the interface using:

enable
configure terminal

interface gigabitEthernet 0/0
ip address 192.168.1.1 255.255.255.0
no shutdown

exit
end
write memory

5. Test Connectivity

Used the "ping" command to verify communication between network devices.

Example:

ping 192.168.1.1

Successful ping responses confirmed network connectivity.

6. Observe Packets

Used Simulation Mode in Cisco Packet Tracer to observe how packets travel through the network and understand basic network communication.

📂 Repository Structure

Cisco-Packet-Tracer-Lab-01/
│
├── README.md
├── Lab-01.pkt
│
├── Configurations/
│   ├── Router-Configuration.txt
│   └── Switch-Configuration.txt
│
└── Demo/
    └── Lab-01-Demo.mp4

🎥 Demo Video

The demo video shows the complete practical process, including:

- LAN creation
- PC configuration
- Switch configuration
- Router configuration
- Ping connectivity test
- Packet observation in Simulation Mode

📚 Learning Outcomes

Through this practical, I gained hands-on experience with:

- Basic LAN networking
- IPv4 addressing
- Router configuration
- Switch configuration
- Network connectivity testing
- Packet transmission and network troubleshooting

🚀 Future Learning

This practical is part of my networking learning journey. I will continue developing my knowledge in:

- CCNA
- Routing & Switching
- Network Security
- Cyber Security
- Network Troubleshooting

---

Created by: Sasidu Wishshanka
Focus: Networking | CCNA | Cyber Security
