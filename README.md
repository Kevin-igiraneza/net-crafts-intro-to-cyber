# net-crafts-intro-to-cyber
# Net Crafts — Intro to Cyber (XE101)

A comprehensive network mapping, external intelligence, and traffic analysis project completed for the **Intro to Cyber (XE101)** final assessment on **Cyberium Simulator**.

## Overview
Operation Net Crafts examines a network from both the inside and the outside:
- **Phase 1 — Internal Network Mapping:** Identified active devices, vendor OUIs, wired vs. wireless connections, Default Gateway, DHCP server, DNS servers, and ISP details, then modeled the full topology in `draw.io` with privacy masking applied.
- **Phase 2 — External Intelligence & Packet Analysis:** Assessed the network's external footprint using **Shodan** (open ports and service banners) and **WHOIS** (AFRINIC IP allocation and registration details), and captured live Ethernet traffic in **Wireshark** to analyze **DNS (Port 53)**, **TLS/HTTPS (Port 443)**, and **HTTP (Port 80)**.
- **Phase 3 — Automation (Creativity Addition):** Built a custom Python audit script that automates local and external network reconnaissance, counts active ARP hosts, and automatically masks sensitive IP and MAC octets for privacy-by-design reporting.

## Tools & Technologies
- **Network Diagramming:** `app.diagrams.net` (`draw.io`)
- **Reconnaissance & OSINT:** Shodan, WHOIS (`viewdns.info`), `ipinfo.io`, `ipconfig`, `arp`
- **Packet Sniffing:** Wireshark
- **Automation:** Python 3

## Project Report
- `Net Crafts.pdf` — Full sanitized project report with network topology diagram and redacted evidence screenshots.

> **Note:** Source code (`net_crafts_audit.py`) is kept private in accordance with Cyberium academic integrity guidelines and is available upon request.

---
*Final Project — Intro to Cyber (XE101) | Cyberium Simulator*
