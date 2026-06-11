# PCI DSS v4.0 Gap Assessment — Enterprise Portfolio Project

![PCI DSS](https://img.shields.io/badge/PCI%20DSS-v4.0-1B3A6B?style=flat-square)
![Status](https://img.shields.io/badge/Status-Complete-2E7D32?style=flat-square)
![Deliverables](https://img.shields.io/badge/Deliverables-15-2E75B6?style=flat-square)
![Controls](https://img.shields.io/badge/Controls%20Assessed-251-orange?style=flat-square)
![Findings](https://img.shields.io/badge/Findings-34-C00000?style=flat-square)

---

## Overview

A complete, enterprise-grade PCI DSS v4.0 Gap Assessment engagement simulating real QSA consulting work — built as a portfolio project to demonstrate practical competency in compliance assessment, IT audit methodology, risk management, and executive reporting.

**Fictional Client:** WhaleAX Financial Consulting Services Pvt Ltd  
**Engagement Reference:** WAX-PCI-2025-001  
**Assessment Period:** April – June 2025  
**PCI DSS Version:** v4.0 (March 2022)

---

## Compliance Snapshot

| Metric | Result |
|---|---|
| Requirements Assessed | 12 of 12 |
| Controls Evaluated | 251 |
| Overall Compliance Score | 45% |
| Critical Findings | 3 |
| High Findings | 12 |
| Medium Findings | 15 |
| Low Findings | 4 |
| Evidence Items Reviewed | 29 |

---

## Key Findings

| ID | Finding | Requirement | Risk |
|---|---|---|---|
| F-001 | Critical CVEs unpatched 97 days past SLA (CVSS 9.8–9.9) | Req 6.3.3 | 🔴 Critical |
| F-002 | Firewall rule review missing for Q4 2024 and Q1 2025 | Req 1.3.2 | 🔴 Critical |
| F-003 | 14/25 analyst accounts over-provisioned; 3 shared service account credentials | Req 7.2.1 | 🔴 Critical |
| F-004 | Network segmentation not validated by penetration test in 12 months | Req 1.4.2 | 🟠 High |
| F-005 | No formal daily log review procedure or evidence | Req 10.4.1 | 🟠 High |
| F-009 | Log retention at 9 months — below 12-month PCI DSS minimum | Req 10.5.1 | 🟠 High |

---

## Deliverables

### Word Documents
| # | Document | Description |
|---|---|---|
| 1 | Project Charter | Scope, methodology, governance, sign-off framework |
| 2 | Executive Summary Report | C-suite findings brief and recommendations |
| 3 | Final Gap Assessment Report | Full requirement-by-requirement findings report |
| 4 | Risk Assessment Report | ISO 31000 risk analysis with 5×5 matrix |
| 5 | Remediation Roadmap & MAP | 20-item Management Action Plan, 4 phases |
| 6 | Security Governance Reviews | Access control, firewall, logging, vuln mgmt, config, TPRM |

### Excel Workbooks
| # | Document | Description |
|---|---|---|
| 7 | Gap Assessment Workbook | All 251 controls, testing method, evidence, status |
| 8 | Findings Register | 34 findings with risk ratings, owners, target dates |
| 9 | Risk Register | 10 risks, inherent/residual ratings, existing controls |
| 10 | Evidence Tracker | 29 ERL items, status, overdue flags |
| 11 | Compliance Dashboard & Scorecard | KPI boxes, bar and pie charts |
| 12 | Asset Inventory & Data Classification | 11 in-scope assets, data classification matrix |
| 13 | PCI DSS Applicability Matrix | 12 requirements × 11 systems |

### PowerPoint
| # | Document | Description |
|---|---|---|
| 14 | Audit Presentation Deck | 12-slide executive presentation |

---

## Environment Assessed (Fictional)

- **Cloud:** AWS Production VPC (us-east-1)
- **App Servers:** WAX-APP-01, WAX-APP-02 (Amazon Linux 2 / Apache)
- **Database:** WAX-DB-01 (RDS PostgreSQL 14)
- **Firewall:** WAX-FW-01 (AWS Network Firewall)
- **SIEM:** WAX-SIEM-01 (Splunk Enterprise 9.1)
- **MFA:** WAX-MFA-01 (Okta Identity Cloud)
- **Vuln Mgmt:** WAX-VULN-01 (Tenable.io)
- **Workstations:** 25 analyst workstations (Windows 10/11)

---

## Skills Demonstrated

`PCI DSS v4.0` `IT Audit Methodology` `Gap Analysis` `Risk Assessment`  
`Evidence Management` `Findings Development` `Remediation Planning`  
`ISO 31000` `AWS Security Architecture` `IAM & Access Control Review`  
`Vulnerability Management` `SIEM & Log Review` `Executive Reporting`  
`CVSS Scoring` `CIS Benchmarks` `Third-Party Risk Management`

---

## Disclaimer

All organisations, personnel, systems, vulnerabilities, and findings in this project are entirely fictional and created for portfolio demonstration purposes only. This project does not represent real client work.

---

*Built by Yash Shukla | www.linkedin.com/in/yashshuklagrc25 | www.yashshukla.in *
