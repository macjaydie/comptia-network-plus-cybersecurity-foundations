# Public vs Private IP Addresses

## Public IP Addresses

Public IP addresses are globally routable and assigned by ISPs.

They are visible on the internet.

Example:
8.8.8.8

Security implications:
- Public exposure increases attack surface
- Services exposed publicly must be hardened

---

## Private IP Address Ranges

Defined by RFC 1918:

10.0.0.0 – 10.255.255.255  
172.16.0.0 – 172.31.255.255  
192.168.0.0 – 192.168.255.255  

Private IPs are not routable on the public internet.

---

## NAT (Network Address Translation)

Routers translate private IP addresses into a public IP.

Purpose:
- Conserve IPv4 addresses
- Hide internal network structure

---

## Security Importance

- SOC analysts identify internal vs external IPs
- Private IPs indicate internal network activity
- Public IPs may indicate external attackers
- NAT logs are important in investigations
