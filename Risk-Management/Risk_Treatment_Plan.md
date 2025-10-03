# Risk Treatment Plan
Generated: 2025-10-03

This plan lists actions to reduce, avoid, transfer, or accept risks identified in the **Risk Register**. Reference risks by **Risk ID**.

| Risk ID | Risk Title (Asset + Threat) | Current Level | Treatment Strategy | Actions | Owner | Budget | Target Date | Status |
|---|---|---|---|---|---|---|---|---|
| RR-001 | Web App – SQL Injection | High | Reduce | Implement WAF rules; add CI/CD SAST; developer training | App Owner / Sec Eng | $5,000 | 2025-08-01 | Open |
| RR-002 | IdP – Credential Stuffing | Medium | Reduce | Rate limiting; password manager rollout; monitor auth anomalies | IT Sec | $2,500 | 2025-07-15 | Open |
| RR-003 | Payment – Data Exfiltration | Medium | Transfer/Reduce | Review cyber insurance; harden S3 policies; enable access logs | Finance/IT | $4,000 | 2025-07-31 | Open |
| RR-004 | HR – Phishing Payroll Fraud | Medium | Reduce | Awareness + phishing simulations; DMARC enforcement | HR Lead / IT | $1,000 | 2025-07-20 | Open |

**Acceptance Criteria:** Risks may be accepted when score < 9 *and* residual risk aligns with risk appetite.  
**Review Cadence:** Monthly for High, quarterly for Medium, semi-annually for Low.
