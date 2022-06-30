---
layout: default
title: Architecture
parent: Blockchain
---
# Architecture

Before we start diving deep into architecture of **BD-WAN**, let's firstly take a look how actually **SD-WAN** topology looks like. Pretty simple and straightforward.
{: .mt-6 .fs-5 .fw-300}
![SD-WAN](https://user-images.githubusercontent.com/107935539/176615210-39840ed5-83db-4839-92f2-5231a69ae1dd.png)

![BD-WAN Topology](https://user-images.githubusercontent.com/107935539/175981387-8c1acce2-c17c-436c-b83e-d53d0a4251f0.png)

![Architechture_1](https://user-images.githubusercontent.com/107935539/175971451-72a5fe8f-438e-4cf5-8071-c99ce779dd50.png)

let's firstly take an example. Which is going to be a pretty simple **SD-WAN** task. To create tunnels and establish connection. Usually you would call an RPC directly in the controller and controller would send some data participants. Whereas your topology would look like this.