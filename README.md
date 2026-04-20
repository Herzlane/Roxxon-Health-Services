# Roxxon Health Services - Enterprise Infrastructure Lab
**Role:** Implementation Specialist
**Environment:** Windows Server 2022, Active Directory, GPO, Entra ID (Hybrid)

## Project Objective
This repository documents the end-to-end implementation of a secure, enterprise-grade clinical infrastructure. The lab simulates a multi-pavilion hospital environment, focusing on identity governance, security isolation, and automated endpoint deployment.

## Technical Architecture & Milestones
* **Identity Management:** Established a multi-tier Organizational Unit (OU) structure for Clinical, Administrative, and Support departments.
* **Security & Compliance:** Implemented Role-Based Access Control (RBAC) with explicit NTFS "Deny" overrides to protect sensitive patient records.
* **Automation:** Deployed Group Policy Objects (GPOs) for mandatory workstation security lockouts and automated network drive mapping.
* **Hybrid Readiness:** Integrated on-premise Active Directory with Entra ID to simulate modern cloud identity governance.

## Staffing & Organizational Structure
The infrastructure supports a diverse staff hierarchy across three main campus sectors:
* **Apex Center:** Executive Administration, Legal, and Compliance.
* **Clinical Pavilions:** Inpatient/Outpatient Medical, Nursing, and Surgery.
* **Vanguard Hall:** IT Operations, Physical Security, and Logistics.
