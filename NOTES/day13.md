# Operation Abu Dhabi 2027
## Day 13 – Network Hardening, Intrusion Tactics & DoS/DDoS Mitigation (Course 3 - Module 3)
**Date:** August 24, 2026

## Objective
Analyze network hardening strategies, examine active network intrusion tactics (Packet Sniffing, IP Spoofing), and evaluate Denial of Service (DoS/DDoS) attack mechanisms and defense protocols.

## Core Concepts Explained
* **Network Intrusion Tactics:**
  * *Packet Sniffing:* Unlawful interception of unencrypted data packets traversing the network.
  * *IP Spoofing:* Forging source IP header details to disguise identity or bypass perimeter access controls.
* **Denial of Service (DoS / DDoS) Vectors:**
  * *ICMP Flood:* Overwhelming target resources by sending high volumes of ICMP Echo Request (ping) packets.
  * *SYN Flood:* Exploiting the TCP 3-Way Handshake by sending continuous SYN requests without sending final ACK confirmations, exhausting server connection queues.
  * *Ping of Death:* Sending malformed or oversized ICMP packets to crash vulnerable legacy systems.
* **SOC Defense & Mitigation:** Implementing Rate Limiting, SYN Cookies, Anomaly Detection Rules in SIEM, and perimeter ACLs to drop malicious traffic.

## Technical Vocabulary
* **SYN Flood** (/sin flad/): Ataque de denegación de servicio que explota la negociación TCP.
* **Packet Sniffing** (/pa-ket snif-fing/): Interceptación y análisis de paquetes de datos en red.
* **Rate Limiting** (/réit li-mi-ting/): Técnica de mitigación que limita el número de solicitudes permitidas en un período.

## Mission Status: ✅ Day 13 Completed — Course 3 Module 3 FULLY COMPLETED