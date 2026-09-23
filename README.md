<a id="readme-top"></a>
## About The Project
BoardNet is a CSE421(Computer Networks) course project for BRAC University made in Cisco Packet Tracer that links six education boards across Bangladesh into a unified network for sharing files, emails, and websites. Built with real-world networking techniques like DHCP, DNS, and RIP routing, it includes automatic backup paths to keep communication seamless even if a connection fails.
<p align="right">(<a href="#readme-top">back to top</a>)</p>

# Built With
* [![Packet Tracer](https://img.shields.io/badge/Cisco-Packet_Tracer-005073?style=for-the-badge&logo=cisco&logoColor=white)](https://www.netacad.com/courses/packet-tracer)
* [![Cisco Networking](https://img.shields.io/badge/Cisco-Networking-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white)](https://www.cisco.com/)
<p align="right">(<a href="#readme-top">back to top</a>)</p>

# Project Overview
### Key Features
- VLSM subnetting from base network `16.65.0.0/16`
- RIPv2 routing between DHK, SYL, and RAJ
- Static routing for KHU and BAR
- Backup paths (floating static routes) for KHU and BAR
- Default route on CTG (only connected to DHK)
- DHCP from DHK router for DHK, CTG, RAJ, and SYL
- Local DHCP servers for KHU and BAR
- Central DNS server in DHK
- Two websites: `www.dhk.edu.bd` and `www.ctg.edu.bd`
- Email server in every board (`mail.dhk.edu.bd`, etc.)
### Network Layout
| Board | Network        | Hosts |
|-------|----------------|-------|
| DHK   | 16.65.0.0/23   | 300   |
| CTG   | 16.65.2.0/24   | 200   |
| RAJ   | 16.65.3.0/24   | 160   |
| SYL   | 16.65.4.0/24   | 150   |
| BAR   | 16.65.5.0/25   | 120   |
| KHU   | 16.65.5.128/25 | 120   |
### Project Files
- `project.pkt`: the Packet Tracer file
- `report.pdf`: full report (VLSM tree, IP table, router configs, services)
- 
<p align="right">(<a href="#readme-top">back to top</a>)</p>

# How To Run
1. Install Cisco Packet Tracer
2. Open `project.pkt`
3. Wait a few seconds for all links to turn green
4. Test with `ping` from any PC, or open a website from a PC's web browser
<p align="right">(<a href="#readme-top">back to top</a>)</p>






