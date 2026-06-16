Detection Logic

Use Case 1: SSH Brute Force Detection

Objective

Detect repeated failed authentication attempts from the same source IP.

Logic

* Authentication failures > 20
* Within a short time window
* Same source IP

Severity

High

⸻

Use Case 2: Nmap Reconnaissance Detection

Indicators

* SSH-2.0-Nmap-SSH2-Hostkey
* SSH-1.5-NmapNSE_1.0
* SSH-1.5-Nmap-SSH1-Hostkey

Severity

Medium

⸻

Use Case 3: Successful Login After Multiple Failures

Objective

Identify potential account compromise.

Logic

* Multiple failures
* Followed by successful authentication

Severity

Critical

⸻

Use Case 4: High Volume Attacker Activity

Objective

Identify top attacking IP addresses.

Logic

* Count events by source IP
* Rank highest volume attackers

Severity

High