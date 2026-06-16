# SSH Brute Force Detection and Security Monitoring using Splunk SIEM

## Project Overview

This project demonstrates how Splunk SIEM can be used to detect SSH brute-force attacks, monitor authentication activity, and identify suspicious login behavior from Linux SSH authentication logs.

## Objectives

* Detect failed login attempts
* Identify brute-force attacks
* Analyze source IP activity
* Monitor successful authentications
* Generate security insights using Splunk dashboards

## Tools Used

* Splunk Enterprise
* SPL (Search Processing Language)
* Linux SSH Logs
* Cybersecurity Analytics

## Detection Use Cases

### Failed Login Monitoring

Track unsuccessful authentication attempts.

### Brute Force Detection

Identify repeated login failures from the same source IP.

### Source IP Profiling

Analyze attacker behavior and frequency.

### Successful Login Monitoring

Track successful authentications and user activity.

## Dashboard Screenshots

Screenshots are available in the screenshots directory.

## MITRE ATT&CK Mapping

| Technique | Description    |
| --------- | -------------- |
| T1110     | Brute Force    |
| T1078     | Valid Accounts |

## Key Findings

* Repeated failed login attempts identified
* Multiple suspicious source IPs detected
* Brute-force attack patterns observed

## Security Recommendations

* Enable Multi-Factor Authentication
* Disable direct root login
* Implement Fail2Ban
* Restrict SSH access using firewall rules

## Author

Dhruv Pandey
