<div align="center">

# 🌐 Computer Networking Notes

A comprehensive collection of Computer Networking concepts for CSE students.

![Status](https://img.shields.io/badge/Status-Learning-blue)
![Topics](https://img.shields.io/badge/Topics-8-green)
![Level](https://img.shields.io/badge/Level-Beginner%20to%20Intermediate-orange)

</div>

---

## 📚 Computer Networking Learning Roadmap

| No. | Subject | Topics Covered | Status |
|------|----------|----------------|---------|
| 1 | Introduction to Networks | LAN, MAN, WAN, Topologies, Internet, Intranet | ⬜ |
| 2 | OSI Reference Model | Physical, Data Link, Network, Transport, Session, Presentation, Application | ⬜ |
| 3 | TCP/IP Model | TCP/IP Layers, OSI Comparison, TCP, UDP | ⬜ |
| 4 | Data Link Layer | Framing, Error Detection, Flow Control, MAC Addressing | ⬜ |
| 5 | Network Layer | IP Addressing, IPv4, IPv6, Subnetting, Routing | ⬜ |
| 6 | Transport Layer | TCP Connection Management, UDP, Congestion Control | ⬜ |
| 7 | Application Layer | DNS, HTTP, HTTPS, FTP, SMTP, DHCP | ⬜ |
| 8 | Network Security | Firewalls, VPNs, Encryption, Network Attacks | ⬜ |

### 📈 Progress Tracker

- [ ] Introduction to Networks
- [ ] OSI Reference Model
- [ ] TCP/IP Model
- [ ] Data Link Layer
- [ ] Network Layer
- [ ] Transport Layer
- [ ] Application Layer
- [ ] Network Security

### 🎯 Completion Status

| Progress | Percentage |
|-----------|------------|
| 0 / 8 | 0% |
| 1 / 8 | 12.5% |
| 2 / 8 | 25% |
| 3 / 8 | 37.5% |
| 4 / 8 | 50% |
| 5 / 8 | 62.5% |
| 6 / 8 | 75% |
| 7 / 8 | 87.5% |
| 8 / 8 | 100% ✅ |

---

## 📖 Table of Contents

1. Introduction to Networks
2. OSI Reference Model
3. TCP/IP Model
4. Data Link Layer
5. Network Layer
6. Transport Layer
7. Application Layer
8. Network Security

---

## 1️⃣ Introduction to Networks

Computer networking is the practice of connecting computers and devices to share resources, exchange data, and communicate efficiently.

### Network Types

#### LAN (Local Area Network)
- Covers a small geographic area.
- Examples: Home, office, school network.
- High speed and low latency.

#### MAN (Metropolitan Area Network)
- Covers a city or metropolitan area.
- Connects multiple LANs.

#### WAN (Wide Area Network)
- Covers large geographical areas.
- Connects cities, countries, or continents.
- Example: The Internet.

### Network Topologies

#### Bus Topology
- All devices share a single communication line.

#### Star Topology
- All devices connect to a central switch or hub.

#### Ring Topology
- Devices form a circular communication path.

#### Mesh Topology
- Every device connects to multiple devices.

#### Tree Topology
- Hierarchical structure of connected nodes.

### Internet and Intranet

#### Internet
- A global network connecting millions of devices.

#### Intranet
- A private network accessible only within an organization.

---

## 2️⃣ OSI Reference Model

The OSI (Open Systems Interconnection) model consists of seven layers.

| Layer | Name |
|---------|---------|
| 7 | Application |
| 6 | Presentation |
| 5 | Session |
| 4 | Transport |
| 3 | Network |
| 2 | Data Link |
| 1 | Physical |

### Layer 1: Physical Layer
Responsibilities:
- Transmission of raw bits
- Cables and connectors
- Electrical signals

Examples:
- Ethernet Cables
- Fiber Optics

### Layer 2: Data Link Layer
Responsibilities:
- Framing
- Error Detection
- MAC Addressing

Protocols:
- Ethernet
- PPP

### Layer 3: Network Layer
Responsibilities:
- Routing
- Logical Addressing

Protocols:
- IP
- ICMP

Devices:
- Routers

### Layer 4: Transport Layer
Responsibilities:
- Reliable Communication
- Flow Control
- Error Recovery

Protocols:
- TCP
- UDP

### Layer 5: Session Layer
Responsibilities:
- Session Establishment
- Session Management
- Session Termination

### Layer 6: Presentation Layer
Responsibilities:
- Data Translation
- Encryption
- Compression

Formats:
- JPEG
- PNG
- ASCII
- Unicode

### Layer 7: Application Layer
Responsibilities:
- User Interaction
- Network Services

Protocols:
- HTTP
- FTP
- SMTP
- DNS

---

## 3️⃣ TCP/IP Model

The TCP/IP model is the practical networking model used on the Internet.

| TCP/IP Layer | Corresponding OSI Layer |
|-------------|--------------------------|
| Application | Application + Presentation + Session |
| Transport | Transport |
| Internet | Network |
| Network Access | Data Link + Physical |

### TCP vs UDP

| Feature | TCP | UDP |
|----------|------|------|
| Connection | Connection-Oriented | Connectionless |
| Reliability | Reliable | Unreliable |
| Speed | Slower | Faster |
| Ordering | Guaranteed | Not Guaranteed |

### Common Internet Protocols

- IP
- TCP
- UDP
- HTTP
- HTTPS
- DNS
- FTP
- SMTP
- DHCP

---

## 4️⃣ Data Link Layer

### Framing

Framing divides data into manageable units called frames.

Functions:
- Synchronization
- Addressing
- Error Detection

### Error Detection and Correction

Methods:
- Parity Check
- Checksum
- CRC (Cyclic Redundancy Check)

### Flow Control

Methods:
- Stop-and-Wait
- Sliding Window

### MAC Addressing

Example:

```text
00:1A:2B:3C:4D:5E
```

---

## 5️⃣ Network Layer

### IP Addressing

Example:

```text
192.168.1.10
```

### IPv4

- 32-bit Address
- Approximately 4.3 Billion Addresses

Example:

```text
192.168.1.1
```

### IPv6

- 128-bit Address
- Vast Address Space

Example:

```text
2001:0db8:85a3::8a2e:0370:7334
```

### Subnetting

Benefits:
- Better Performance
- Improved Security
- Efficient IP Allocation

Example:

```text
192.168.1.0/24
```

### Routing Algorithms

#### Distance Vector Routing
- Uses Hop Count
- Example: RIP

#### Link State Routing
- Uses Complete Network Topology
- Example: OSPF

---

## 6️⃣ Transport Layer

### TCP Connection Management

Three-Way Handshake:

```text
Client  ------ SYN ------> Server
Client <--- SYN-ACK ----- Server
Client ------ ACK ------> Server
```

Connection Established.

### UDP Communication

Characteristics:
- No Connection Setup
- Faster Communication
- Minimal Overhead

### Congestion Control

- Slow Start
- Congestion Avoidance
- Fast Retransmit
- Fast Recovery

---

## 7️⃣ Application Layer

### DNS (Domain Name System)

Converts domain names into IP addresses.

Example:

```text
google.com → 142.250.x.x
```

### HTTP

Default Port:

```text
80
```

### HTTPS

Default Port:

```text
443
```

Uses:
- SSL/TLS Encryption

### FTP

Default Ports:

```text
20, 21
```

### SMTP

Default Port:

```text
25
```

### DHCP

Default Ports:

```text
67, 68
```

Functions:
- Assigns IP Address
- Assigns Gateway
- Assigns DNS Server

---

## 8️⃣ Network Security

### Firewalls

Types:
- Hardware Firewall
- Software Firewall

Functions:
- Packet Filtering
- Access Control

### VPN (Virtual Private Network)

Benefits:
- Privacy
- Security
- Remote Access

### Encryption Basics

#### Symmetric Encryption
- Same Key for Encryption and Decryption

Examples:
- AES
- DES

#### Asymmetric Encryption
- Public Key
- Private Key

Examples:
- RSA
- ECC

### Common Network Attacks

#### Phishing
Fake emails or websites designed to steal sensitive information.

#### DoS (Denial of Service)
Overloads a server with excessive requests.

#### DDoS (Distributed Denial of Service)
Attack launched from multiple devices simultaneously.

#### Man-in-the-Middle (MITM)
Attacker intercepts communication between two parties.

#### Malware
- Virus
- Worm
- Trojan
- Ransomware

---

## 🏁 Conclusion

Computer Networking is the foundation of modern communication systems.

By learning:

✅ Network Fundamentals  
✅ OSI Model  
✅ TCP/IP Model  
✅ Routing & Switching  
✅ Network Protocols  
✅ Network Security  

You build a strong foundation for:

- Software Engineering
- Cybersecurity
- Cloud Computing
- DevOps
- System Administration
- Network Engineering

---

## 📚 Recommended Resources

- Cisco CCNA
- Computer Networking: A Top-Down Approach (Kurose & Ross)
- Data Communications and Networking (Forouzan)
- Wireshark
- Cisco Packet Tracer

---

<div align="center">

### ⭐ If you find these notes helpful, consider starring this repository!

Happy Learning 🚀

</div>
