# Computer Network

1. **Computer Networks and The Internet**
   1. What is the Internet?
      - The Internet is **a computer network that interconnects** hundreds of millions of com- puting **devices throughout the world**.
      - The Internet is all about connecting end systems to each other, so the ISPs that provide access to end systems must also be interconnected.
      - Laptops, smartphones, tablets, TVs, gaming consoles, Web cams, automobiles, environmental sensing devices, picture frames, and home electrical and security system are called **hosts** or **end systems**.
      - End systems are connected together by a network of **communication links** and **packet switches**
      - **There are many types of communication links**, which are made up of different types of physical media, including coaxial cable, copper wire, optical fiber, and radio spectrum. **Different links can transmit data at different rates**, with the **transmission rate** of a link measured in **bits/second**.
      - When sending data from 1 end system to the other end system:
        - Segments the data
        - Add header byte to each Segment
        - => Called **packets** in the jargon of computer networks, then sent through the network to the destination through **ROUTE** or **PATH**
      - **Packet Switch**:
        - Take a packet arriving on the 1 of the **INCOMING** **communication links** and forward to **OUTGOING communication links**
        - 2 most prominent types:
          - Routers:
            - Typically used in the network core.
          - Link-layer Switches:
            - Typically used in access networks
      - **Internet Service Providers (ISPs)**
        - End systems access the Internet through **Internet Service Providers (ISPs)**, including residential ISPs such as local cable or telephone companies; corporate ISPs; university ISPs; and ISPs that provide WiFi access in airports, hotels, coffee shops, and other public places
        - Each ISP is in itself **a network of packet switches** and **communication links**
        - ISPs also provide Internet access to content providers, connecting Web sites directly to the Internet
        - **Lower-tier ISPs** - Interconnected through national and international upper-tier ISPs such as **Level 3 Communications, AT&T, Sprint, NTT.**
        - An upper-tier ISP consists of high-speed routers interconnected with high-speed fiber-optic links.
      - **Protocols**
        - End systems, packet switches, and other pieces of the Internet run **protocols** that control the sending and receiving of information within the Internet.
        - The **Transmission Control Protocol (TCP)** and the **Internet Protocol (IP)** are two of the most important protocols in the Internet. => Known as **TCP/IP**
        - Specifies the **format of the packets**
   2. A Services Description
      1. Internet is **an infrastructure that provides services to applications**:
         - Electronic mail (email), Web surfing, Social Networks, Instant Messaging, Voice over-IP (VoIP), video streaming, distributed games, peer-to-peer file sharing, television over the Internet, remote login,...
         - Those are said to be **distributed applications**, since they involve multiple end systems that exchange data with each other.
      2. End systems attached to the Internet provide an **Application Programming Interface (API)**:
         - Specifies how a program running on **1 end system** asks the **Internet infrastructure** to **deliver data to** a specific destination on **the other end system**. 
         - A set of rules that the sending program must follow so that the Internet can deliver the data to destination program.
   3. **PROTOCOL**
      1. In human protocol, _there are specific messages we send, specific actions we take in response to the received reply messages or other events_ 
      2. *A* **protocol** *defines the format and the order of messages exchanged between two or more communicating entities, as well as the actions taken on the transmission and/or receipt of a message or other event.*
      3. **Network Protocol**
         1. All activities in the Internet that involves **two or more** communicating remote entities is governed by a protocol.
         2. **Congestion-control protocol** - Control the rate at which packets are transmitted between sender and receiver.
         3. **Protocols in routers** - Determine a packet's path from source to destination.
   4. **THE NETWORK EDGE**
      1. Computers, devices usually referred as **end systems** because they sit at the **edge of the Internet**
      2. **End systems** are also referred to as **hosts** because they host (run) application programs such as Web browser program, e-mail client program, e-mail server program. Can be divided into:
         1. Clients
         2. Servers
   5. **Access Networks**

