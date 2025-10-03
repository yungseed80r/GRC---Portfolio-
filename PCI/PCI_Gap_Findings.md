# PCI DSS v4.0 Gap Assessment Findings

**Assessment Date:** 2025-10-03  
**Assessor:** Alexander T. Ramos  

---

## Summary
This assessment compared current controls against PCI DSS v4.0 requirements.  
Of the 10 sample controls reviewed, **6 were compliant**, **4 had gaps** requiring remediation.

---

## Compliant Controls
- Requirement 1.2 – Firewall in place to protect cardholder data environment (CDE).  
- Requirement 2.2 – Vendor defaults removed; secure configurations applied.  
- Requirement 6.4 – Secure software development practices in place.  
- Requirement 10.2 – Logging and audit trails enabled.  
- Requirement 11.3 – Penetration tests conducted annually.  
- Requirement 12.6 – Security awareness training conducted annually.  

## Gaps Identified
- Requirement 3.5 – Stored cardholder data not tokenized or vaulted.  
- Requirement 8.4 – Multi-factor authentication not enforced for CDE access.  
- Requirement 9.4 – Physical access controls incomplete for server room.  
- Requirement 12.10 – Incident response plan exists but not tested.  

---

## Recommendations
- Implement tokenization or vaulting for stored account data.  
- Enforce MFA for all users accessing CDE systems.  
- Strengthen physical security for server room (badges, cameras, logs).  
- Conduct annual incident response tabletop exercises.
