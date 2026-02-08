# Common Network Ports and Protocols



Understanding ports and protocols is critical for both networking and cybersecurity.



---



## Well-Known Ports (0–1023)



| Protocol | Port | Purpose |

|----------|------|----------|

| HTTP | 80 | Web traffic |

| HTTPS | 443 | Secure web traffic |

| FTP | 21 | File transfer |

| SSH | 22 | Secure remote access |

| Telnet | 23 | Remote access (insecure) |

| SMTP | 25 | Email sending |

| DNS | 53 | Name resolution |

| DHCP | 67/68 | IP address assignment |



---



## Registered Ports (1024–49151)



Used by applications and services.



---



## Dynamic Ports (49152–65535)



Temporary ports used by clients.



---



## TCP vs UDP Usage



TCP:

- Reliable

- Used for HTTP, HTTPS, SSH



UDP:

- Faster

- Used for DNS queries, streaming



---



## Security Relevance



Open ports increase attack surface.



Examples:

- Port 3389 (RDP) exposed to internet → brute force risk

- Port 22 exposed → SSH attacks



Security controls:

- Firewalls

- Port filtering

- Network segmentation

- Intrusion Detection Systems
