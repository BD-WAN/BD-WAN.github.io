---
layout: default
title: Architecture
parent: BD-WAN
nav_order: 2
---
# Architecture

**BD-WAN** itself represents couple of **VNF**s working together:
{: .mt-6 .fs-5 .fw-300}
- **BD-WAN VNF**
- [**BaaT**](https://bd-wan.github.io//docs/BaaT) 
{: .mt-2 .fs-5 .fw-300}
**VNF**
First one provides complete BD-WAN services, but without an advanced military grade encryption and other benefits. We will keep [BaaT](https://bd-wan.github.io//docs/BaaT) topic for later.
{: .mt-2 .fs-5 .fw-300}

## BD-WAN
### Substrate
> *The Blockchain Framework for a Multichain Future*
{: .mt-6 .fs-5 .fw-300}
We are using [Substrate](https://substrate.io/). Powerful, well designed, efficient and secure **Blockchain framework** that helps us to realize our ideas and develop new aproach in **Software Designed** industry.
{: .mt-6 .fs-5 .fw-300}
![Architecture BD-WAN](https://user-images.githubusercontent.com/107935539/176629484-a8e47726-711f-429f-81b6-cffabdf211bf.png)

### Substrate Details
To understand it more we are suggesting to take a look on this [documentation](https://docs.substrate.io/main-docs/fundamentals/transaction-types/).
{: .mt-6 .fs-5 .fw-300}

## BaaT
**BaaT** operation across the public Internet is appealing as a viable WAN option for many network operators such as enterprises, service proders, and teclos in front of conventional, expensive **WAN** options such as dedicated links, **MPLS**, or Virtual Private Networks(**VPNs**).
{: .mt-6 .fs-5 .fw-300}
**BaaT** acieves control  plane operation via Blockchain. In this mode, the **VXLAN** Tunnel Endpoints (**VTEPs**) are also nodes of a public or private BLockchain that can span the public Internet.
{: .mt-2 .fs-5 .fw-300}
Unlike other tunneling techniques, **BaaT** is built to operate in a multipoint fashion. Its signaling is done separately via the Blockchain and it has no scalability issues. Multicast and broadcast traffic is handled via the head-end replication on the source **VTEP** to all other known **VTEPs** in the same **VXLAN**. The list of **VTEPs** is known - and always updated - over the Blockchain.
{: .mt-2 .fs-5 .fw-300}

