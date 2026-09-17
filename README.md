# NSE5_FSW-7.2-FortiSwitch-Administrator-Study-Guide-Exam-Preparation
Community study guide for NSE5_FSW-7.2 FortiSwitch Administrator covering FortiSwitch 7.2 administration, VLANs, FortiLink, switching, routing, security, monitoring, troubleshooting, and labs.
# NSE5_FSW-7.2 FortiSwitch Administrator Study Guide

A concise community study guide for FortiSwitch administration with a focus on FortiSwitchOS 7.2, switching, FortiLink, VLANs, routing, security, monitoring, and troubleshooting.

## Introduction

This repository is for network and security professionals preparing for the NSE5_FSW-7.2 FortiSwitch Administrator certification. It combines focused study notes with practical lab ideas based on Fortinet's FortiSwitch 7.2 documentation.

Always verify the current exam code, availability, objectives, and delivery details with Fortinet before booking.

## Exam Overview

| Item | Details |
|---|---|
| Vendor | Fortinet |
| Exam | NSE5_FSW-7.2 FortiSwitch Administrator |
| Product | FortiSwitch / FortiSwitchOS 7.2 |
| Purpose | FortiSwitch administration, configuration, monitoring, and troubleshooting |
| Target candidates | Network/security administrators managing FortiSwitch deployments |
| Prerequisites | Practical networking and FortiSwitch/FortiGate knowledge recommended |
| Exam format | Verify current Fortinet exam page |
| Duration | Verify current Fortinet exam page |
| Questions | Verify current Fortinet exam page |
| Passing score | Verify current Fortinet exam page |

Fortinet's 7.2 documentation covers both standalone FortiSwitch administration and FortiSwitch devices managed through FortiGate. FortiSwitch Manager 7.2 provides another centralized management option. :contentReference[oaicite:0]{index=0}

## Who Should Take It?

This material is suited to network administrators, security engineers, and Fortinet professionals responsible for deploying, configuring, monitoring, and troubleshooting FortiSwitch networks.

A solid understanding of Ethernet switching, VLANs, IP networking, routing, and Fortinet administration is recommended.

## Exam Objectives / Domains

### 1. FortiSwitch Administration
- Initial configuration and management access
- GUI and CLI administration
- Administrator accounts and access profiles
- Firmware, backups, configuration revisions, and system maintenance
- RADIUS and TACACS+ authentication

FortiSwitchOS 7.2 supports administrator profiles and remote administrative authentication. :contentReference[oaicite:1]{index=1}

### 2. Switching and VLANs
- VLAN creation and assignment
- Access and trunk ports
- MAC address learning
- Port configuration and statistics
- Link aggregation
- Port security concepts

### 3. FortiLink and Centralized Management
- FortiLink architecture
- FortiGate-managed FortiSwitch
- Device discovery and authorization
- Managed-switch configuration
- FortiSwitch Manager concepts

FortiSwitch Manager 7.2 supports discovery, authorization, VLANs, ports, PoE, trunks, STP, security features, monitoring, and firmware operations. :contentReference[oaicite:2]{index=2}

### 4. Layer-3 Networking
- Switch virtual interfaces
- Routed VLAN interfaces
- Static routing
- OSPF and BGP fundamentals
- VRRP and ECMP
- Policy-based routing
- ARP and routing troubleshooting

FortiSwitchOS 7.2 documentation includes Layer-3 routing, OSPF, BGP, VRRP, ECMP, and related diagnostic features. :contentReference[oaicite:3]{index=3}

### 5. Switching Security and Monitoring
- DHCP blocking and trusted DHCP
- Dynamic ARP Inspection
- IPv4 source guard
- STP and loop protection
- Storm control
- Port mirroring
- SNMP and sFlow
- Flow tracking

These capabilities are documented in FortiSwitch Manager 7.2 and FortiSwitchOS 7.2 administration materials. :contentReference[oaicite:4]{index=4}

## Detailed Study Notes

**VLANs:** Understand how VLANs separate Layer-2 broadcast domains and how ports are assigned to VLANs. Practice access and trunk configurations.

**FortiLink:** FortiLink connects FortiSwitch to FortiGate for centralized management. Learn discovery, authorization, managed-switch configuration, and common connectivity problems.

**STP:** Understand how Spanning Tree prevents Layer-2 loops. Know the purpose of edge ports and loop protection.

**LACP:** Link aggregation combines multiple physical links into a logical connection. Understand member interfaces, negotiation, redundancy, and capacity considerations.

**PoE:** Power over Ethernet allows compatible devices to receive power through Ethernet cabling. Understand port configuration, power limits, and troubleshooting.

**Layer-3 routing:** FortiSwitch can perform routing functions depending on model and configuration. Understand SVIs, routed VLAN interfaces, static routes, and dynamic routing.

**Security:** DHCP trust, Dynamic ARP Inspection, IPv4 source guard, and related controls help protect switching environments from specific Layer-2 attacks.

**Monitoring:** Learn how to interpret port statistics, MAC tables, logs, SNMP/sFlow data, and diagnostic output.

## Important Concepts

- FortiSwitchOS 7.2
- FortiLink
- VLANs
- Access and trunk ports
- MAC address tables
- LACP/link aggregation
- STP and loop guard
- PoE
- Layer-3 switching
- Static routing
- OSPF and BGP
- VRRP
- DHCP security
- Dynamic ARP Inspection
- IPv4 source guard
- SNMP and sFlow
- Port mirroring
- FortiSwitch Manager

## Practical Examples / Labs

Use an authorized FortiSwitch lab or Fortinet training environment:

1. Configure management access through GUI and CLI.
2. Create VLANs and assign switch ports.
3. Build an access/trunk topology.
4. Connect FortiSwitch to FortiGate using FortiLink.
5. Discover and authorize a managed switch.
6. Configure an LACP trunk.
7. Configure STP and test loop-protection behavior safely.
8. Configure PoE on supported hardware.
9. Configure an SVI and static route.
10. Inspect MAC tables, port statistics, logs, and packet captures.
11. Test DHCP-security features in an isolated lab.
12. Troubleshoot a deliberately misconfigured VLAN or FortiLink connection.

## Study Strategy

Start with Fortinet's FortiSwitch 7.2 Administration Guide. Build each configuration in a lab instead of memorizing GUI locations. For every feature, understand its purpose, prerequisites, expected behavior, and troubleshooting method.

Review official training material and legitimate practice questions after completing the technical study. Focus on configuration reasoning rather than memorization.

## 30-Day Study Plan

**Days 1–4:** Ethernet, VLANs, switching, MAC learning, and basic FortiSwitch administration.

**Days 5–8:** Ports, trunks, LACP, STP, loop protection, and PoE.

**Days 9–12:** FortiLink architecture, FortiGate-managed switches, discovery, and authorization.

**Days 13–16:** FortiSwitch Manager and centralized administration.

**Days 17–20:** Layer-3 interfaces, static routing, OSPF, BGP, VRRP, and ECMP.

**Days 21–23:** DHCP security, DAI, source guard, port security, and related controls.

**Days 24–26:** SNMP, sFlow, logging, monitoring, diagnostics, and packet capture.

**Days 27–28:** Complete hands-on troubleshooting labs.

**Day 29:** Review official objectives and weak areas.

**Day 30:** Final revision and exam preparation.

## Common Mistakes

- Confusing access and trunk ports.
- Treating FortiLink as ordinary unmanaged switching.
- Ignoring STP when troubleshooting loops.
- Forgetting VLAN and routing dependencies.
- Memorizing commands without understanding their effect.
- Ignoring port statistics and diagnostic information.
- Skipping hands-on practice.
- Using exam dumps or leaked questions.

## Exam-Day Tips

Read each scenario carefully and identify the network requirement first. Eliminate answers that conflict with the topology or configuration described. Keep track of time and avoid spending too long on one question.

## Final Checklist

- [ ] Understand FortiSwitchOS 7.2 administration.
- [ ] Configure VLANs and ports.
- [ ] Understand FortiLink.
- [ ] Configure and troubleshoot LACP.
- [ ] Understand STP and loop protection.
- [ ] Understand PoE.
- [ ] Understand Layer-3 routing.
- [ ] Review switching-security features.
- [ ] Practice monitoring and diagnostics.
- [ ] Verify current Fortinet exam information.

## Official Resources

- Fortinet Training Institute: https://training.fortinet.com/
- FortiSwitch 7.2 Administration Guide: https://docs.fortinet.com/document/fortiswitch/7.2.0/administration-guide
- FortiSwitch 7.2 documentation: https://docs.fortinet.com/product/fortiswitch/7.2
- FortiSwitch Manager 7.2 Administration Guide: https://docs.fortinet.com/document/fortiswitch-manager/7.2.0/administration-guide

Fortinet's documentation provides current technical references for standalone FortiSwitch administration, FortiLink-managed deployments, and FortiSwitch Manager. :contentReference[oaicite:5]{index=5}

## Voucher / Discount

Learn SecByte provides certification voucher options and discounts where available.

Voucher: https://learn.secbyte.org/vouchers/fortinet-nse5-fsw-7-2

Check the current offer, pricing, eligibility, and availability before purchasing.

## Disclaimer

This is an independent/community study guide and is not an official Fortinet publication. Fortinet, FortiSwitch, FortiLink, and related names are trademarks of their respective owners. Verify current exam information, objectives, availability, and certification requirements with Fortinet before booking. Voucher pricing and availability may change. This repository does not contain exam dumps, leaked questions, or recalled exam questions.
