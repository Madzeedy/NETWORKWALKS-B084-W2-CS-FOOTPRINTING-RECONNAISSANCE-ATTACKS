# NETWORKWALKS-B084-W2-CS-FOOTPRINTING-RECONNAISSANCE-ATTACKS
FOOTPRINTING &amp; RECONNAISSANCE ATTACKS WITH MULTIPLE KALI TOOLS


📌 About This Project

This repository contains my Week 2 cybersecurity internship work at Networkwalks (Batch B082).

The practical work covered two areas: Footprinting and Network Scanning. I used Kali Linux tools to gather information about networkwalks.com and Zenmap to explore devices and services on my local lab network.

It also includes the main findings, screenshots, and final report.

🎯 What I Set Out to Do

Practise gathering information about a target domain.

Explore DNS records and website technologies.

Check HTTP headers and WAF protection.

Discover active devices on a local network.

Identify open ports and running services.

Understand and document scan results.

📚 Completed Activities

Modules	Status
W2-PM1	✅ Completed
W2-PM5	✅ Completed
W2-PM-FINAL	✅ Completed

🔎 Phase 1 – Domain Reconnaissance (W2-PM1)

Objective: Explore the public information available about networkwalks.com.

Steps I Followed

WHOIS: Checked domain registration details.
<img width="1206" height="667" alt="1" src="https://github.com/user-attachments/assets/50b0dde3-27f3-4d49-a22e-9bce6eadcbec" />


WhatWeb: Looked at the website's technologies and CMS.
<img width="1360" height="797" alt="2" src="https://github.com/user-attachments/assets/4adc4c21-02d6-42df-aaa1-995067752e1c" />


NSLookup: Checked DNS records and IP resolution.
<img width="1355" height="748" alt="3" src="https://github.com/user-attachments/assets/3b194e19-24c1-44ba-b352-27c536b8ceab" />


cURL: Examined HTTP responses and headers.
<img width="1392" height="811" alt="4" src="https://github.com/user-attachments/assets/5d7dbfdb-0243-47e5-9fb8-55a6b11bfb6f" />


Wafw00f: Checked for WAF protection.
<img width="1422" height="777" alt="5" src="https://github.com/user-attachments/assets/c195a8b3-c5ad-46b8-ac9d-ede45f57ff3b" />


DNSRecon: Gathered additional DNS information.
<img width="1452" height="930" alt="6" src="https://github.com/user-attachments/assets/c0a6f1c7-1953-43e6-b7be-3c6e3526b010" />

🌐 Phase 2 – Exploring the Local Network (W2-PM5)

Objective: Explore my local lab network and identify active hosts, open ports, and available services using Zenmap.

Types of Scans Performed

Ping Scan:  Find active hosts

4 hosts were live (including my PC), though it kept changing to 3 or 2; you will notice that in my screenshots because other devices kept connecting and disconnecting.

The IPs:
192.168.1.254
192.168.1.66

<img width="873" height="645" alt="7" src="https://github.com/user-attachments/assets/e31cac7b-2a48-4752-9a3c-7ffbe7fbd8c5" />



Quick Scan:   Check commonly used ports
<img width="1917" height="908" alt="8" src="https://github.com/user-attachments/assets/23223397-2803-4ba8-ac41-90399ddc337c" />


Regular Scan:  Standard port scan
<img width="1918" height="1017" alt="9" src="https://github.com/user-attachments/assets/4f64d47f-8c75-4b9d-971b-4e11a6c46cfa" />


Intense Scan:  Details about ports, services, and OS information
<img width="1918" height="1016" alt="10" src="https://github.com/user-attachments/assets/1998da68-3c9a-44cb-87cf-85be1da0c8b4" />

Topology View:  View discovered hosts and their network connections
<img width="952" height="496" alt="W2-PM1-FP" src="https://github.com/user-attachments/assets/c3ef1a57-3dfb-454c-b9eb-5ce9581466a7" />

Below, you can find my final report

[Final report_W2.pdf](https://github.com/user-attachments/files/34880760/Final.report_W2.pdf)


