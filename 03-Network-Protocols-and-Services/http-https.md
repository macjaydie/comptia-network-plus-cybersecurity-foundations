# HTTP and HTTPS

## HTTP

HyperText Transfer Protocol  
Port 80  
Unencrypted

Used for:
- Web communication

Security issue:
Data transmitted in plaintext.

---

## HTTPS

HyperText Transfer Protocol Secure  
Port 443  
Encrypted using TLS

Provides:
- Confidentiality
- Integrity
- Authentication

---

## TLS Handshake Overview

1. Client hello
2. Server certificate
3. Key exchange
4. Encrypted communication begins

---

## Security Risks

- Man-in-the-Middle attacks
- Expired certificates
- Weak cipher suites

SOC analysts review web logs and TLS alerts for anomalies.
