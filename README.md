SOC L1 Portfolio (Microsoft Sentinel + KQL)
This repo contains short, SOC-style investigation tickets and one basic detection rule created in Microsoft Sentinel.
Each case includes: alert summary, triage steps, evidence (KQL), IOCs, impact assessment, and recommended response/escalation.

Contents
Cases (2 Sentinel triage + 2 phishing investigations): /cases
Detection (1 analytics rule): /detections
KQL snippets used during investigations: /kql
How I work (L1 triage approach)
Validate the alert (is it real? what’s the scope?)
Gather evidence (timeline, affected user/host/IP, related alerts)
Decide disposition (benign / true positive / needs escalation)
Contain/escalate with clear next steps and documentation
