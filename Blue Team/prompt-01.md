Triage this URL as a SOC Threat Hunter: <URL>

Context (if any): <HOW_IT_WAS_SEEN: email/proxy/EDR/user_report>
Time observed: <UTC_TIME>
Source host/user: <HOSTNAME>/<USERNAME>

Deliver:
1) Normalization (final URL after redirects if known, domain, path, params)
2) Immediate risk signals (brand impersonation, unusual TLD, punycode, URL shortener, auth bait, file download, tracking params)
3) What internal logs to check next (DNS, proxy, firewall, EDR, email gateway)
4) Hypotheses (phishing / malware delivery / C2 / benign)
5) Severity + confidence (with brief justification)
6) Recommended actions (block/allow, isolate host, reset creds, user comms)
Format: bullet points + a small table of “Signal | Why it matters | Evidence needed”.
