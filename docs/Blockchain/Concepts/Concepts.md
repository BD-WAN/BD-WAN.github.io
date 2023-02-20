---
layout: default
title: Concepts
parent: BD-WAN
has_children: true
nav_order: 2
---
# Concepts

## SD-WAN
Before we start diving deeper into architecture of **BD-WAN**, let's firstly take a look on how actually **SD-WAN** topology looks like. Pretty simple and straightforward.
{: .mt-6 .fs-5 .fw-300}
![SD-WAN](https://user-images.githubusercontent.com/107935539/176615210-39840ed5-83db-4839-92f2-5231a69ae1dd.png)
SD-WAN controller recieves new tasks from GUI and implements them by sending some **RPC commands** to each **SD-WAN Router**.
{: .mt-6 .fs-5 .fw-300}
## BD-WAN
![BD-WAN CONTRORELLES Diagram](https://user-images.githubusercontent.com/107935539/178145474-1c055140-ea45-4a0e-8794-a1603a240ef4.png)
BD-WAN recieves new tasks from GUI and implements them by sending some **RPC commands** to the **Blockchain** where they are being spread across all **BD-WAN Routers**.
{: .mt-6 .fs-5 .fw-300}

Described above approach provides us:
- Reliability
- Synchronization
- Database handling
- Policies
- Recovery
- And a lot more Blockchain features
{: .mt-2 .fs-5 .fw-300} 


**Blockchain** is a way to share data. Every node is connected to the chain. So there is only one logical dataflow chanel. And a lower layer topology can be realised in any way. **We are aggregating data to one(or several) dataflow chains!**
{: .mt-6 .fs-5 .fw-300}

## Information spreading
Information sharing is our thing! It is fast and cheap, simultaneously secure and smart. You will not share any unnecessary information, only valid and approved data will be forwarded and accepted. Our goal is to make everything as easy as it can bee.
{: .mt-6 .fs-5 .fw-300} 
For example, if you want to share your LAN network IP address (*To build encrypted tunnels to pass data*) you can specify which nodes are allowed to recieve the data, you can choose a node, or a group of nodes. You can even specify **Blockchain Domain**(*we will talk about **Blockchain Domains** later [here](https://bd-wan.github.io//docs/Blockchain/Concepts/Crosschain/).) That is not the only acknolewdgment step we have. As you can see in the diagram below, we also do **Policing** at **Receiving Block** step. 
{: .mt-6 .fs-5 .fw-200}
![Architechture_1](https://user-images.githubusercontent.com/107935539/175971451-72a5fe8f-438e-4cf5-8071-c99ce779dd50.png)
Now we can jump into the next Concept we are glad to share with you. [Controller](https://bd-wan.github.io//docs/Blockchain/Concepts/Controller/).
{: .mt-6 .fs-5 .fw-300}

[Controller](https://bd-wan.github.io//docs/Blockchain/Concepts/Controller/)
{: .mt-6 .fs-6 .fw-300}