# SME-Network-Design

This repository contains the solution for the Small-Medium Business (SME) network design. The network design involves designing, building, and testing a network infrastructure for an SME with three departments: Engineering, Sales, and Management. The network should accommodate the current needs of the departments and also account for future growth and changes in traffic patterns.

The primary goal of this assignment is to propose a network design that meets the requirements of the SME, taking into consideration the different departments, their sub-departments, traffic patterns, growth projections, and monitoring needs. The assignment highlights the following key points:

Network Structure,
Traffic Patterns,
Growth and Changes,
Monitoring Requirements.
Proposed Solution: To address the requirements, the following network design has been proposed:

Network Hierarchy: The network follows a hierarchical design, with core, distribution, and access layers. This design allows for scalability, resiliency, and efficient traffic routing.

Subnetting: Each sub-department is assigned to its own subnet. This ensures efficient IP address management, security, and proper segmentation of network traffic.

Layer 2 and Layer 3 Devices: The network includes a combination of layer 2 and layer 3 devices to provide appropriate connectivity and routing. Layer 2 switches handle local traffic within each department, while layer 3 routers manage inter-departmental communication.

VPN Setup: A VPN server is set up to cater to remote salespeople. This server allows secure access to the main office network, ensuring confidentiality and data integrity.

Monitoring Solution: For monitoring, a combination of network monitoring tools is proposed. For regular network links, tools that provide link status, utilization, and historical data are suggested. Critical components like Service Production Units (SPUs) are monitored more frequently, at a 10-second interval, to ensure their availability.

Future Growth: The network design takes into account the anticipated growth in staff and customer numbers. It considers the addition of new services and the merging of engineering groups.
