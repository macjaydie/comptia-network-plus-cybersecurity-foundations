# TCP/IP Model



## Introduction



While the OSI model is a conceptual framework, the TCP/IP model is the practical networking model used in real-world environments. It forms the foundation of the modern internet.



The TCP/IP model consists of four layers:



1. Application

2. Transport

3. Internet

4. Network Access



---



## 1. Application Layer



This layer combines the OSI Application, Presentation, and Session layers.



It handles:

- HTTP / HTTPS

- FTP

- SMTP

- DNS

- SSH



This layer allows applications to communicate over the network.



Security relevance:

Most attacks target this layer (e.g., web exploits, phishing, DNS attacks).



---



## 2. Transport Layer



Responsible for end-to-end communication.



Protocols:

- TCP (reliable, connection-oriented)

- UDP (faster, connectionless)



TCP Features:

- Three-way handshake

- Sequence numbers

- Error checking

- Flow control



UDP Features:

- No handshake

- Faster

- Used for streaming, VoIP, DNS queries



Security relevance:

- Port scanning targets this layer

- SYN floods exploit TCP handshake



---



## 3. Internet Layer



Responsible for logical addressing and routing.



Protocols:

- IP (IPv4 / IPv6)

- ICMP

- ARP



Functions:

- Packet routing

- Addressing

- Path determination



Security relevance:

- ICMP abuse

- IP spoofing

- Routing attacks



---



## 4. Network Access Layer



Equivalent to OSI Data Link + Physical layers.



Handles:

- MAC addressing

- Framing

- Ethernet

- Physical transmission



Security relevance:

- MAC flooding

- ARP spoofing



---



## OSI vs TCP/IP Comparison



OSI has 7 layers (conceptual model).  

TCP/IP has 4 layers (practical implementation).



OSI is used for understanding and troubleshooting.  

TCP/IP is used in real-world network communication.



---



## Why This Matters for Cybersecurity



Understanding TCP/IP is essential for:



- Packet analysis

- Network monitoring

- IDS/IPS configuration

- Firewall rules

- SOC investigations
