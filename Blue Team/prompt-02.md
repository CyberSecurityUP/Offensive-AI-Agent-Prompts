Analyze this IP for SOC triage: <IP>

Seen in: <FIREWALL/PROXY/DNS/EDR/SIEM>
Direction: <INBOUND/OUTBOUND>
Protocol/port: <PROTO:PORT>
First seen / last seen: <TIMES>
Asset involved: <HOSTNAME/IP/OWNER/CRITICALITY>

Deliver:
- Likely role (CDN/cloud/VPN/residential/hosting) and what that implies
- High-risk indicators (ASN patterns, uncommon ports, bursty beacons, geo anomalies, TOR/VPN hints)
- Internal correlation checklist (netflow, DNS, process tree, user activity)
- Severity + confidence
- Next steps: contain / monitor / block / escalate
Output: “Finding Summary”, then “Evidence to Collect”, then “Decision”.
