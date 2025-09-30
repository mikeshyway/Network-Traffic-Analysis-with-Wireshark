# 🕵️‍♂️ Network Traffic Analysis with Wireshark

Welcome to the **Network Traffic Analysis with Wireshark** repository! 🎉 This project demonstrates practical **network traffic capture, protocol analysis, and troubleshooting** using Wireshark.  
It highlights our team's ability to **apply theory into practice**, investigate vulnerabilities, and present findings with evidence.  

### [🎥 Watch This Demostration Video](https://youtu.be/-zOpCeAN_Eo)
[![Watch the video](https://img.youtube.com/vi/ii6_VkVIilk/maxresdefault.jpg)](https://youtu.be/-zOpCeAN_Eo)

---

## 🎯 Objectives
- Capture and analyze **real network traffic** across multiple OSI layers.  
- Investigate **protocol behavior, anomalies, and security risks**.  
- Troubleshoot connectivity issues through **live simulations**.  
- Apply critical thinking and document findings professionally.  

---

## 🛠️ Methodology
- **Setup**: Home Wi-Fi + Virtual Machines  
- **Tools**: Wireshark, Command Prompt (ping, nslookup, FTP client)  
- **Process**:
  - 10+ minutes of real-time capture  
  - Protocol-specific filters (`http`, `dns`, `ftp`, `tcp`, `udp`, `icmp`, `arp`)  
  - Annotated screenshots for evidence  
  - Analysis cross-referenced with *Computer Networking: A Top-Down Approach*  

---

## 🔑 Key Findings

### 🌐 HTTP – Insecure Data Transmission
- Login credentials (username/password) captured in **plaintext**.  
- Demonstrates why **HTTP → HTTPS** migration is critical.  
<!-- - 📸 *Use image from* **“3.1.2 Packet Analysis & Observations” (p.7–9)** -->

---

### 📡 DNS – The Internet’s Phonebook
- Queries and responses observed in **plaintext**.  
- Vulnerable to **spoofing & eavesdropping**.  
- Recommended secure alternatives: **DNS over HTTPS (DoH)** / **DNS over TLS (DoT)**.  
<!-- - 📸 *Use image from* **“3.2.2 Packet Analysis & Observations” (p.14–18)**  -->

---

### 📂 FTP – Plaintext Credentials & Files
- Username, password, and file contents transmitted without encryption.  
- Proves the need for **SFTP/FTPS** instead of legacy FTP.  
<!-- - 📸 *Use image from* **“3.3.2 Packet Analysis & Observations” (p.21–23)**  -->

---

### 🔄 TCP vs UDP – Reliability vs Speed
- **TCP**: Reliable delivery, retransmission observed during file download.  
- **UDP**: Used in **Google Meet SRTP calls**, showed encryption + packet loss tolerance.  
- Demonstrated understanding of **DTLS handshake, SRTP encryption, STUN NAT traversal**.  
<!-- - 📸 *Use images from*  
  - **“4.1.2 Packet Analysis & Observations” (p.27–29)** – TCP 3-way handshake & retransmission  
  - **“4.2.2 Packet Analysis & Observations” (p.34–39)** – UDP SRTP packets + encrypted payload   -->

---

### 🖧 ICMP & ARP – Diagnostics & Vulnerabilities
- **ICMP**: Verified reachability (ping), traced paths (traceroute).  
- **ARP**: Resolved IP→MAC, but vulnerable to **spoofing attacks**.  
<!-- - 📸 *Use images from*  
  - **“5.1.2 Packet Analysis & Observations” (p.51–53)** – ICMP Echo/Reply & Traceroute  
  - **“5.2.2 Packet Analysis & Observations” (p.56–57)** – ARP Request/Reply   -->

---

### ❌ DNS Failure Simulation – Critical Dependency
- Misconfigured DNS → Internet access failed despite working network.  
- Showed how to **diagnose with nslookup, Wireshark, and revert to DHCP**.  
<!-- - 📸 *Use image from* **“6.1.2 Packet Analysis & Observations” (p.62–63)** -->

---

## 💡 Skills Demonstrated
- ✅ Wireshark packet capture & protocol filtering  
- ✅ Network protocol dissection & vulnerability identification  
- ✅ Troubleshooting (DNS failures, packet loss, retransmission)  
- ✅ Secure alternatives recommendation (HTTPS, SFTP, DoH/DoT)  
- ✅ Professional reporting & technical communication  

---

## 📘 Conclusion
This project proved our team's ability to **analyze protocols across all layers**, identify **security weaknesses**, and **resolve connectivity issues** with industry-standard tools.  
It strengthened both our **technical expertise** and the **ability to communicate findings effectively**.  

---

## 🏆 Special Thanks
Developed with ❤️ by:
- **Lau Jia Wei (@milkeshyway)**
- 
