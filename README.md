# Wireshark Packet Capture and Protocol Analysis

## Objective
To capture live network traffic using Wireshark, analyze packets, identify multiple network protocols, and summarize findings.

---

## Steps Performed
1. Installed Wireshark on Kali Linux.
2. Started packet capture on the active network interface (eth0 / Wi-Fi).
3. Generated network traffic by browsing websites and using the ping command.
4. Stopped the capture after approximately one minute.
5. Applied protocol filters such as `tcp`, `udp`, `dns`, `tls`, and `http`.
6. Identified at least three different protocols from the captured traffic.
7. Exported the capture as a `.pcap` file.
8. Summarized findings and packet details based on the captured packets.

---

## Protocols Observed (Examples)
| Protocol | Purpose |
|---------|----------|
| TCP | Reliable connection-oriented protocol used for communication across the web. |
| UDP | Fast connectionless protocol commonly used for streaming and gaming. |
| TLS | Encryption layer that protects HTTPS communication. |
| DNS | Resolves domain names to IP addresses. |
| HTTP/HTTPS | Web browsing traffic sent using TCP / TLS. |

---

## Summary of Findings
The live packet capture showed the presence of multiple protocols operating simultaneously.  
TCP packets displayed the three-way handshake sequence (SYN → SYN/ACK → ACK), confirming reliable session establishment.  
UDP packets were observed during video or media Web requests, indicating low-latency communication.  
TLS packets were captured during HTTPS browsing, showing encrypted communication between the client and server.  

Overall, the experiment demonstrates how different protocols cooperate to ensure secure, fast, and reliable network communication.

---

## Tools Used
- Wireshark
- Kali Linux
- Web browser  (Firefox)
- Terminal (ping utility) for generating ICMP/DNS requests

---

## Conclusion
This activity successfully demonstrates:
- Ability to capture and analyze live network packets
- Understanding of various protocol functions
- Recognition of encrypted and non-encrypted network traffic patterns

---


