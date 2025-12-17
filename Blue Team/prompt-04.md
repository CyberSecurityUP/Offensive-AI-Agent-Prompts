Act as a SOC analyst investigating a suspected phishing URL: <URL>

Email context:
- Sender: <FROM>
- Subject: <SUBJECT>
- Received time: <TIME>
- Targeted users: <COUNT/DEPT>
- Any attachments? <YES/NO + TYPE>
- User interaction: <CLICKED/OPENED/CREDENTIALS_ENTERED/UNKNOWN>

Deliver:
- Phishing likelihood assessment (with reasons)
- What to hunt in email gateway logs (message IDs, similar subjects, lookalike senders)
- What to hunt in proxy/DNS after the email time window
- Containment playbook (user actions + technical blocks)
- Communication snippet to send users (2–3 lines, non-technical)
