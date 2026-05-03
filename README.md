# Nmap Network Recon Lab

## Objective
Perform network discovery and identify active hosts, open ports, and services.

## Tools Used
- Kali Linux
- Nmap

## Network Range
10.0.2.0/24

## Target Analyzed
10.0.2.2

## Commands Used

### Host Discovery


### Service Scan


## Findings

### Open Ports:
- 135/tcp → MSRPC (Windows Remote Procedure Call)
- 445/tcp → SMB (File Sharing)
- 5357/tcp → Microsoft HTTPAPI (SSDP/UPnP)

## Analysis
The scan identified a Windows-based host with multiple open ports. SMB (port 445) is commonly targeted in attacks and should be secured properly.

## Risk Assessment
Medium

## Recommendations
- Restrict SMB access (port 445)
- Use firewall rules to limit exposure
- Monitor for unauthorized access attempts
- Keep system updated with security patches
