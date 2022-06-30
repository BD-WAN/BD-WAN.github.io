---
layout: default
title: Concepts
parent: BD-WAN
has_children: true
permalink: docs/Blockchain/Concepts/
nav_order: 2
---
# Concepts

## SD-WAN
Before we start diving deeper into architecture of **BD-WAN**, let's firstly take a look how actually **SD-WAN** topology looks like. Pretty simple and straightforward.
{: .mt-6 .fs-5 .fw-300}
![SD-WAN](https://user-images.githubusercontent.com/107935539/176615210-39840ed5-83db-4839-92f2-5231a69ae1dd.png)
SD-WAN controller recieves new tasks from GUI and implement them by sending some **RPC commands** that are being realized by SD-WAN Routers. 
{: .mt-6 .fs-5 .fw-300}
## BD-WAN
![BD-WAN Topology](https://user-images.githubusercontent.com/107935539/175981387-8c1acce2-c17c-436c-b83e-d53d0a4251f0.png)
BD-WAN recieves new tasks from GUI and implement them by sending some **RPC commands** to the **Blockchain** that are being spread across all **Blockchain** nodes and being realized by BD-WAN Routers.
{: .mt-6 .fs-5 .fw-300}

By doing this, we are leveraging:
- Reliability
- Synchronization
- Database handling
- Policies
- Recovery
- And a lot more feature on the Blockchain
{: .mt-6 .fs-5 .fw-300} 


#We are not builind thousands of sockets to comunicate with each other, we do not rely on a single point of failure as a controller. No need in backing up the database and being scared of your server will get offline, shut down, be blocked or have some routing issue or whatever can happen!
{: .mt-6 .fs-5 .fw-300}

![Architechture_1](https://user-images.githubusercontent.com/107935539/175971451-72a5fe8f-438e-4cf5-8071-c99ce779dd50.png)
let's firstly take an example. Which is going to be a pretty simple **SD-WAN** task. To create tunnels and establish connection. Usually you would call an RPC directly in the controller and controller would send some data participants. Whereas your topology would look like this.