# OSI Model (Open Systems Interconnection)



The OSI model is a conceptual framework that explains how data travels across a network. It breaks network communication into seven distinct layers, each with a specific responsibility.



Understanding the OSI model is essential for troubleshooting, network design, and cybersecurity analysis.



---



## Why the OSI Model Matters



The OSI model helps:



- Standardize network communication

- Simplify troubleshooting

- Identify where network failures occur

- Understand how attacks target specific layers



When diagnosing issues, IT professionals often isolate the problem to a specific OSI layer.



---



## The 7 Layers of the OSI Model



![OSI Model Diagram](../images/osi-model-diagram.png)



### Layer 7 — Application

This layer interacts directly with end-user software.



Examples:

- HTTP

- FTP

- SMTP

- DNS



This is where user-facing network services operate.



---



### Layer 6 — Presentation

Responsible for data formatting, encryption, and compression.



Examples:

- SSL/TLS encryption

- Data translation between formats



Cybersecurity relevance:

Encryption happens at this layer.



---



### Layer 5 — Session

Manages sessions between devices.



Responsibilities:

- Session establishment

- Session maintenance

- Session termination



Example:

Keeping a web session active while browsing.



---



### Layer 4 — Transport

Responsible for reliable data delivery.



Protocols:

- TCP (reliable, connection-oriented)

- UDP (fast, connectionless)



Key responsibilities:

- Port numbers

- Flow control

- Error checking



Cybersecurity relevance:

Port-based filtering and many attacks target this layer.



---



### Layer 3 — Network

Handles logical addressing and routing.



Key components:

- IP addresses

- Routers

- Packet forwarding



Cybersecurity relevance:

IP-based filtering and routing controls occur here.



---



### Layer 2 — Data Link

Responsible for physical addressing and local network communication.



Key concepts:

- MAC addresses

- Switches

- Frames



Cybersecurity relevance:

ARP spoofing occurs at this layer.



---



### Layer 1 — Physical

Transmits raw bits over physical media.



Examples:

- Ethernet cables

- Fiber optic cables

- Electrical signals



This layer deals strictly with hardware transmission.



---



## OSI Mnemonic



To remember the layers from top to bottom:



All  

People  

Seem  

To  

Need  

Data  

Processing



(Application → Physical)



---



## How the Layers Work Together



When data is sent:

1. It starts at Layer 7.

2. Each layer adds its own header (encapsulation).

3. Data travels physically across the network.

4. The receiving device removes headers layer by layer (decapsulation).



---



## OSI Model and Troubleshooting



If a website does not load:

- Check Layer 1 (cables connected?)

- Check Layer 3 (IP configuration correct?)

- Check Layer 4 (port open?)

- Check Layer 7 (is the service running?)



The OSI model provides a structured way to isolate issues.
