# Security Portfolio — Andrew Jamieson

Defensive and assessment-focused security work: web and network penetration
testing, malware analysis, and incident response. All work was carried out in
academic, lab, or authorised-assessment settings against deliberately
vulnerable targets, provided lab environments, or mock clients — never against
third-party production systems.

## Contents

| Report | Area | Summary |
|--------|------|---------|
| [Web Application Penetration Test](reports/web-application-penetration-test.pdf) | Web app security | OWASP/WSTG-based assessment of a client web application. Identification, exploitation, and remediation of SQL injection, cleartext credential transmission, weak session handling, and weak password policy, using Burp Suite, OWASP ZAP, nmap, Nikto, and manual testing. |
| [Penetration Test Report (2023–2024)](reports/penetration-test-report-2023-2024.docx) | Infrastructure / pentest | End-to-end penetration test: reconnaissance, enumeration, exploitation, and a prioritised remediation write-up. |
| [Malware Analysis Report](reports/malware-analysis-report.pdf) | Malware analysis / RE | Static and dynamic triage of a real-world ransomware sample using strings, FLOSS, capa, and disassembly, with indicators and behavioural analysis. |
| [Malware Infection Incident Response](reports/malware-infection-incident-response.docx) | Incident response | Investigation and response to a simulated malware infection incident: scoping, containment, eradication, and lessons learned. |
| [Network Security Report](reports/network-security-report.docx) | Networking | Network design and security assessment, including addressing, segmentation, and defensive recommendations. |

## Methodology

Assessments follow recognised industry frameworks (OWASP WSTG for web testing;
standard reconnaissance → enumeration → exploitation → reporting for
infrastructure). Automated tooling is paired with manual testing to reduce
false negatives, and every finding is paired with a concrete remediation.

## Note

These are academic and lab deliverables published as work samples. Any
client or target names are fictional or scoped lab environments.
