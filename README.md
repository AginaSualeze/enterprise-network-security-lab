# enterprise-network-security-lab
Secure enterprise network design featuring multi-ISP BGP routing, FortiGate firewalls, site-to-site VPN, and monitoring-ready architecture.
Secure Enterprise Network Design & Architecture (Capstone Project)
Overview

This project demonstrates the design and implementation of a secure enterprise network architecture using industry best practices.
The lab simulates a real-world enterprise environment with multi-ISP connectivity, BGP routing, firewall-enforced security, site-to-site VPN connectivity, and monitoring-ready design.

The goal was to build a resilient, scalable, and security-focused network, not just a functional lab.

# Architecture Summary

The network is designed using a layered enterprise model:
. Service Provider Layer

Multiple ISPs with distinct Autonomous System Numbers (ASNs)

BGP used for dynamic routing and redundancy

Edge Routing Layer

 Dedicated routers handling WAN routing and ISP peering
 Separation of routing and security responsibilities

## Perimeter Security Layer

. FortiGate firewalls enforcing security policies

. NAT, traffic inspection, and VPN termination

. Internal Enterprise Network

. Segmented LAN using private IP addressing

. Controlled access between internal subnets

## Key Technologies Used

1. FortiGate Firewall

2. Cisco Routers

3. BGP (Multi-ISP)

4. IPsec Site-to-Site VPN

5. VLANs & Subnetting

6. NAT & Firewall Policies

7. Centralized Logging (Monitoring-ready)

8. EVE-NG Lab Environment

## Site-to-Site VPN

 A permanent IPsec site-to-site VPN was configured between two FortiGate firewalls to securely interconnect separate enterprise sites over untrusted networks.

## Purpose:

Encrypted inter-site communication

Secure resource sharing

Cost-effective WAN extension

Real-world branch-to-HQ simulation

## Security Design Principles

Defense-in-depth

Least privilege firewall rules
Network segmentation

Encrypted WAN communication

Centralized visibility and logging readiness

## Monitoring & Visibility

Network monitoring platforms

Fortigate log

This enables traffic analysis, threat detection, and incident investigation.

## Use Cases Simulated

Multi-ISP enterprise internet connectivity

Secure branch-to-branch communication

Enterprise perimeter defense

SOC and threat-hunting readiness

Hybrid cloud–ready architecture

## What I Learned

Designing networks for failure and resilience

Real-world BGP behavior and ISP redundancy

Firewall-based security enforcement

VPN integration into enterprise routing

Translating business requirements into technical architecture
