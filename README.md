# 🌐 Introduction to Computer Networks

This document covers the fundamental concepts of computer networking.
---

## 📚 Table of Contents

1. OSI Model  
2. Types of Networks  
   - LAN  
   - WAN  
   - Internet  
3. Network Addressing  
   - MAC Address  
   - IP Address  
   - Private and Public IP Address  
   - IPv4 and IPv6  
   - Localhost  
   - Subnet  
4. Network Protocols  
   - TCP  
   - UDP  
   - Ports  
5. Network Tools  
   - Ping / ICMP  
   - netstat  
6. Key Concepts Summary  

---

## 🧱 1. OSI Model

### 🔍 What is the OSI Model?
The **OSI (Open Systems Interconnection) model** is a conceptual framework that explains **how data is transmitted from one computer to another over a network**.

It helps to:
- Understand how networks work
- Standardize network communication
- Troubleshoot network issues

---

### 📐 OSI Model Layers

The OSI model is composed of **7 layers**, each with a specific role:

| Layer | Name | Description |
|-----|------|-------------|
| 7 | Application | User interaction |
| 6 | Presentation | Data format, encryption |
| 5 | Session | Session management |
| 4 | Transport | Data transport (TCP/UDP) |
| 3 | Network | Routing and IP addressing |
| 2 | Data Link | MAC addressing |
| 1 | Physical | Cables and signals |

Each layer communicates only with the layers directly above and below it.

---

## 🏠 2. LAN (Local Area Network)

### 📌 What is a LAN?
A **LAN** is a network that connects devices within a **limited geographical area**.

### 🧠 Typical Usage
- Home networks
- Offices
- Schools
- Small businesses

### 📏 Typical Geographical Size
- One building
- Campus
- Few kilometers

---

## 🌍 3. WAN (Wide Area Network)

### 📌 What is a WAN?
A **WAN** is a network that spans a **large geographical area**.

### 🧠 Typical Usage
- Corporate networks
- Connecting multiple LANs

### 📏 Typical Geographical Size
- Cities
- Countries
- Continents

➡️ **The Internet is the largest WAN in the world**

---

## 🌐 4. Internet

### 📌 What is the Internet?
The **Internet** is a global network of interconnected networks that use the **IP protocol**.

It allows billions of devices worldwide to communicate.

---

## 🆔 5. MAC Address

### 📌 What is a MAC Address?
A **MAC (Media Access Control) address** is a **unique identifier** assigned to a network interface.

- Format: `AA:BB:CC:DD:EE:FF`
- OSI Layer: **Layer 2 (Data Link)**

It identifies a device on a **local network**.

---

## 🌐 6. IP Address

### 📌 What is an IP Address?
An **IP address** is a logical identifier assigned to a device on a network using the IP protocol.

---

### 🔄 Types of IP Addresses

#### 🔐 Private IP Address
- Used inside a local network
- Not reachable from the Internet
- Common ranges:
  - `192.168.x.x`
  - `10.x.x.x`

#### 🌍 Public IP Address
- Accessible from the Internet
- Assigned by an Internet Service Provider (ISP)

---

## 🔢 7. IPv4 and IPv6

### 📘 IPv4
- Format: `192.168.1.1`
- 32-bit address
- Limited number of addresses

### 📗 IPv6
- Format: `2001:db8::1`
- 128-bit address
- Created to solve IPv4 address exhaustion
- Improved performance and security

---

## 🖥️ 8. Localhost

### 📌 What is Localhost?
**Localhost** refers to the **local machine itself**.

- IPv4: `127.0.0.1`
- IPv6: `::1`

It is commonly used for testing services locally.

---

## 🧩 9. Subnet

### 📌 What is a Subnet?
A **subnet (subnetwork)** is a logical subdivision of an IP network.

### 🎯 Purpose of Subnetting
- Efficient IP address usage
- Improved network security
- Reduced network traffic

---

## 🚚 10. TCP and UDP

### 📌 Transport Layer Protocols
**TCP and UDP** are the two main data transfer protocols at the **Transport Layer (Layer 4)** of the OSI model.

---

### 🔐 TCP (Transmission Control Protocol)
- Reliable
- Connection-oriented
- Ensures data delivery and order
- Slower than UDP

Used for:
- HTTP
- HTTPS
- SSH

---

### ⚡ UDP (User Datagram Protocol)
- Unreliable
- Connectionless
- Faster than TCP
- No delivery guarantee

Used for:
- Video streaming
- Online gaming
- VoIP

---

### 🔍 Main Difference Between TCP and UDP

| TCP | UDP |
|----|----|
| Reliable | Fast |
| Connection-based | Connectionless |
| Error checking | No guarantee |

---

## 🚪 11. Ports

### 📌 What is a Port?
A **port** identifies a specific service or application running on a device.

- Range: `0 – 65535`

### 🧠 Common Ports to Memorize

| Service | Port |
|-------|------|
| SSH | 22 |
| HTTP | 80 |
| HTTPS | 443 |

---

## 🧪 12. Ping and ICMP

### 📌 Ping
`ping` is a network utility used to **check if a device is reachable**.

### 📡 ICMP
**ICMP (Internet Control Message Protocol)** is the protocol used by `ping`.

It helps diagnose network connectivity issues.

---

## 🛠️ 13. Network Commands

### 🔍 ping
```bash
ping google.com
````

Checks network connectivity.

---

### 📊 netstat

* Displays active network connections
* Shows listening ports
* Helps analyze network activity

---

## ✅ Key Concepts Summary

* The OSI model has **7 layers**
* LAN = local network
* WAN = wide area network
* Internet = global network
* An IP address identifies a device
* Private IP ≠ Public IP
* IPv6 was created to replace IPv4
* TCP is reliable, UDP is fast
* SSH: 22, HTTP: 80, HTTPS: 443
* `ping` is commonly used to test network connectivity

---

