# Networking Fundamentals
---

## Rooms completed on TryHackMe
- Introductory Networking
- What is networking
- DNS in detail
- HTTP in detail

## Objective
The purpose of this room was to build a foundational understanding of networking concepts and how systems communicate. This knowledge is essential in ethical hacking, as most attacks and defenses occur over networks.

---

## Networking Basics
Networking refers to the connection of devices that allows them to communicate and share data.
From an ethical hacking perspective, understanding how devices communicate is critical. Attackers rely on network communication to identify targets, map systems, and exploit vulnerabilities. Without a solid understanding of networking, it is difficult to perform effective reconnaissance or analyze network traffic.

---

## IP Addressing
IP addresses are unique identifiers assigned to devices on a network. They allow systems to locate and communicate with each other.
In ethical hacking, IP addresses are fundamental during reconnaissance. Attackers use IP ranges to scan for active hosts, identify targets, and map network structures. Understanding the difference between public and private IP addresses also helps in identifying externally exposed systems versus internal network assets.

---

## DNS 
DNS is responsible for translating domain names into IP addresses so that users can access websites using human-readable names.
In ethical hacking, DNS plays an important role during information gathering. Attackers often use DNS queries to discover subdomains, identify infrastructure, and uncover potential entry points. Misconfigured DNS can also be exploited through techniques such as DNS spoofing or cache poisoning.

---

## HTTP and HTTPS
HTTP and HTTPS are protocols used for transferring data over the web. HTTPS provides encryption, while HTTP does not.
From an ethical hacking standpoint, understanding these protocols is essential when analyzing web traffic. Unencrypted HTTP traffic can be intercepted and manipulated, making it vulnerable to attacks such as man-in-the-middle attacks. HTTPS helps mitigate these risks, but attackers may still attempt to exploit misconfigurations or weak implementations.

---

## Ports and Protocols
Ports are used to identify specific services running on a system, while protocols define how data is transmitted.
In ethical hacking, identifying open ports is a key part of enumeration. Open ports indicate running services, which may contain vulnerabilities. Tools like port scanners are used to discover these services and determine potential attack vectors.

---

## Practical Relevance to Ethical Hacking
The concepts I covered in this room form the foundation for more advanced techniques such as network scanning, enumeration, and exploitation.

## What i have learnt in these rooms
Understanding networking allows an ethical hacker to:
- Identify active systems on a network
- Analyze traffic for vulnerabilities
- Discover exposed services
- Understand how attacks are carried out over networks

---

## Conclusion
This room provided a strong introduction to networking concepts and their importance in cybersecurity. The knowledge gained is directly applicable to ethical hacking, particularly in the early stages of reconnaissance and enumeration.
