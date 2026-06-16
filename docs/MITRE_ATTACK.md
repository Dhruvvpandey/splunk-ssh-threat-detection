MITRE ATT&CK Mapping

Overview

Observed attack activity was mapped to the MITRE ATT&CK framework to identify adversary tactics and techniques.

⸻

Technique Mapping

Technique ID	Technique	Description
T1110	Brute Force	Repeated authentication attempts against SSH services
T1046	Network Service Discovery	Discovery of exposed services through scanning
T1595	Active Scanning	Reconnaissance activity observed from attacker hosts
T1078	Valid Accounts	Potential use of legitimate credentials after brute-force attempts
T1021	Remote Services	SSH used as a remote access mechanism

⸻

ATT&CK Tactics

Reconnaissance

* T1595 Active Scanning

Discovery

* T1046 Network Service Discovery

Credential Access

* T1110 Brute Force

Lateral Movement

* T1021 Remote Services

Persistence

* T1078 Valid Accounts

⸻

Security Monitoring Coverage

The implemented Splunk detections provide visibility into reconnaissance, authentication abuse, and unauthorized access attempts.