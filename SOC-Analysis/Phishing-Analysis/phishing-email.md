# Phishing Email Investigation

## Alert
User reported suspicious email requesting password reset.

## Email Details
Sender: security@micros0ft-support.com  
Subject: Urgent Password Reset Required  
Attachment: password_reset.html  

## Investigation Steps
- Checked sender domain
- Analyzed email headers
- Inspected embedded links
- Scanned URL with VirusTotal
- Checked domain reputation

## Findings
Domain is fake and impersonating Microsoft.
Link redirects to credential harvesting page.

## Indicators of Compromise
micros0ft-support.com
185.199.110.153

## MITRE ATT&CK
T1566 - Phishing

## Risk Level
High

## Response
- Block domain
- Alert users
- Delete email
- Monitor for similar messages

## Conclusion
Confirmed phishing attack attempting credential theft.
