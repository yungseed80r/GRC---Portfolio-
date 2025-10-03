# Incident Response Tabletop Scenario
**Scenario Title:** Phishing Attack Leads to Payroll Fraud  
**Date:** 2025-10-03  

---

## Background
A phishing email is sent to multiple employees, appearing to be from HR. One employee clicks the link and enters credentials. Attacker gains access to payroll system and changes direct deposit information.

---

## Objectives
- Test ability to detect phishing and escalate appropriately.
- Assess communication flow between IT, HR, and Legal.
- Evaluate containment and recovery procedures.

---

## Injects (Events During Exercise)
1. Employee reports suspicious email to IT.
2. SIEM detects multiple failed logins from overseas IP.
3. Payroll change request submitted from compromised account.
4. Rumors spread on Slack about “hacked payroll.”

---

## Discussion Questions
- How quickly is the phishing identified?  
- Who approves containment actions (e.g., disabling account)?  
- How is communication handled internally and externally?  
- What evidence is collected for investigation?  
- What changes would you recommend post-incident?
