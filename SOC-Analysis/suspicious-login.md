# Suspicious Login Investigation

## Alert
Multiple failed login attempts detected from a single IP address.

## Data Observed
- Username: admin
- Attempts: 25 failed logins
- Source IP: 185.220.101.4
- Time: 03:14 AM

## Investigation Steps
- Checked login failures
- Identified repeated attempts
- Verified targeted account
- Checked IP reputation

## Findings
Possible brute force attack detected.

## MITRE ATT&CK
T1110 - Brute Force

## Risk Level
High

## Response
- Block IP
- Force password reset
- Enable MFA
- Monitor logs

## Logs Example

Failed login from 185.220.101.4
Failed login from 185.220.101.4
Failed login from 185.220.101.4
Failed login from 185.220.101.4

User: admin
Status: Failed
Action: login attempt

## Analyst Notes
Repeated login attempts detected targeting admin account.
Behavior consistent with brute force attack.

## Conclusion
Confirmed malicious activity.
