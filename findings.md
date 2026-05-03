# SOC Incident Report

## Incident Type
Network Reconnaissance

## Time of Activity
TOC: 15:15

## Summary
A network scan identified an active Windows host with multiple exposed services.

## Observations
- Host 10.0.2.2 is active
- Ports 135, 445, and 5357 are open
- SMB service detected (high-value target)

## Risk Level
Medium

## Analyst Notes
SMB (port 445) is commonly targeted by attackers. Exposure of this service increases risk of exploitation if not properly secured.

## Recommended Actions
- Restrict SMB access
- Apply firewall filtering
- Monitor logs for suspicious activity
