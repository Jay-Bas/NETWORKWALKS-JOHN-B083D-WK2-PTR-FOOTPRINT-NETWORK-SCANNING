## Project Overview

This repository contains the final deliverable for **Week 2** of the Networkwalks Cybersecurity Internship.

The report covers two practical modules:

| Module | Title | Phase |
|--------|-------|-------|
| **W2-PM1** | Footprinting & Reconnaissance with Multiple Kali Tools | Phase 1 – Reconnaissance |
| **W2-PM5** | Network Scanning with Zenmap | Phase 2 – Scanning & Discovery |

All activities were performed **only** against authorized targets:
- `networkwalks.com` (written permission obtained)
- My own local Wi-Fi network (`172.20.10.0/28`)

---

## Repository Structure

```
├── README.md
├── W2-PM-FINAL_John_Segun_A_B083D.pdf   ← Full professional report
├── evidences/
│   ├── 1_whois.jpg
│   ├── 2_whatweb.jpg
│   ├── 3_nslookup.jpg
│   ├── 4_curl.jpg
│   ├── 5_wafw00f.jpg
│   ├── 6_dnsrecon.jpg
│   ├── 7_ipconfig.jpg
│   ├── 8_zenmap_scan.jpg
│   └── 9_topology.jpg
└── docs/                                ← Additional notes (optional)
```

---

## Tools Used

**Footprinting (Kali Linux)**
- `whois`
- `whatweb`
- `nslookup`
- `curl -I`
- `wafw00f`
- `dnsrecon`

**Network Scanning (Windows)**
- Zenmap (Nmap GUI)
- Windows Command Prompt (`ipconfig`)

---

## Key Findings Summary

### Footprinting (networkwalks.com)
- Registrar: GoDaddy.com, LLC
- Name Servers: HostGator (NS6135 / NS6136)
- Real IP: **192.232.216.135**
- CMS: **WordPress 7.1** + WP Download Manager 3.3.58
- WAF: **ModSecurity (SpiderLabs)**
- DNS: Bind 9.16.23-RH, SPF record, cPanel autodiscover SRV records

### Local Network Scan (172.20.10.0/28)
- Live hosts: **2**
  - `172.20.10.1` – Gateway (phone hotspot)
  - `172.20.10.3` – My Windows PC
- Topology PDF generated and included in the report

---

## How to Use This Repository

1. Download or clone the repository.
2. Open `W2-PM-FINAL_John_Segun_A_B083D.pdf` for the complete professional report.
3. All original screenshots used as evidence are available in the `evidences/` folder.

---

## Disclaimer

All activities documented in this report were performed strictly within the authorized scope of the Networkwalks Cybersecurity Internship (Batch B083D).  

These materials are for **educational and research purposes only**.  
Unauthorized use of any techniques described here against systems you do not own or have explicit written permission to test is illegal.

---

**Author:** John Segun A  
**Batch:** B083D  
**Institution:** Networkwalks  
**Week:** 02
