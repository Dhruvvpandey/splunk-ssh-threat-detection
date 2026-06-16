# Security Findings Report

## Executive Summary

SSH authentication logs were analyzed using Splunk SIEM to identify brute-force attacks, suspicious authentication attempts, and unauthorized access patterns.

## Analysis Methodology

The investigation used custom SPL queries to analyze:

- Failed login attempts
- Successful logins
- High-volume source IP activity
- Potential brute-force attacks

## Key Findings

### Failed Authentication Attempts

Multiple failed login attempts were observed across monitored systems.

### Brute Force Activity

Several source IP addresses generated repeated authentication failures, indicating possible brute-force attack behavior.

### Targeted User Accounts

The most frequently targeted accounts included:

- root
- admin
- ubuntu

### Source IP Analysis

A small number of source IPs generated a disproportionately high volume of failed authentication attempts.

## Risk Assessment

These findings indicate a risk of:

- Credential compromise
- Unauthorized access
- Privilege escalation
- Lateral movement

## Security Recommendations

1. Enable Multi-Factor Authentication (MFA)
2. Disable direct root SSH login
3. Implement Fail2Ban
4. Restrict SSH access using firewall rules
5. Continuously monitor authentication logs

## MITRE ATT&CK Mapping

| Technique ID | Technique |
|--------------|-----------|
| T1110 | Brute Force |
| T1078 | Valid Accounts |