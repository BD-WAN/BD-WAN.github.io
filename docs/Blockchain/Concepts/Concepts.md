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
Before we start diving deeper into architecture of **BD-WAN**, let's firstly take a look on how actually **SD-WAN** topology looks like. Pretty simple and straightforward.
{: .mt-6 .fs-5 .fw-300}
![SD-WAN](https://user-images.githubusercontent.com/107935539/176615210-39840ed5-83db-4839-92f2-5231a69ae1dd.png)
SD-WAN controller recieves new tasks from GUI and implement them by sending some **RPC commands** to each **SD-WAN Router**.
{: .mt-6 .fs-5 .fw-300}
## BD-WAN
![BD-WAN Topology](https://user-images.githubusercontent.com/107935539/175981387-8c1acce2-c17c-436c-b83e-d53d0a4251f0.png)
BD-WAN recieves new tasks from GUI and implement them by sending some **RPC commands** to the **Blockchain** where they are being spread across all **BD-WAN Routers**.
{: .mt-6 .fs-5 .fw-300}

By having the exact approach we are leveraging:
- Reliability
- Synchronization
- Database handling
- Policies
- Recovery
- And a lot more feature on the Blockchain
{: .mt-6 .fs-5 .fw-300} 


We are not builind thousands of sockets to comunicate with each other and we do not rely on a single point of failure as a controller. No need in backing up the database and being scared of your server will get offline, shut down, be blocked or have some routing issue or whatever can happen!
{: .mt-6 .fs-5 .fw-300}

## Information spreading
Information sharing is one of the best our benefits. It is fast and cheap, simultaneously secure and smart. You will not share any unnecessary information, only valid and approved data will be forwarded and accepted. Our goal is to make everything as easy as it can bee. So, for example, if you want to share your LAN network IP address (*To build encrypted tunnels to pass data*) you can specify which nodes are allowed to recieve the data, maybe choose a node, or a group of nodes. You can even specify **Blockchain Domain**(*we will talk about **Blockchain Domains** later here.) That is not the only acknolewdgment step we have. As you can see in the diagram below, we also do **Policing** at **Receiving Block** step.
{: .mt-6 .fs-5 .fw-300}
![Architechture_1](https://user-images.githubusercontent.com/107935539/175971451-72a5fe8f-438e-4cf5-8071-c99ce779dd50.png)
Now we can jump into the next Concept we are glad to share with you. ![Transactions](https://bd-wan.github.io//docs/Blockchain/Concepts/Transactions/).
{: .mt-6 .fs-5 .fw-300}