 SOC Incident Response Case Studies
Overview

This repository presents a curated portfolio of Security Operations Center (SOC) incident response case studies designed to demonstrate my hands-on capability in alert triage, log analysis, investigation, correlation, and incident documentation.

All incidents are based on simulated security events generated within controlled training and home-lab environments. The emphasis of this portfolio is not on specific tools, but on analytical thinking, investigative methodology, and decision-making aligned with real-world SOC operations.

What This Repository Demonstrates

Through these case studies, I demonstrate the ability to:

Perform initial alert triage and risk-based severity classification

Analyze endpoint, authentication, network, and application logs

Correlate multiple events to identify attack patterns

Differentiate true positives, false positives, and benign activity

Investigate incidents across different stages of the attack lifecycle

Document findings clearly using SOC-style incident reports

Communicate technical conclusions suitable for both technical teams and stakeholders

Incident Case Studies Included
1. Suspicious PowerShell Activity on a Windows Endpoint

Category: Endpoint Security
Focus Areas:

Process execution analysis

Encoded PowerShell command detection

Endpoint investigation and containment

Outcome:

Suspicious activity investigated and validated

No persistence or lateral movement identified

2. Suspected Brute-Force Login Attempt Against a Privileged Account

Category: Authentication Security
Focus Areas:

Failed login pattern analysis

Privileged account monitoring

Attack validation and escalation decisions

Outcome:

Brute-force attempt detected and contained

No unauthorized access observed

3. Login from an Unusual Geographic Location

Category: Identity & Access Management
Focus Areas:

Anomalous login detection

User behavior analysis

False-positive validation

Outcome:

Activity confirmed as legitimate

Alert closed after verification

4. Potential Lateral Movement via Remote Service Creation

Category: Endpoint & Network Security
Focus Areas:

Event correlation across multiple hosts

Remote service creation analysis

Lateral movement detection techniques

Outcome:

Suspicious service activity identified and contained

No further propagation observed

5. Suspicious PowerShell Script Download and Execution

Category: Endpoint Security
Focus Areas:

Script-based attack detection

Command-line and execution policy analysis

Outbound network activity review

Outcome:

Malicious execution pattern identified

Endpoint protected from further exploitation

6. Credential Dumping Attempt via LSASS Access

Category: Credential Access
Severity: Critical
Focus Areas:

LSASS access monitoring

Process legitimacy verification

High-risk attack stage response

Outcome:

Credential access attempt blocked

Endpoint isolated before compromise

7. Web Application Attack Attempt (SQL Injection)

Category: Web Security
Focus Areas:

Web server log analysis

Attack payload identification

Exploitation validation

Outcome:

Attack attempt detected and mitigated

No data exposure or application compromise

Approach & Methodology

Each incident follows a structured SOC-style workflow:

Alert detection and initial triage

Log and evidence analysis

Event correlation and investigation

Impact and risk assessment

Response and mitigation actions

Lessons learned and case closure

Log excerpts included in the reports are sanitized and minimal, focusing on relevant fields rather than raw data dumps, mirroring real SOC documentation practices.

Tools & Concepts Referenced

Specific vendor tools are intentionally abstracted. The investigations are based on common SOC concepts and telemetry, including:

Windows Security Event Logs

Endpoint process and service creation events

Authentication and access logs

Network and web server logs

SIEM alerting and correlation logic

Incident severity classification and escalation

Important Note on Data Authenticity

All incidents, logs, and scenarios in this repository were generated within simulated environments for training and demonstration purposes only.
No production, enterprise, or customer data is included.

This portfolio is intended to demonstrate analytical capability, investigative approach, and SOC-ready documentation, not access to real organizational systems.

About Me

I am an aspiring SOC Analyst (L1 / early L2) with hands-on experience in log analysis, incident triage, and security monitoring through structured training and home-lab practice. I focus on building job-ready defensive security skills aligned with modern SOC operations and continuously improving my incident response capabilities.
