# Networkwalks Cybersecurity Internship — Week 02

Hands-on work completed during Week 2 of the Cybersecurity & Ethical Hacking Internship at Networkwalks.

**Author:** Muhammad Saif Ur Rehman Feroz  
**Batch:** B084-Networkwalks  
**Date:** 11 November 2026

## Week 2 activities

| Task | Activity | Scope | Key outcome |
|---|---|---|---|
| W2-PM1 | Footprinting and reconnaissance | `networkwalks.com` (written permission secured) | Collected domain-registration, DNS, web-technology, HTTP-header, and WAF-identification information using six Kali Linux tools |
| W2-PM5 | Local network discovery with Zenmap | Own local network | Ping scan identified **17 live hosts** |

## Repository structure

```text
.
├── README.md
├── PM1-Footprinting-and-Reconnaissance/
│   ├── README.md
│   └── Commands/
│       ├── 01-WHOIS.txt
│       ├── 02-WhatWeb.txt
│       ├── 03-Nslookup.txt
│       ├── 04-cURL.txt
│       ├── 05-Wafw00f.txt
│       └── 06-DNSRecon.txt
├── PM5-Network-Scanning/
│   └── README.md
├── Reports/
│   └── README.md
└── .gitignore
```

## Scope and responsible-use statement

- PM1 reconnaissance was performed against `networkwalks.com` with written permission.
- PM5 host discovery was performed only on the author's own local network.
- The work documented here covers information gathering and host discovery. It does not claim exploitation, penetration, or vulnerability validation.
- Sensitive values such as session-cookie values, private contact details, and client-specific DNS verification tokens are intentionally omitted or redacted from the public command records.

## Key observations

- WhatWeb identified WordPress **7.1.4** and WordPress Download Manager **3.3.76** in the observed web response.
- Wafw00f identified ModSecurity (SpiderLabs) as the WAF associated with the HTTPS site. This records tool detection only; it is not proof of the WAF's effectiveness.
- DNSRecon returned eight DNS records during the recorded enumeration.
- Zenmap Ping Scan identified **17 live hosts** on the user's local network.

## Tools used

- Kali Linux
- WHOIS
- WhatWeb
- Nslookup
- cURL
- Wafw00f
- DNSRecon
- Zenmap / Nmap

## Evidence and report

Sanitized command records are provided in the PM1 folder. Add screenshots only after checking that they do not expose personal information, private LAN details, tokens, cookies, or other sensitive values.

The internship report can be placed in `Reports/` after reviewing it for consistency with the practical findings and removing any information that should not be public.

## Disclaimer

This repository is a learning portfolio documenting authorized cybersecurity practice. Tool output reflects observations at the time the commands were run and may change over time.
