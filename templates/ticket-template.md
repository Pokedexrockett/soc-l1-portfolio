Ticket:
Date:
Environment: Microsoft Sentinel (Azure)
Category: <Authentication | Endpoint | Email/Phishing | Other>
Severity: <Informational | Low | Medium | High>
Status/Disposition: <True Positive | Benign Positive | False Positive | Needs Escalation>

1) Alert summary (3–5 lines)
What triggered:
Entity/entities involved (user/host/IP):
Why this is concerning:
2) Triage checklist (what I did)
 Confirm alert details in Sentinel (rule name, entities, time range)
 Identify impacted scope (how many users/hosts? one or many?)
 Look for related activity (adjacent alerts, same IP, same user)
 Collect evidence (key logs + KQL results)
 Decide disposition and next steps
3) Evidence (include KQL + what it showed)
Key findings
Finding 1:
Finding 2:
Finding 3:
KQL used
// paste query 1
// paste query 2

4) Indicators (IOCs)
IPs:
Domains/URLs:
File hashes:
Processes/commands:
Other:
5) Impact assessment
Affected user(s):
Affected host(s):
Data at risk (if any):
Business impact (plain language):
6) Recommended response (L1 actions)
Immediate:
Containment (if applicable):
User comms (if applicable):
Escalation notes (what I’d send to L2/IR):
7) Notes / what I’d improve next time
Tuning ideas / false positives:
Missing telemetry I’d want:
