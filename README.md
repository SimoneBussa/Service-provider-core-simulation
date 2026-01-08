# Service Provider Core Simulation

This project simulates a Service Provider MPLS backbone using **GNS3** and **Cisco IOS/IOS-XE** devices.

The goal is to design and implement a scalable, redundant, and resilient ISP core network capable of providing connectivity between geographically **distributed customer sites**, each with its own internal architecture and different routing / QoS requirements.

The backbone runs **IPv4** and provides **isolated VPN services** using **MPLS L3-VPN** technology. It covers Service Provider well-known design principles, such as:

- Control Plane vs Data Plane separation
- MPLS efficient forwarding and load balancing
- Backup and redundancy
- Scalability

<p align="center">
  <img src="./images/overview-1.JPG" width="600"/>
</p>


NOTE: The full GNS3 source file is available upon request to protect intellectual property. Please reach out at simone.bussa@libero.it if you'd like to review the full project.

---
## Overview

