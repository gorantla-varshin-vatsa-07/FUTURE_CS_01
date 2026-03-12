# Vulnerability Assessment Report - Task 1

## Internship Details
Program: Future Interns - Cyber Security Track
Task 1 - Vulnerability Assessment Report
Assessed by: Gorantla Varshin Vatsa
Date: 14 March 2026

## Website Tested
Target: OWASP Juice Shop
URL: https://demo.owasp-juice.shop
Type: Intentionally vulnerable web application (safe for testing)

## Scope
Public-facing pages only
Passive scanning — no exploitation performed
Header and configuration analysis
Directory exposure check
No login bypass attempted
No denial-of-service attacks

## Tools Used
OWASP ZAP (Passive Scan)
Browser DevTools (Chrome)
SecurityHeaders.com
Direct URL Inspection

## Findings Summary
| # | Vulnerability | Risk Level |

| 1 | Missing Content-Security-Policy | 🔴 High |
| 2 | Missing Strict-Transport-Security | 🔴 High |
| 3 | Wildcard CORS Policy | 🔴 High |
| 4 | Exposed FTP Directory | 🔴 High |
| 5 | Missing Referrer-Policy | 🟡 Medium |
| 6 | Missing Permissions-Policy | 🟡 Medium |
| 7 | Server Information Disclosure | 🟡 Medium |
| 8 | Deprecated Feature-Policy Header | 🟢 Low |
| 9 | Unusual X-Recruiting Header | 🟢 Low |

## Overall Security Rating
🔴 Grade D (Poor) - as rated by SecurityHeaders.com

## Repository Contents
FUTURE_CS_01_Report.pdf - Full vulnerability assessment report
screenshots/ - Evidence screenshots from the assessment
README.md — This file

## Ethical Statement
This assessment was conducted passively and ethically, No exploitation, login bypass, brute force, or denial-of-service attacks were performed. All testing was limited to public-facing pages only.
