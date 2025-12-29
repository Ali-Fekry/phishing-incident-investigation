# Incident Report: Phishing Attack Leading to Account Compromise

## 1. Incident Summary
A phishing email impersonating a legitimate service was delivered to a user. The user entered credentials into a malicious website, resulting in unauthorized access to the account.

## 2. Detection Method
The incident was detected through a user-reported suspicious email and analysis of authentication logs showing abnormal login activity.

## 3. Phishing Email Analysis
The email contained multiple phishing indicators, including:
- Spoofed sender domain
- Urgent language
- Malicious credential-harvesting link

## 4. Evidence Collected
- Phishing email content
- Authentication logs showing suspicious logins and password change

## 5. Attack Classification
Attack Type: Phishing  
Impact: Account Compromise

## 6. MITRE ATT&CK Mapping
Tactic: Initial Access  
Technique: Phishing (T1566)

## 7. Incident Response Actions
- Validated phishing email
- Reset compromised account credentials
- Revoked active sessions
- Forced password reset
- Recommended user awareness training

## 8. Impact Assessment
One finance user account was compromised. No evidence of lateral movement or data exfiltration was found.

## 9. Lessons Learned
Improved phishing awareness training and stronger email filtering controls are required to reduce future incidents.
