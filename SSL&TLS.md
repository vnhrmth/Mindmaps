# SSL/TLS
## What is SSL/TLS?

- SSL (Secure Sockets Layer) and TLS (Transport Layer Security) are cryptographic protocols designed to provide secure communication over a computer network.

## What are the key components of SSL/TLS?

- Encryption
- Authentication
- Integrity
- Handshake Protocol
- Certificates

---

## What is Encryption in SSL/TLS?
- Encryption ensures that data transmitted between parties is unreadable to unauthorized entities.

  - What types of encryption are used?
    - Symmetric Encryption
      - Symmetric encryption uses the same key for both encryption and decryption.
    - Asymmetric Encryption
      - Asymmetric encryption uses a pair of keys: a public key for encryption and a private key for decryption.
---
## What is Authentication in SSL/TLS?

Authentication verifies the identity of the communicating parties.

### How is authentication achieved?

- Through digital certificates
- Using Certificate Authorities (CAs)

#### What is a Digital Certificate?

- A digital certificate is an electronic document that proves ownership of a public key.

#### What is a Certificate Authority (CA)?

- A CA is a trusted entity that issues digital certificates and verifies identities.

---

## What is Integrity in SSL/TLS?

- Integrity ensures that the data has not been altered during transmission.

  - How is integrity maintained?
    - Using Message Authentication Codes (MACs)
    - Hashing algorithms like SHA-256

---

## What is the Handshake Protocol?
- The handshake protocol establishes a secure connection between client and server.

  - What happens during the handshake?
    
    - Exchange of supported cipher suites
    - Authentication via certificates
    - Key exchange for encryption
    - Session key generation

---

## What are Certificates in SSL/TLS?

- Certificates are used to authenticate the identity of servers and clients.

  - What types of certificates exist?
    
    - Domain Validated (DV)
      - DV certificates verify domain ownership and are the most basic type.
    - Organization Validated (OV)
      - OV certificates verify both domain ownership and organization identity.
    - Extended Validation (EV)
      - EV certificates provide the highest level of trust by verifying legal and physical existence of the organization.
---

## What is the difference between SSL and TLS?

- TLS is the successor to SSL and offers improved security and performance.
  
  - What are the versions of SSL/TLS?
    
    - SSL 2.0 and 3.0 (deprecated)
    - TLS 1.0, 1.1 (deprecated)
    - TLS 1.2 (widely used)
    - TLS 1.3 (latest and most secure)

---

## What are common uses of SSL/TLS?

- Securing websites (HTTPS)
- Email encryption
- VPN connections
- Secure file transfers

