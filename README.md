# Elevate-Lab-internship-task5

Network Packet Capture and Analysis – Kali Linux & Wireshark
This project demonstrates network traffic capture using Wireshark on Kali Linux, including traffic generation, protocol filtering, and multi-protocol identification. Step-by-step instructions and code snippets are provided in the documentation. Screenshots show the live capture session and filtering process.

Steps Overview
Capture Packets:
Launch Wireshark and select your active network interface (e.g., eth0). Start packet capture.

Generate Traffic:
Visit any website in your browser or use ping google.com in the terminal to generate packets.

Stop Capture:
After about a minute, stop the capture to save the recorded packets.

Filter by Protocol:
Use Wireshark’s display filter bar (e.g., tcp, tls, arp, or combinations like http or dns or tcp) to isolate specific protocols in your data.

Protocol Identification:
Confirm the presence of at least three protocols from the packet details (TCP, TLS, ARP, HTTP, SSDP, etc).

Export File:
Save the session in .pcap format for future reference and analysis.

Documentation and Code
All detailed steps and code snippets are provided in task5_documantation.docx. Screenshots showcase the actual capture and filter results.
