---
layout: default
title: BaaT
nav_order: 2
has_children: true
permalink: docs/BaaT
---
# Blockchain as a Transport

Blockchain as a Transport is based on the well-known Software-Defined WAN (SD-WAN) architecture butwith lots of fine tuning and blockchain engagement as will be detailed. BaaT is an advanced network automation solution for both enterprises and telco/service providers, with which the organization can leverage the public Internet or any type of networks (MPLS, 5G, 4G, Satellite, PVC and etc.) for their WAN traffic so that they don’t need to share traffic with their upstream providers as in the case of MPLS VPN service or even modern SD-WAN.
{: .mt-6 .fs-5 .fw-300} 
Unlike  other  circuit  techniques,  BaaT  is  built  to  operate  in  a  multipoint  fashion.Its signaling and control plane data sharing is done separately via theblockchain and it has no scalability issues.
{: .mt-2 .fs-5 .fw-300} 
BaaT is a flexible Overlay solution. We are using **VXLAN** protocol to establish tunnels between BaaT Edge devices. But we also can use:
- GRE 
- GENEVE
- STT
- LISP
{: .mt-2 .fs-5 .fw-300} 
BaaT is a very secured solution. It is protected by Quantum Resistant [encryption](https://bd-wan.github.io//docs/BaaT/Encryption/) + **AES256** + **SHA256** algorythms. Which makes our solution *Military Grade*.
{: .mt-6 .fs-5 .fw-300} 

Now we can switch to the next topic - [Encryption](https://bd-wan.github.io//docs/BaaT/Encryption/).