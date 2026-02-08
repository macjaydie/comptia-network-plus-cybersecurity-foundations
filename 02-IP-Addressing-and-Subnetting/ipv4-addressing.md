# IPv4 Addressing

## What is an IP Address?

An IP (Internet Protocol) address is a logical address assigned to a device on a network. It allows devices to identify and communicate with each other.

IPv4 addresses are 32-bit numbers written in dotted decimal format.

Example:
192.168.1.10

---

## Structure of an IPv4 Address

An IPv4 address consists of four octets.

Each octet:
- 8 bits
- Range: 0–255

Example breakdown:
192.168.1.10

Each number represents 8 bits of binary data.

---

## Binary Representation

Example:
192 = 11000000
168 = 10101000
1   = 00000001
10  = 00001010

Understanding binary is essential for subnetting.

---

## Network Portion vs Host Portion

An IP address is divided into:

- Network portion
- Host portion

This division is determined by the subnet mask.

Example:
192.168.1.10/24

/24 means:
- 24 bits for network
- 8 bits for hosts

---

## Classful Addressing (Legacy)

Class A: 1.0.0.0 – 126.255.255.255  
Class B: 128.0.0.0 – 191.255.255.255  
Class C: 192.0.0.0 – 223.255.255.255  

Modern networks use CIDR instead of strict classes.

---

## Why IPv4 Matters in Cybersecurity

- Log analysis includes IP tracking
- Firewall rules filter by IP
- Incident response requires identifying source and destination IPs
- Attack attribution depends on IP intelligence
