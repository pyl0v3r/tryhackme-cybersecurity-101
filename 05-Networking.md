🌐 Networking Fundamentals – TryHackMe Summary
This document summarizes key networking concepts and tools learned from the TryHackMe Networking module, including core protocols, secure communication standards, and practical packet analysis using Wireshark, TCPDump, and Nmap. A solid understanding of networking is critical for identifying vulnerabilities, analyzing traffic, and performing effective penetration testing or incident response.

✅ Key Learnings:
1. Networking Concepts & Essentials
Understood OSI and TCP/IP models, data encapsulation, and packet flow across layers.

Learned about IP addressing (IPv4/IPv6), subnetting, and CIDR notation for efficient network design.

Explored common network topologies, NAT, and DHCP operations.

2. Core Networking Protocols
Studied the functionality and security considerations of protocols like ARP, ICMP, DNS, HTTP, and HTTPS.

Understood how attackers exploit weaknesses in protocols (e.g., ARP spoofing, DNS poisoning).

3. Secure Networking Protocols
Learned the importance of TLS, SSH, and IPSec in protecting data in transit.

Differentiated between secure and insecure protocols (e.g., HTTPS vs. HTTP, SFTP vs. FTP).

4. Wireshark: The Basics
Captured and analyzed network traffic to identify source/destination IPs, ports, and protocols.

Learned to filter packets using display filters (ip.addr, tcp.port, http.request).

Identified suspicious traffic patterns useful in threat hunting and incident response.

5. TCPDump: The Basics
Performed live packet captures directly from the command line.

Used essential TCPDump filters (tcp, udp, port, host) to focus on specific traffic.

Understood how TCPDump complements Wireshark in CLI-based forensic investigations.

6. Nmap: The Basics
Learned active network reconnaissance techniques including host discovery, port scanning, and service enumeration.

Practiced common Nmap scans:

-sS (SYN scan) for stealth scanning

-sV (Service/Version detection)

-O (OS detection)

Understood how attackers use Nmap for footprinting and how defenders can detect such activity.

7. Security Relevance
Networking knowledge is critical for identifying vulnerabilities, spotting anomalous traffic, and conducting effective penetration testing and defensive monitoring.

Hands-on experience with Wireshark, TCPDump, and Nmap strengthened my ability to perform basic network forensics and reconnaissance.

🧠 Key Takeaways
A strong understanding of networking models, IP addressing, and protocols is vital for analyzing and securing network communications.
Familiarity with both insecure and secure protocols equips you to identify weaknesses and implement proper protections.
Hands-on practice with tools like Wireshark and TCPDump enhances skills in packet capture and traffic analysis, essential for threat detection and incident response.
Using Nmap for network reconnaissance builds critical abilities in identifying live hosts, open ports, and running services.
Overall, networking fundamentals are indispensable for penetration testing, vulnerability assessment, and effective cybersecurity defense.