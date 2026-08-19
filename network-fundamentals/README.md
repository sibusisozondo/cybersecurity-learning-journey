# 🌐 Networking Fundamentals

## 📚 About This Project

This project documents my beginner-level study of computer networking as part of my cybersecurity learning journey.

I started with zero formal cybersecurity experience and am building my knowledge step by step.

---

## 🎯 Learning Objectives

I am learning how computers and devices communicate across networks and how networking concepts relate to cybersecurity.

---

## 🧠 Topics I Learned

### 1. IP Addresses

An IP address is a logical network address used to identify a device or network interface and help direct network traffic.

Example:

`192.168.1.20`

---

### 2. MAC Addresses

A MAC address is an identifier associated with a network interface and is used for communication on a local network.

Example:

`00:1A:2B:3C:4D:5E`

---

### 3. DNS

**DNS (Domain Name System)** translates human-readable domain names into IP addresses.

Example:

```text
google.com
     ↓
DNS
     ↓
IP address 
4.DHCP
DHCP (Dynamic Host Configuration Protocol) automatically provides devices with network configuration, including an IP address.

5. TCP/IP

TCP/IP is a suite of networking protocols that allows devices to communicate across networks.

TCP focuses on reliable and ordered delivery of data.
IP provides addressing and routing.
6. Ports

A port is a numbered communication endpoint used by network services.

Example:

192.168.1.20:443

192.168.1.20 = IP address
443 = port number

Common ports I learned:

Port	Common Service
22	SSH
53	DNS
80	HTTP
443	HTTPS
7. HTTP vs HTTPS

HTTP is used for communication between web browsers and web servers.

HTTPS provides security through TLS encryption.

I learned that HTTPS is commonly associated with port 443.

8. TCP vs UDP

TCP provides reliable and ordered communication.

UDP is generally faster and has less overhead, but does not provide TCP's reliability mechanisms.

🔎 Network Traffic Example

I learned how to break down basic network traffic:

192.168.1.20 → 8.8.8.8 → 53 → UDP
Analysis
Source IP: 192.168.1.20
Destination IP: 8.8.8.8
Port: 53
Protocol: UDP

Port 53 is commonly associated with DNS.

🛡️ Cybersecurity Relevance

Understanding networking is important in cybersecurity because security analysts need to understand normal network communication before they can identify suspicious activity.

I will continue developing these skills through practical labs and security tools.

📈 Learning Status

Beginner — Currently Learning

Next Topics
Networking deeper dive
OSI Model
Subnetting
Network security
Linux fundamentals
Wireshark
Nmap
Security monitoring
📝 Reflection

I learned that networking is one of the foundations of cybersecurity.

I can now explain the basic roles of IP addresses, MAC addresses, DNS, DHCP, TCP, UDP, ports, HTTP, and HTTPS.

This project represents my progress from having zero cybersecurity background toward developing practical cybersecurity skills
