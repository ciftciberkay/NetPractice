*This project has been created as part of the 42 curriculum by beciftci.*

# NetPractice

## Description
This project is a general practical exercise designed to introduce the basics of computer networking. The main goal is to configure small-scale networks by fixing issues related to IP addressing and routing to ensure proper communication between devices.

The project consists of 10 levels of increasing difficulty where we must manually configure IP addresses, subnet masks, and routing tables for hosts, routers, and switches.

## Instructions

### Open the exercises

This repository contains ten exported JSON configurations, from [level1.json](./level1.json) through [level10.json](./level10.json). Obtain the NetPractice exercise package separately through the 42 Intranet. Run its `run.sh` from the extracted exercise directory to open the simulator.

### Use the simulator

1. Enter your 42 login in the simulator.
2. Adjust IP addresses, subnet masks, and routes until the devices can communicate.
3. Use **Get my config** to export each completed level.

### Submission
To submit this project, the 10 exported configuration files (one for each level) have been placed at the root of this Git repository as required.

## Resources
* https://www.youtube.com/watch?v=TAymJsyE-G0
* https://www.calculator.net/ip-subnet-calculator.html

### Networking Concepts
This project relies on the understanding of the following core networking concepts:
* **TCP/IP Addressing:** Understanding IPv4 address classes and structure.
* **Subnet Masks & CIDR:** Calculating network ranges and splitting networks into subnets.
* **Default Gateways:** Configuring exit points for traffic destined for outside networks.
* **Routers and Switches:** Understanding the difference between switching and routing forwarding.
* **Routing Tables:** Static routing and next-hop configuration.
* **OSI Layers:** Troubleshooting connectivity based on network layers.

### AI Usage
As permitted by the subject, AI tools were used to assist in the learning process.
* **Tasks:** AI was used to generate explanations for complex subnetting calculations (e.g., /26 vs /28 masks) and to visualize routing loops in theoretical scenarios.
