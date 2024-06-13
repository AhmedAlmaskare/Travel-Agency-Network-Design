# International Travel Agency Network Implementation
## Project Overview
This repository contains the configurations and supporting documents for the CCNP SWITCH practice skills exam, focused on designing and implementing a switched network for the International Travel Agency. The project aims to establish a robust, scalable, and secure network using Cisco technologies, following specific requirements outlined in this project.
## Network Topology
The network consists of two distribution layer switches (DLS1 and DLS2) and two access layer switches (ALS1 and ALS2). A topology diagram is included in the repository to provide a visual understanding of the network structure.
## Technologies Used
•	Cisco switches and router
•	Layer 3 Etherchannel using LACP and PAgP
•	VLAN and VTP configurations
•	Multiple Spanning Tree (MST)
•	Hot Standby Router Protocol version 2 (HSRPv2)
•	Enhanced Interior Gateway Routing Protocol (EIGRP)
•	Various security features such as DHCP snooping, PortFast, BPDUguard, and UDLD
## Files Included
* Topology_Diagram.pdf: Network topology diagram illustrating the connection and configuration of switches.
* Switch_Configurations/: Folder containing the configuration files for each switch.
* DLS1_config.txt
* DLS2_config.txt
* ALS1_config.txt
* ALS2_config.txt
* Verification_Screenshots/: Folder with screenshots demonstrating the successful application and operation of configurations.
* Implementation_Instructions.txt: Detailed instructions followed for configuring the network as per the requirements.
## Configuration Highlights
* Implementation of Layer 3 Etherchannel between DLS1 and DLS2 using LACP.
* Setup of VLANs for different departments and purposes, including special configurations for management and voice VLANs.
* Security enhancements including SSH setup, port security, and access control lists (ACLs) to regulate network access and enhance security.
* Routing and redundancy configurations using EIGRP and HSRP to ensure network reliability and fault tolerance.
## Project Outcomes
The configured network meets the requirements set out in the CCNP SWITCH project providing a resilient and secure network environment for the International Travel Agency. This project demonstrates the application of advanced networking principles and Cisco configurations in a real-world scenario.
## Conclusion
This repository serves as a comprehensive guide and reference for setting up a switched network tailored to specific operational needs, showcasing skills in network design, configuration, and troubleshooting.
Contact Information
For any inquiries or further information regarding the network setup and configurations, please contact Eng.AhmedAlmaskari@gmail.com
