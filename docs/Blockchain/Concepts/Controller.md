---
layout: default
title: Controller
parent: Concepts
grand_parent: BD-WAN
nav_order: 2
---

# BD-WAN Controlerless approach

{: .mt-6 .fs-5 .fw-300}


In fact, **BD-WAN** is the first world serverless **SD-WAN** concept. We do our topology flat and simple. We don't have a Controller, but you can assume that every **BD-WAN** node has Controller attributes. You can manage your **Blockchain** domain from any **BD-WAN** node you are able to interact with, but you have to have some credentials for that. As you can see, you don't have any single point of control anymore. You can controll your network directly from any place you assume allowed, especially if you are using **BaaT** encrypted channels. Which makes your traffic *invisible* in the Internet. But we will get more familiar with **BaaT** [here](https://**BD-WAN**.github.io//docs/BaaT).
{: .mt-6 .fs-5 .fw-300}
![BD-WAN CONTRORELLES Diagram](https://user-images.githubusercontent.com/107935539/178145474-1c055140-ea45-4a0e-8794-a1603a240ef4.png)

Here you can see simplified dataflow. It shows what happens when you implement new command in GUI, if the command is related globally.
{: .mt-6 .fs-5 .fw-300}
![**BD-WAN** RPC FLOW (1)](https://user-images.githubusercontent.com/107935539/177583340-34f067be-ba92-42b9-9fd1-bc8f44118f0a.png)

**Blockchain** RPC requested by user can be shared with every node in the Blockchain, if it's needed. You can specify as much nodes as it's needed to realise the task. But before you insert the **RPC** data within **Block** you have to **validate** your rights.
{: .mt-6 .fs-5 .fw-300}