# W2-PM1 — Footprinting and Reconnaissance

**Target:** `networkwalks.com`  
**Authorization:** Written permission was secured for the activity.  
**Environment:** Kali Linux  
**Date:** 11 November 2026

## Objective

Practice passive and low-impact information gathering to identify publicly observable domain, DNS, web-technology, HTTP-response, and WAF-related information.

## Tools and practical findings

| Tool | Purpose | Observed result |
|---|---|---|
| WHOIS | Domain registration lookup | Registrar: GoDaddy.com, LLC.; creation: 6 November 2019; registry expiry: 6 November 2027; DNSSEC: unsigned |
| WhatWeb | Web technology fingerprinting | Apache; WordPress 7.1.4; WordPress Download Manager 3.3.76; Bootstrap; jQuery |
| Nslookup | DNS lookup | `networkwalks.com` resolved to `192.232.216.135` at the time of testing |
| cURL | HTTP response/header inspection | HTTPS response `HTTP/2 200`; Apache; WordPress REST API discovery link; Secure and HttpOnly cookie attributes observed |
| Wafw00f | WAF identification | Tool identified ModSecurity (SpiderLabs) |
| DNSRecon | DNS enumeration | Eight records found, including SOA, NS, MX, A, TXT, and SRV record information |

## Interpretation and limitations

- These results describe what the tools observed during this run; DNS records, software versions, and HTTP headers can change.
- Wafw00f's identification is not a security assessment and does not establish how effectively the WAF blocks attacks.
- Technology fingerprinting does not establish that a component is vulnerable.
- No exploitation or vulnerability validation is claimed.

## Command records

See the `Commands/` directory for sanitized command transcripts. Sensitive values have been redacted before publication.
