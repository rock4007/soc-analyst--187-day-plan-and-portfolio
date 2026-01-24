HEAD
# 🛡️ 187-Day SOC Analyst Transformation & Dissertation Labs

## 📊 Progress Tracker
This table tracks my daily technical growth and laboratory evidence for my university dissertation.

| Day | Date | Focus Area | Key Accomplishment | Evidence |
| :--- | :--- | :--- | :--- | :--- |
| *001* | 22 Jan 2026 | Environment Setup | Established GitHub HQ & Network Baseline | [View Lab Docs](Screenshot%202026-01-22%20160611.png) |
| **002** | 23 Jan 2026 | Networking | TCP/IP Deep Dive & Packet Analysis |[jan.pcapng](./jan.pcapng) |
| **003** | 24 Jan 2026 | Networking | Port Scanning & Firewall Logic | Pending |

---

## 🔬 Daily Activity Log

### Day 1: Thursday, 22 January 2026
**Objective:** Set up a professional evidence vault and verify core networking utilities.

#### Tasks Completed:
- [x] Initialized GitHub Repository with professional naming conventions.
- [x] Verified local network path using `tracert google.com`.
- [x] Identified local network configuration using `ipconfig`.
- [x] Established the "Day-by-Day" tracking system.

#### Technical Findings:
During the `tracert` lab, I observed the packet path taking 19 hops to reach the destination. Some hops resulted in "Request Timed Out," indicating ICMP filtering by intermediary firewalls—a common security practice.

---

## 🎓 Dissertation Research Notes
**Current Working Title:** *Evaluating Network Traffic Forensics in Modern Security Operations.*

*Focus:* Collecting raw data from these labs to support my university thesis chapters on network visibility.
=======
| Day | Date | Focus Area | Key Accomplishment | Evidence |
| :--- | :--- | :--- | :--- | :--- |
| 002 | 23 Jan 2026 | Networking | TCP/IP Analysis & Baseline | jan.pcapng |

Jan 23 Log:
 Captured and analyzed a TCP 3-way handshake baseline.
 # 🛡️ SOC Analyst Path: Day 1 - Networking & Cloud Fundamentals

## 📅 Date: January 24, 2026

## 🎯 Learning Objectives
Today's session focused on bridging the gap between basic networking protocols and how they are applied in a Cloud SOC environment.

---

## 🛠️ Technical Deep Dive

### 1. Networking Protocols & Security
* **Encrypted vs. Unencrypted:** Analyzed **Port 23 (Telnet)** vs. **Port 22 (SSH)**. Documented that Telnet is a high-risk protocol due to plain-text data transmission.
* **The TCP 3-Way Handshake:** 1. `SYN` (Synchronize)
    2. `SYN-ACK` (Acknowledge)
    3. `ACK` (Finalize)
* **Attack Recognition (SYN Flood):** Identified how attackers exploit the handshake by leaving connections "half-open" to cause a **Denial of Service (DoS)**.



### 2. The OSI Model
* **Layer 3 (Network Layer):** Confirmed that IP filtering and routing happen here.
* **Layer 4 (Transport Layer):** Identified that Port-based blocking (TCP/UDP) occurs here.
* **Stateful Inspection:** Learned that modern firewalls are "Stateful," meaning they remember the context of a conversation rather than just looking at individual packets.

[attachment_0](attachment)

### 3. Cloud Security Theory
* **Shared Responsibility Model:** * **Provider:** Responsible for security *of* the cloud (Hardware/Data Centers).
    * **Customer (Me):** Responsible for security *in* the cloud (VPC, Security Groups, Data).
* **Zero Trust & Lateral Movement:** Studied the importance of the **Principle of Least Privilege (PoLP)**. Configured logic to prevent "hopping" from a Web Server to a Database by restricting internal traffic.



---

## 🧠 Mock Interview Reflection
* **Scenario:** Massive spike in SYN packets with no ACKs.
* **Analysis:** This is a SYN Flood attack. The server’s memory/buffer is being exhausted by half-open connections, preventing legitimate traffic from connecting.
* **Outcome:** Successfully identified the attack and the relevant OSI Layer (Layer 3) for mitigation.

---

## 📈 Next Steps
* [ ] Study **ICMP** and **ARP** protocols from the PDF (Page 18).
* [ ] Explore **Packet Sniffing** basics (Wireshark).
* [ ] Document Day 2 progress.
*



 Verified SYN/SYN-ACK packet flags using tshark. 
Secured evidence in the dissertation repository via authenticated PAT push.

