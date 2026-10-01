# ONeill Contractors Inc.
## Enterprise Google Workspace Shared Drive Architecture & AI Database Explorer
**Standard Operating Procedure:** SOP-ADM-001 v3.3  
**System Engine:** Google Workspace Shared Drives + AI Vector Database Index  
**Gatekeeper Integration:** Streamlit Document Controller Application  

---

### 📌 Overview

This repository hosts the interactive web-based explorer for **ONeill Contractors Inc.**'s board-approved document control and file architecture system (SOP-ADM-001 v3.3). 

The interactive dashboard provides leadership, estimators, project managers, and auditors with a live, visual demonstration of how ONeill Contractors structures its cloud infrastructure as a **relational and vector-indexed document database** designed for automated AI agents and enterprise search.

---

### 🚀 Key Architectural Features

* **3-Tier Shared Drive Security Model:** Enforces zero-trust isolation across `ONEILL-CORPORATE` (C-Suite Restricted), `ONEILL-TEAM` (All-Staff Operational Hub), and `SAWTOOTH` (Joint Venture Workspace).
* **Universal Industry Client Acronyms:** Replaces artificial codes with standard agency acronyms (`USACE`, `ARMY`, `NAVFAC`, `ANG`, `FAA`, `GSA`, `VA`, `FBI`, `DOL`, `GLN`).
* **Single Lifecycle Project Container:** Eliminates paperwork loss during Estimating-to-PM handoffs by storing all project records—from initial bidding through closeout—inside a single job container (`[YY]-[CLI]-[PRJ]_[Description]`).
* **Dynamic Provisioning Threshold ($50,000):** Provisions a 15-subfolder template for major jobs ($\ge \$50k$) and a 5-subfolder template for micro-repair orders ($<\$50k$).
* **CSI MasterFormat Trade Quotations:** Incorporates standard CSI trade subfolders inside `13-Subs` (`Div-03-Concrete`, `Div-26-Electrical`) to organize 100+ subcontractor proposals without folder clutter.
* **100% Self-Describing Standalone Files:** Enforces an AI-tokenizable naming syntax (`[YY]-[CLI]-[PRJ]_[DocType]_[CSI/Sec]_[Description]_[YYYY-MM-DD]_[Version].[ext]`) containing human-readable trade descriptors so anyone inside or outside construction can immediately identify detached documents.
* **Guaranteed Windows Path Safety:** Eliminates Windows 255-character path crashes (`MAX_PATH`) by mapping local sync points to virtual drive letter `O:\` (leaving a 65+ character safety margin under the 210-character target budget).

---

### 🛠️ Interactive Dashboard Capabilities

* **Tree Explorer:** Expand and collapse shared drive nodes down to individual document specifications.
* **Live Inspection Panel:** Click any folder or file to calculate its exact character length, safety margin gauge, access permissions, and SOP directive rules in real time.
* **Instant Keyword Filter:** Search across all three drives by keyword (`USACE`, `ARMY`, `QUO`, `Div-26`, `01-Contracts`).
* **View Controls:** Instant **Expand All**, **Collapse All**, and **Reset View** toolbar controls for boardroom presentations.

---

### 📄 Documentation Standards

| Field | Value |
| :--- | :--- |
| **Document ID** | SOP-ADM-001 v3.3 |
| **Proposal Date** | October 1, 2026 |
| **Personnel Scope** | ~50 Full-Time Staff |
| **Database Engine** | Google Workspace / Vector Index |
| **Lifecycle Model** | Single Project Container |
| **System Gatekeeper** | Streamlit Controller Application |
