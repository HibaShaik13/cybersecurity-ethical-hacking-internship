# Networking & Crypto Notes

## OSI Model (7 layers)
1. Physical — cables, signals
2. Data Link — MAC addresses, switches
3. Network — IP addresses, routing
4. Transport — TCP/UDP, ports
5. Session — connection management
6. Presentation — encryption/formatting
7. Application — HTTP, DNS, actual apps

## IP Addressing & Subnetting
- A `/24` network (subnet mask `255.255.255.0`) means the first 3 octets identify the network, the last octet identifies the device.
- Example: `192.168.56.0/24`
  - Network address: `192.168.56.0` (reserved)
  - Usable range: `192.168.56.1` – `192.168.56.254`
  - Broadcast address: `192.168.56.255` (reserved)

## TCP vs UDP
- **TCP** — connection-based, reliable, uses a 3-way handshake (SYN, SYN-ACK, ACK)
- **UDP** — connectionless, faster, no delivery guarantee

## Cryptography Basics
- **Symmetric encryption** — same key encrypts and decrypts (e.g., AES)
- **Asymmetric encryption** — public/private key pair (e.g., RSA)
- **Hashing** — one-way function, used for integrity checks (MD5, SHA256)
- **SSL/TLS** — secures data in transit using certificates and asymmetric + symmetric encryption together
