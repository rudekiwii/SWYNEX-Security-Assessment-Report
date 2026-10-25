# SWYNEX — Security Assessment Report

## Overview
This repository contains a consolidated defensive security assessment based on authorized lab exercises completed as part of the SWYNEX internship tasks.

## Objectives
- Review web application security controls.
- Inspect HTTP response headers and application configuration.
- Analyze network protocols using Wireshark.
- Document observations, potential risks, and remediation recommendations.

## Tools and Environment
- OWASP Juice Shop — local training application
- Browser Developer Tools
- Wireshark 4.6.6
- Kali Linux in Oracle VirtualBox

## Assessment Activities
1. Security fundamentals assessment.
2. Network traffic analysis using DNS, TCP, and TLS display filters.
3. Defensive web security review of the local OWASP Juice Shop application.
4. Consolidation of findings into a final assessment report.

## Key Observations
- `X-Content-Type-Options: nosniff` and `X-Frame-Options: SAMEORIGIN` were observed.
- A Content Security Policy header was not visible in the inspected main document response.
- A wildcard CORS header was observed; its security impact was not established.
- Registration UI password guidance was inconsistent and requires further validation.
- TCP and TLS 1.3 traffic were observed during network analysis.

These observations are not claims of confirmed exploitable vulnerabilities. Refer to the report for scope, limitations, priorities, and recommendations.

## Main Report
[Read the consolidated security assessment report](security-assessment-report.md)

## Evidence
Supporting screenshots should be available in the `evidence/` directory and correspond to the observations described in the report.

## Scope and Disclaimer
Assessment activities were limited to authorized local training environments. No third-party systems were targeted. Sensitive credentials, session tokens, and private information should not be included in public evidence.

## Conclusion
This project demonstrates practical experience with defensive network analysis, browser-based web security review, evidence documentation, and remediation planning.

