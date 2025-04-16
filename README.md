# OSI-Model-Packet-Tracer-Simulation
This lab is designed to help understand and analyze how data flows through the different layers of the OSI model using Cisco Packet Tracer. It includes packet capturing, IP addressing, DHCP interaction, and Layer 7 analysis via simulation mode.
🔧 Objective
This lab is designed to help understand and analyze how data flows through the different layers of the OSI model using Cisco Packet Tracer.
It includes packet capturing, IP addressing, DHCP interaction, and Layer 7 analysis via simulation mode.

🧪 Tasks Performed
Simulation Mode Analysis

Used simulation mode to analyze traffic between devices (PC1, SRV1, Routers, Switches).

Identified OSI layers used in each step of communication (Layers 1 to 7 depending on traffic type).

IP Address Renewal on PC1

Released and renewed IP address on PC1 to observe DHCP Request / Offer / ACK process.

This generated Layer 7 traffic, which was captured and analyzed.

Traffic Flow Observation

Observed packet path from PC1 to SRV1 and beyond (through switches and routers).

Verified correct IP configuration and routing between 192.168.1.0/24 and 10.0.0.0/24 networks.

🔍 OSI Layers Observed

Layer	Protocols/Actions Seen
1 – Physical	Ethernet cables, interfaces (F0/1, G0/1, etc.)
2 – Data Link	MAC addressing, frame delivery (switching)
3 – Network	IP addressing, routing (R1 ↔ R2)
4 – Transport	UDP/TCP segments during DHCP and traffic flows
7 – Application	DHCP traffic, simulated web/app-like traffic
✅ Results
Successfully captured and analyzed multi-layer network traffic.

Understood how each OSI layer is involved in data communication.

Practiced DHCP, routing, and packet analysis using Simulation Mode.

📎 Notes
Use “Event List” panel in Simulation Mode to trace packets.

DHCP traffic shows how devices get IPs dynamically (Layer 7 and below).

Routing between R1 and R2 verified using 10.0.0.0/24 and 192.168.1.0/24 networks.

