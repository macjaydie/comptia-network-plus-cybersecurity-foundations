# Network Types and Topologies



## Network Types



### LAN (Local Area Network)



A network within a limited geographic area such as a home, school, or office.



Characteristics:

- High speed

- Low latency

- Privately managed



Security relevance:

Internal network attacks often originate within the LAN.



---



### WAN (Wide Area Network)



A network that spans large geographic areas.



Example:

The Internet.



Security relevance:

Exposure to external threats increases significantly.



---



### MAN (Metropolitan Area Network)



Covers a city or campus-sized area.



---



### PAN (Personal Area Network)



Short-range network (Bluetooth, mobile tethering).



---



## Network Topologies



### Star Topology



All devices connect to a central switch.



Advantages:

- Easy to manage

- Fault isolation is simple



Disadvantages:

- Single point of failure (the switch)



[![simple-star-topology](simple-star-topology.drawio.png)]



---



### Bus Topology



All devices share one backbone cable.



Rare in modern networks.



---



### Ring Topology



Devices connected in circular format.



Rare today.



---



### Mesh Topology



Each device connects to multiple devices.



Used in:

- Enterprise networks

- High availability systems



---



## Modern Enterprise Design



Most enterprise networks use:



- Star topology at access layer

- Mesh connections at core layer



---



## Why This Matters for Security



Understanding topology helps with:



- Identifying single points of failure

- Planning redundancy

- Detecting lateral movement

- Network segmentation design

