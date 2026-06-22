# Part C: Risk Assessment Activity

**Scenario:** Acting as a Security Analyst for a college, I conducted a risk assessment across key institutional assets to identify threats, assess their potential impact, and assign risk levels accordingly.

| Asset | Threat | Impact | Risk Level |
|---|---|---|---|
| Student Login Portal | Credential Stuffing / Brute Force | High | High |
| Examination Results Database | Unauthorized Modification | High | High |
| College Email System | Phishing / Business Email Compromise | Medium | High |
| Staff Payroll System | Insider Fraud / Data Theft | High | High |
| Campus Wi-Fi Infrastructure | Unauthorized Access / Rogue Access Points | Medium | Medium |
| College Mobile App | API Vulnerabilities / Data Interception | Medium | Medium |
| CCTV & Physical Security Systems | Tampering / Unauthorized Access | Medium | Medium |
| Cloud Storage (Google Drive / OneDrive) | Misconfiguration / Public Link Exposure | High | High |

## Notes on Assessment

- **Student Login Portal** is a critical target because compromised credentials can provide access to personal data, course records, and linked services — making brute-force and credential-stuffing attacks both likely and high-impact.
- **Examination Results Database** is rated high risk because unauthorized modification (changing grades) is an integrity attack with serious academic and legal consequences.
- **College Email System** is elevated to high risk because email is the primary delivery mechanism for phishing — a single compromised staff account can be used to launch further attacks internally.
- **Cloud Storage** is frequently overlooked but carries high risk due to the ease with which files can be accidentally shared publicly through misconfigured sharing settings.

Risk Level was assigned based on a combination of **likelihood** (how probable the threat is given current practices) and **impact severity** (the consequence if the threat materializes). High likelihood + high impact = High risk.
