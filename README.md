# Tech-Solutions-Inc
Design and configure a network for Tech Solutions Inc., a fictional company. The network should support multiple departments, ensure secure communication, and provide internet access. The project will involve configuring routers, switches, VLANs, DHCP, and security features.

Project Overview:

Network Design:

Headquarters: Includes various departments like HR, Sales, R&D, and IT.
Remote Office: A smaller site connected to the headquarters.
Internet Access: A connection to simulate external internet access.
VPN: For secure remote access to the company's network.
Components:

Routers: 2 (for HQ and Remote Office)
Switches: 4 (one for each department in HQ and one for the Remote Office)
PCs: 20 (5 per department)
Servers: 2 (one for DHCP and one for internal web hosting)
Firewall: 1 (to manage security between the internal network and the internet)
Wireless Access Points: 2 (for wireless connectivity)
Network Cables: As needed
IP Addressing:

HQ Network: 192.168.1.0/24
Remote Office Network: 192.168.2.0/24
Management Network: 192.168.3.0/24 (for devices like the firewall and VPN server)
VLANs for different departments:
HR: VLAN 10
Sales: VLAN 20
R&D: VLAN 30
IT: VLAN 40
Configuration Steps:

A. Network Design:

HQ Setup:

Connect the router to the internet.
Configure VLANs on the switch.
Set up DHCP on the router or a dedicated server for VLAN-specific IP assignments.
Configure inter-VLAN routing on the router.
Remote Office Setup:

Connect the router to HQ router via a serial link.
Configure VLANs and IP addressing on the switch.
Set up DHCP if needed.
Internet Access:

Configure NAT on the HQ router to allow internal devices to access the internet.
VPN Setup:

Configure a VPN server to allow remote access from the internet.
Set up VPN client configurations on remote PCs.
Firewall:

Place the firewall between the HQ router and the internet.
Configure rules to allow necessary traffic and block unwanted traffic.
Wireless Access:

Connect wireless access points to the network.
Configure SSIDs and security settings for wireless clients.
![image](https://github.com/user-attachments/assets/d8df184b-d21a-4ab1-8719-8dd0d008b5e4)
