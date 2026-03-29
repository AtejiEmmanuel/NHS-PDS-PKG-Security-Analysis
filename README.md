# NHS-PDS-PKG-Security-Analysis

> **MSc Cyber Security Dissertation | Sheffield Hallam University | 2024**

## Overview

This repository contains the dissertation report for an MSc in Cyber Security submitted to Sheffield Hallam University in September 2024. The research critically evaluates the **security implications of integrating the Parkinson's KinetiGraph (PKG) wearable device with the NHS Spine's Personal Demographics Service (PDS)**, a highly relevant case study at the intersection of healthcare wearable technology and national health IT infrastructure security.

---

## Research Title

**"Evaluating the Security of the NHS Spine's Personal Demographics Service (PDS) and Its Integration with the Parkinson's KinetiGraph Wearable Device: An Analysis of Data Handling Practices and Potential Threats"**

**Author:** Emmanuel Ateji  
**Student ID:** 33043543  
**Supervisor:** Kavyan Zoughalian  
**Institution:** Sheffield Hallam University, Faculty of Business, Technology and Engineering  
**Submission Date:** 10th September 2024  

---

## Abstract

As healthcare systems increasingly adopt wearable technologies, the security risks associated with integrating these devices into national health infrastructure become critically important. This study examines the security landscape of connecting the **Parkinson's KinetiGraph (PKG)**, a wearable device used for continuous monitoring of Parkinson's Disease symptoms, with the **NHS Spine's Personal Demographics Service (PDS)**.

Key findings include:
- While the NHS Spine and PDS employ robust baseline security (strong authentication, encryption), the integration of wearable devices **introduces new and unique vulnerabilities**
- Identified risks include **unauthorised access, data interception**, and challenges maintaining **data integrity** across integrated systems
- Complexities around **patient consent and continuous health data privacy** are significant and underexplored in current governance frameworks

The research proposes a **phased, multi-layered security enhancement framework** covering authentication hardening, secure data transmission, and rigorous API management practices.

---

## Research Aims & Objectives

The study was designed around three core investigative themes:

1. **Evaluate existing security measures** within the NHS Spine and PDS infrastructure
2. **Assess the security impact** of integrating the PKG wearable device with PDS
3. **Identify vulnerabilities and threats** specific to the PDS-PKG integration
4. **Propose actionable recommendations** for mitigating identified risks

### Research Questions

- What security measures currently exist within the NHS Spine's PDS?
- How does the integration of the PKG wearable device affect the security of PDS?
- What are the key threats and vulnerabilities introduced by this integration?
- What recommendations can be made to enhance security across the integrated system?

---

## Methodology

| Element | Detail |
|---|---|
| **Research Type** | Qualitative |
| **Approach** | Case Study |
| **Data Collection** | Document Analysis & Literature Review |
| **Analysis Method** | Thematic Analysis (Six-Phase Framework) |
| **Ethical Considerations** | No primary human subjects; secondary data only |

A qualitative case study approach was adopted to allow deep, contextual investigation of the NHS Spine, PDS functionality, and PKG integration. Document analysis drew on NHS technical documentation, regulatory frameworks, and published academic literature.

---

## Key Themes & Findings

### Theme 1 — NHS Spine & PDS Infrastructure
Analysis of the Spine's core services, PDS functionality and scope, data integration and access mechanisms, system components, and interoperability standards.

### Theme 2 — Security Measures & Data Protection
Examination of authentication and access control (including Smart Card systems), data encryption and transmission security, and data protection governance (GDPR, NHS DSP Toolkit, Data Security Standards).

### Theme 3 — PKG Integration & Its Impact on Data Security
Review of PKG watch specifications and features, data handling and lifecycle management, integration challenges, and regulatory/approval considerations.

### Theme 4 — Security Threats & Vulnerabilities in PDS-PKG Integration
Identification of integration-specific risks including:
- Unauthorised access risks
- Data interception vulnerabilities
- API security weaknesses
- Data integrity challenges across systems
- Consent management complexity in continuous monitoring contexts

### Theme 5 — Recommendations for Enhanced Security
A prioritised, phased set of security recommendations including:
- Enhanced multi-factor authentication protocols
- Secured and monitored data transmission pathways
- Rigorous API lifecycle management
- Strengthened patient consent and data governance frameworks
- Continuous security monitoring and incident response planning

---

## Repository Contents

```
/
├── README.md                        ← This file
└── PKG-NHS-Spine-Security-Dissertation.PDF   ← [Full dissertation report](https://github.com/AtejiEmmanuel/NHS-PDS-PKG-Security-Analysis/blob/main/PKG-NHS-Spine-Security-Dissertation.pdf)
```

---

## Key Technologies & Systems Discussed

- **NHS Spine** — the national IT infrastructure underpinning NHS digital services
- **Personal Demographics Service (PDS)** — the national electronic database of NHS patient demographic data
- **Parkinson's KinetiGraph (PKG)** — a wrist-worn wearable device for objective, continuous monitoring of Parkinson's Disease motor symptoms
- **HL7 FHIR** — healthcare data interoperability standards
- **Smart Card Authentication** — NHS Role-Based Access Control (RBAC) system
- **TLS/HTTPS Encryption** — data-in-transit security protocols
- **GDPR & NHS DSP Toolkit** — regulatory and compliance frameworks

---

## Relevance & Contribution

This dissertation contributes to a relatively underexplored intersection: **the cybersecurity implications of wearable medical devices connecting to national health IT systems**. It provides:

- A structured security threat analysis for the PKG-PDS integration scenario
- A practical, prioritised recommendations framework applicable to similar healthcare IoT integrations
- A foundation for future empirical research in this rapidly evolving space
- Insights relevant to healthcare organisations, NHS digital teams, and wearable technology providers

---

## Academic Context

This work was submitted in partial fulfilment of the requirements for the **Master of Science in Cyber Security** at Sheffield Hallam University. It does not contain confidential material and has been cleared for sharing via the university library.

---

## Disclaimer

This repository is shared for academic and portfolio purposes. All research findings, analysis, and recommendations are the independent academic work of the author and do not represent the views or official positions of the NHS, Sheffield Hallam University, or any other organisation mentioned within the dissertation.
