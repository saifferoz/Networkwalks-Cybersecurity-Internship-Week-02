# W2-PM5 — Local Network Scanning with Zenmap

**Scope:** Author's own local network  
**Tool:** Zenmap (Nmap graphical interface)  
**Scan type:** Ping Scan

## Objective

Identify live hosts on the local network and review the scan results using Zenmap's host and topology views.

## Method

1. Used `ipconfig` on Windows to identify the local network configuration.
2. Entered the relevant local subnet in Zenmap.
3. Selected **Ping Scan**.
4. Reviewed the discovered hosts and the topology view.
5. Saved the topology output as supporting evidence.

## Result

The practical scan identified **17 live hosts** and displayed 17 MAC addresses in the scan results.

## Privacy note

Before publishing screenshots, redact local IP addresses, MAC addresses, hostnames, and any other information that could expose the local network or connected devices.

## Scope limitation

A Ping Scan is host discovery. It does not, by itself, establish that discovered hosts have exploitable vulnerabilities or open services.
