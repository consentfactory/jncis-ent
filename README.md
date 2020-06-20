# JNCIS-ENT (JN0-348) Study Guide

This is a studying resource for myself that I'm making public and *is a work-in-progress*. In the past, my studying for past certifications took an approach that crammed the material in a short window; for JNCIS-ENT, and others, I wanted a better framework that I felt could last longer and be more easily referenced. Also, I love typing markdown for some reason.

Thus, this project is created with the intent archiving information for myself and sharing the resources I've put together for others to use. 

**Table of Contents**
- [Exam Information](#exam-information)
  * [Exam Details](#exam-details)
  * [Exam Objectives](#exam-objectives)
    + [Layer 2 Switching or VLANs](#layer-2-switching-or-vlans)
    + [Spanning Tree](#spanning-tree)
    + [Layer 2 Security](#layer-2-security)
    + [Protocol Independent Routing](#protocol-independent-routing)
    + [OSPF](#ospf)
    + [IS-IS](#is-is)
    + [BGP](#bgp)
    + [Tunnels](#tunnels)
    + [High Availability](#high-availability)
  * [Resources](#resources)
    + [Books](#books)
    + [PDFs](#pdfs)
    + [Websites](#websites)

## Exam Information

[Exam Information Website](https://www.juniper.net/us/en/training/certification/certification-tracks/ent-routing-switching-track?tab=jncis-enterprise)

Updated as of 2020.06.14.

### Exam Details

JNCIS-ENT exam topics are based on the content of the recommended instructor-led training courses, as well as the additional resources.

* Exam code: JN0-348
* Written exam
* Administered by Pearson VUE
* Exam length: 90 minutes
* Exam type: 65 multiple-choice questions
* Pass/fail status is available immediately
* Software Release:
    * Junos 18.4
    * Junos Space Network Director 3.1

### Exam Objectives

This list provides a general view of the skill set required to successfully complete the specified certification exam. 

#### Layer 2 Switching or VLANs

* Identify the concepts, operation, or functionality of Layer 2 switching for the Junos OS
    * Bridging components
    * Frame processing
* Describe the concepts, benefits, or functionality of VLANs
    * Ports
    * Tagging
    * Native VLANs and voice VLANs
    * Inter-VLAN routing
* Demonstrate knowledge how to configure, monitor or troubleshoot Layer 2 switching or VLANs
    * Interfaces and ports
    * VLANs
    * Junos Network Director
    * Inter-VLAN Routing

#### Spanning Tree

* Describe the concepts, benefits, operation, or functionality of the Spanning Tree Protocol
    * STP and RSTP concepts
    * Port roles and states
    * BPDUs
    * Convergence and reconvergence
* Demonstrate knowledge how to configure, monitor, or troubleshoot STP and RSTP
    * STP
    * RSTP

#### Layer 2 Security

* Identify the concepts, benefits or operation of various Layer 2 protection or security features
    * BPDU, loop or root protection
    * Port security, including MAC limiting, DHCP snooping, * Dynamic ARP inspection (DAI) or IP source guard
    * MACsec
    * Storm control
* Identify the concepts, benefits or operation of Layer 2 firewall filters
    * Filter types
    * Processing order
    * Match criteria and actions
* Demonstrate knowledge how to configure, monitor, or troubleshoot Layer 2 security
    * Protection
    * Port security
    * Storm control
    * Firewall filter configuration and application

#### Protocol Independent Routing

* Identify the concepts, operation or functionality of various protocol-independent routing components
    * Static, aggregate, and generated routes
    * Martian addresses
    * Routing instances, including RIB groups
    * Load balancing
    * Filter-based forwarding
* Demonstrate knowledge how to configure, monitor, or troubleshoot various protocol-independent routing components
    * Static, aggregate, and generated routes
    * Load balancing
    * Filter-based forwarding

#### OSPF

* Describe the concepts, operation or functionality of OSPF
    * Link-state database
    * OSPF packet types
    * Router ID
    * Adjacencies and neighbors
    * Designated router (DR) and backup designated router (BDR)
    * OSPF area and router types
    * Realms
    * LSA packet types
* Demonstrate knowledge how to configure, monitor or troubleshoot OSPF
    * Areas, interfaces and neighbors
    * Additional basic options
    * Routing policy application
    * Troubleshooting tools (e.g., ping, traceroute,trace options, show commands, logging)

#### IS-IS

* Describe the concepts, operation or functionality of IS-IS
    * Link-state database
    * IS-IS PDUs
    * TLVs
    * Adjacencies and neighbors
    * Levels and areas
    * Designated intermediate system (DIS)
    * Metrics
* Demonstrate knowledge of how to configure, monitor or troubleshoot IS-IS
    * Levels, interfaces and adjacencies
    * Additional basic options
    * Routing policy application
    * Troubleshooting tools (e.g., ping, traceroute, trace options, show commands, logging)

#### BGP

* Describe the concepts, operation or functionality of BGP
    * BGP basic operation
    * BGP message types
    * Attributes
    * Route/path selection process
    * IBGP and EBGP functionality and interaction
* Demonstrate knowledge of how to configure, monitor, or troubleshoot BGP
    * Groups and peers
    * Additional basic options
    * Routing policy application
    * Troubleshooting tools (e.g., ping, traceroute,trace options, show commands, logging)

#### Tunnels

* Identify the concepts, requirements or functionality of IP tunneling
    * Tunneling applications and considerations
    * GRE/UDP
    * IP-IP
* Demonstrate knowledge of how to configure, monitor or troubleshoot IP tunnels
    * GRE/UDP
    * IP-IP
    * Troubleshooting tools (e.g., ping, traceroute, trace options, show commands, logging)

#### High Availability
* Identify the concepts, benefits, applications or requirements for high availability in a Junos OS environment
    * Link aggregation groups (LAG)
    * Redundant trunk groups (RTG)
    * Virtual Chassis
    * Graceful restart (GR)
    * Graceful Routing Engine switchover (GRES)
    * Nonstop active routing (NSR)
    * Nonstop bridging (NSB)
    * Bidirectional Forwarding Detection (BFD)
    * Virtual Router Redundancy Protocol (VRRP)
    * Unified In-Service Software Upgrade (ISSU)
* Demonstrate knowledge of how to configure, monitor, or troubleshoot high availability components
    * LAG and RTG
    * Virtual Chassis
    * GR, GRES, NSB, and NSR
    * VRRP
    * ISSU
    * Troubleshooting tools (e.g., trace options, show commands, logging)

### Resources

The following is a *general* list of resources that are used in my studying for JNCIS-ENT. More specific materials will be noted in each study section.

#### Books

* [Junos Enterprise Routing](https://www.amazon.com/Junos-Enterprise-Routing-Practical-Certification-ebook/dp/B005EI85GE)
* [Junos Enterprise Switching](https://www.amazon.com/JUNOS-Enterprise-Switching-Practical-Certification-ebook/dp/B0043D2E90/146-1054384-4832765)

#### PDFs

* [JNCIS-ENT-Routing](study_guides/JNCIS-ENT-Routing_2012-12-20_2015-05-22.pdf) - Older guide but still plenty of good material.
* [JNCIS-ENT-Switching](study_guides/JNCIS-ENT-Switching_2012-12-27_2015-01-28.pdf) - Older guide but still plenty of good material.

#### Websites

* [Juniper Genius JNCIS-ENT](https://cloud.contentraven.com/junosgenius/learningpath-detail/1630/3/1846/2) - **Free** resource, but requires registration.

#### Lab Work

* [Juniper VLabs](https://jlabs.juniper.net/vlabs/portal/index.page) - Requires registration. Free resource for trying out Juniper labs and scenarios.
* [EVE-NG](https://www.eve-ng.net/) - Home virtual environment you can create. Best approach is build it on standalone hardware, particularly if you're doing Juniper lab work due to the resource demands of the virtualized Juniper images. 