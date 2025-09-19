# CCNA Lab Portfolio - Networking Foundations

This repository contains my completed labs for the Cisco CCNA 200-301 certification. The projects follow the curriculum from Jeremy's IT Lab and are designed to apply theoretical networking concepts to practical, hands-on scenarios using Cisco Packet Tracer.

Each project demonstrates foundational skills in routing, switching, and network security.

## Table of Contents
- [Network Fundamentals](#network-fundamentals)
- [LAN Switching Technologies](#lan-switching-technologies)
- [IP Connectivity](#ip-connectivity)
- [IP Services](#ip-services)
- [Security Fundamentals](#security-fundamentals)
- [Automation and Programmability](#automation-and-programmability)
- [Routing](#routing)

***

### Network Fundamentals

This section showcases my foundational skills in building network topologies, configuring basic device settings, and understanding IP addressing.

- **Basic Device Connectivity**: A foundational lab demonstrating how to connect routers, switches, and PCs to form a simple network topology. [[Link to file]](network-fundamentals/connecting-devices-lab/README.md/)

- **OSI Model**: This lab showcases PDU information in different devices as data gets transferred through the network. [[Link to file]](network-fundamentals/osi-model-lab/README.md/)

- **Subnetting VLSM**: This lab is an excellent highlight of subnetting and routing a VLSM network. We configure each subnet individually across 4 LANs and then configure a point-to-point connection between two routers. Doing so allows efficient use of address space as well as reachability across the entire network. [[Link to file]](network-fundamentals/subnetting-vlsm-lab/README.md/)

***

### LAN Switching Technologies

This section focuses on my ability to configure and troubleshoot LAN switching protocols and features.

- **Analyzing Ethernet Switching**: Using the 'ping' command, we can see how switches dynamically learn MAC addresses when their MAC address and ARP tables are completely empty. [[Link to file]](lan-switching/analyzing-ethernet-switching-lab/README.md/)

- **VLANs Lab**: In this lab, we are introduced to VLANs. We are using access ports (not trunk ports) in this lab. An access port belongs to a single VLAN. Upon configuring the network for all 3 VLANs, we should have connectivity across the network and our router doing all of our inter-VLAN routing. [[Link to file]](lan-switching/vlans-lab/README.md/)

- **VLANs Trunking Lab**: This lab is a step up from the normal VLANs lab. We use 'trunk' mode to host multiple VLANs on a single physical conneciton between routers and switches. We logically separate them using subinterfaces on the router. For the switches we simply create and allow the VLANs to ensure each switch can receive traffic for all VLANs it is associated with. We also configure native VLANs in this lab. [[Link to file]](lan-switching/vlans-trunking-lab/README.md/)

- **Multilayer Switching Lab**: In this lab, we will be changing the preset router-on-a-stick (ROAS) configuration to do inter-vlan routing via SVI's on SW2. [[Link to file]](lan-switching/multilayer-switching-lab/README.md/)

- **DTP / VTP Lab**: In this lab, we go through a variety of VTP and DTP configurations throughout a network. [[Link to file]](lan-switching/dtpvtp-lab/README.md/)


***

### IP Connectivity

This section demonstrates my skills in configuring and troubleshooting IP routing protocols and paths.

- **Configuring IP Addresses**: This lab showcases the configuration of a router's interfaces to switches as well as configuring the static IPs of clients connected to those switches. [[Link to file]](ip-connectivity/configuring-ip-addresses-lab/README.md)

- **Configuring Interfaces**: Configuring the interfaces of all switches and routers in a LAN as well as the IP addresses for all end hosts. The goal is to use best practice and disable all unused interfaces in switches and give meaningful descriptions to each connected interface. [[Link to file]](ip-connectivity/configuring-interfaces-lab/README.md)

- **Life of a Packet**: Using CLI and Packet Tracer's simulation mode, we trace how a packet moves through a network. I verified the source / destination MAC addresses at each specified point during the packet's route. The goal was to see how the ethernet frame gets encapsulated and de-encapsulated during the route of a ping. [[Link to file]](ip-connectivity/life-of-a-packet-lab/README.md)

***
### Routing

This section highlights my ability to route throughout a network.

- **Configuring Static Routes**: The goal of this lab is to have a network that is not configured at all. We are to establish a connection betweeen two PCs across the network on opposite sides. [[Link to file]](routing/configuring-static-routes-lab/README.md)

- **Troubleshooting Static Routes**: There are 1 misconfiguration(s) on each router in this lab. Our goal is to go into the CLI and use our skills to find and fix the misconfigurations. By the end of the lab, I will have fixed all of the misconfigurations and PC1 will be able to ping PC2. [[Link to file]](routing/troubleshooting-static-routes-lab/README.md)

***
### IP Services

This section highlights my ability to configure essential network services.



***

### Security Fundamentals

This section showcases my practical knowledge of network security principles and device hardening.

- **Basic Device Security**: Dives into the CLI of some Cisco routers and switches and showcases how to add an unencrypted password, type 7 encrypted password, and MD5 encrypted password. [[Link to file]](security-fundamentals/basic-device-security-lab/README.md/)


***

### Automation and Programmability

This section contains projects focused on network automation concepts using tools like Python and APIs.


