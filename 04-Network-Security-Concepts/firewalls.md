# Firewalls

## What is a Firewall?

A firewall is a security device or software that monitors and controls incoming and outgoing network traffic based on predefined rules.

Firewalls enforce security boundaries between trusted and untrusted networks.

---

## Types of Firewalls

### Packet Filtering Firewall
- Examines packets based on IP, port, and protocol
- Fast but limited inspection

### Stateful Firewall
- Tracks active connections
- More secure than packet filtering

### Next-Generation Firewall (NGFW)
- Deep packet inspection
- Application awareness
- Intrusion prevention
- SSL inspection

---

## Firewall Rules

Rules define:
- Source IP
- Destination IP
- Port
- Protocol
- Action (Allow / Deny)

Example:
Block inbound TCP port 3389 from the internet.

---

## Security Importance

Firewalls:
- Reduce attack surface
- Prevent unauthorized access
- Are critical in network perimeter defense

SOC analysts review firewall logs to identify malicious traffic and policy violations.
