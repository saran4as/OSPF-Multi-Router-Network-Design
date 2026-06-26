# OSPF Multi-Router Network Design

##  Project Overview
This project demonstrates a simulated enterprise network using OSPF (Open Shortest Path First) in Cisco Packet Tracer. The design includes 3 routers connected via serial DCE/DTE links with multiple LAN networks, enabling dynamic routing between all subnets.

##  Tech Stack
- Cisco Packet Tracer  
- OSPF (Open Shortest Path First)  
- Dynamic Routing Protocols  
- IP Subnetting (/30 & /24)  
- WAN Serial Links (DCE/DTE)

##  Network Design
- 3 Router topology (R1, R2, R3)  
- Area 0 (Backbone OSPF Area)  
- LAN networks connected via switches and PCs  
- Point-to-point WAN links using /30 subnetting  

##  Configuration Highlights
- Configured OSPF on all routers  
- Assigned unique Router IDs  
- Used wildcard masks for network advertisement  
- Established neighbor adjacency (FULL state)  
- Verified routing tables for dynamic route learning  

##  IP Addressing Scheme
- WAN Links: /30 subnet  
- LAN Networks: /24 subnet  

## Results
- OSPF neighbors successfully formed  
- All routes dynamically exchanged  
- Full connectivity between all 6 PCs across subnets  
- Verified end-to-end communication  
