---
toc: true
comments: true
layout: post
title: Computers and Networks (Unit 4)
description: Add Definitions from Unit 4 Computer Systems and Networks
image: /images/apcsp.png
categories: []
type: ap
week: 29
---

## Requirements
> Work through College Board Unit 4... blog, add definitions, and pictures.  Be creative, for instance make a story of Computing and Networks that is related to your PBL experiences this year.


### How a Computer Works
> As we have learned, a computer needs aa program to do something smart.  The sequence of a program initiates a series of actions with the computers Central Processing Unit (CPU). This component is essentially a binary machine focussing on program instructions provided.  The CPU retrieives and stores the data it acts upon in Random Access Memory (RAM). Between the CPU, RAM, and Storage Devices a computer can work with many programs and large amounts of data.



List specification of your Computer, or Computers if working as Pair/Trio
- Processor GHz: 2.20
- Memory in GB: 4GB
- Storage in GB: 237 GB
- OS: Microsoft Windows 11 

Define or describe usage of Computer using Computer Programs. Pictures are preferred over a lot of text.  Use your experience.

- Input devices
- Output devices
- Program File
- Program Code
- Processes
- Ports
- Data File
- Inspect Running Code
- Inspect Variables


![image](https://user-images.githubusercontent.com/111611921/235412829-8794437e-3395-458b-881d-42f464f27dda.png)

![Computer Hardware]({{site.baseurl}}/images/cpu.jpeg)


### The Internet
> Watch/review College Board Daily Video for 4.1.1

- Essential Knowledge
    - A computing device is a physical artifact that can run a program. Some examples include computers, tablets, servers, routers, and smart sensors.
    - A computing system is a group of computing devices and programs working together for a common purpose.
    - A computer network is a group of interconnected computing devices capable of sending or receiving data.
    - A computer network is a type of computing system. 
    - A path between two computing devices on a computer network (a sender and a receiver) is a sequence of directly connected computing devices that begins at the sender and ends at the receiver.
    - Routing is the process of finding a path from sender to receiver.
    - The bandwidth of a computer network is the maximum amount of data that can be sent in a fixed amount of time.
    - Bandwidth is usually measured in bits per second

- Complete Vocabulary Matching Activity.  Incorporate this into your learnings from year.  To analyze measure path and latency use `traceroute` and `ping` commands from Linux Terminal.  
    - Path 
    - Route
    - Computer System
    - Computer Device
    - Bandwidth
    - Computer Network

> Watch/review College Board Daily Video 4.1.2

- Complete True of False Questions
0. T: Open standards and protocols enable diff3erent manufacturers and developers to build hardware and software that can communicate with hardware/software on the rest of the internet
1. F: IETF is a task force used to enforce laws to keep manufacturers out of the internet
2. F: routes are determined in advance and are not flexible
3. T: Protocol is agreed upon set of rules that specify behavior of a system
4. F: UDP guarentees transfers and is faster
5. F: WWW is the internet
T. T: HTTP is a protocol used by WWW

- Essential Knowledge
    - The internet is a computer network consisting of interconnected networks that use standardized, open (nonproprierary) communication protocols.
    - Access to the internet depends on the ability to connect a computing device to an internet connected device.
    - A protocol is an agreed-upon set of rules that specify the behavior of a system.
    - The protocols used in the internet are open, which allows users to easily connect additional computing devices to the internet.
    - Routing on the internet is usually dynamic; it is not specified in advance
    - The scalability of a system is the capacity for the system to change in size and scale to meet new demands.
    - The internet was designed to be scalable
    - Information is passed through the internet as a data stream. Data streams contain chunks of data, which are encapsulated in packets. 
    - Packets contain a chunk of data and metadata used for routing the packet between the origin and the destination on the internet, as well as for data reassembly.
    - Packets may arrive at the destination in order, out of order, or not at all
    - IP, TCP and UDP are common protocols used on the internet.
    - The world wide web is a system of linked pages, programs, and files.
    - HTTP is a protocol used by the world wide web
    - The world wide web uses the internet

- Go over AP videos, vocabulary, and essential knowledge.  Draw a diagram showing the internet and its many levels. A preferred diagram would using your knowledge of frontend, backend, deployment, etc.  Picture would highligh vocabulary by illustration. The below illustration have some ideas

![image](https://user-images.githubusercontent.com/111611921/235413363-021e4c37-e3b7-4cb0-bd15-f30351aaf7e9.png)

- Often we draw pictures of machines communicating over the Internet with arrows.  However, the real communication goes through protocol layers and the machine and then is trasported of the network.   For College Board and future Computer Knowledge you should become familiar with the following ...

```
     User Machine  <---> Frontend Server <---> Backend Server
    +-----------+         +-----------+         +-----------+
    |  Browser  |         |  GH Page  |         |   Flask   |
    +-----------+    ^    +-----------+    ^    +-----------+
    |    HTTP   |    |    |    HTTP   |    |    |    HTTP   |
    +-----------+    |    +-----------+    |    +-----------+
    |    TCP    |    |    |    TCP    |    |    |    TCP    |   
    +-----------+    |    +-----------+    |    +-----------+
    |     IP    |    V    |     IP    |    V    |     IP    |
    +-----------+         +-----------+         +-----------+
    |  Network  |  <--->  |  Network  |  <--->  |  Network  |
    +-----------+         +-----------+         +-----------+
```

The "http" layer is an application layer protocol in the TCP/IP stack, used for ***communication between web browsers and web servers***. It is the protocol used for transmitting data over the World Wide Web.

The "transport" layer (TCP) is responsible for providing reliable data transfer between applications running on different hosts.  The TCP protocol segments the data into smaller ***chunks called "segments"***. Each segment contains a sequence number that identifies its position in the original stream of data, as well as other control information such as source and destination port numbers, and checksums for error detection.

The "ip" layer is responsible for packetizing data received from the TCP layer of the protocol stack, and then ***encapsulating the data into IP packets***. The IP packets are then sent to the lower layers of the protocol stack for transmission over the network.

The "network" layer is responsible for ***routing data packets between networks*** using the Internet Protocol (IP). This layer handles tasks such as packet addressing and routing, fragmentation and reassembly, and ***network congestion*** control.


### Fault Tolerance
> Watch both Daily videos for 4.2

- Complete the network activity, summarize your understanding of fault tolerance.
Fault tolerance is a system's ability to function even there are multiple errors or fault. SImply put, it is the system tolerating possible faults. When one component or path fails, another one can take over in it's place and have the exact same function. 

### Parallel and Distributed Computing
> Review previous lecture on Parallel Computing and watch Daily vidoe 4.3.  Think of ways to make something in you team project to utilize Cores more effectively.  Here are some thoughts to add to your story of Computers and Networks...

- What is naturally Distributed in Frontend/Backend archeticture? 
Frontend is distributed among users as it runs on their devices. The frontend interacts with the backend thorugh API. Backend handles data processing and storage and is distributes across servers. 

- Analyze this command in Docker: ```ENV GUNICORN_CMD_ARGS="--workers=1 --bind=0.0.0.0:8086"```.   Determine if there is options are options in this command for parallel computing within the server that runs python/gunicorn.  Here is an [article](https://medium.com/building-the-system/gunicorn-3-means-of-concurrency-efbb547674b7)
ENV GUNICORN_CMD_ARGS="--workers=1 --bind=0.0.0.0:8086 sets environment variable GUNICORN_CMD_ARGS with two specifications, ="--workers=1 specifies that one worker process should be used (no parallel), and --bind=0.0.0.0:8086 tells the port. 

## My Notes
# 4.1 Video 1
- As time evolved, computers became smaller
- computers are capable of sending and recieving data
- A computer system is a group of computing devices and programs working together for a joint purpose
- A computer network is a group of interconnected computing devices capable of sending or recieving data, type of computing system
- Packet switching: message is broken up into files and sent in any order. the packets are reassembled by reciever's device
- Routing is the process of finding a path from sender to reciever
- A path between two computing devices on a computer netqork (a sender and a reciever) is a sequence of directly connected computing devices that begins at the sender and ends at the reciever
- Bandwith: maximum amount of data that can be snet in a fixed amount of time on a computer network (bits/second)

# 4.1 Video 2
- Packet: small amount of data sent over a netqork. Each packet also includes the source and destination of the Data. 
- protocol: agreed upon set of rules that specify the behavior of a system
## Computer Protocol Methods:
- OSI: open systems interconnect: layers you have to go through to communicate (7 groups of protocols)
- TCP: establishes common standard for how to send messages
- Network Access Layer: Setting things up in the hardware, NIC card or wire. MAC address is unique to each card. uses binary
- INternet Protocol Layer (IP): Where the packets get set up with sender ip, reciever ip, metadata(contains information used for routing information). 
- MAC address are used to transport message from sender ip to reciever ip


