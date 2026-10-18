---
title: "Standard Operating Procedure: Membership Roster Management and Voting Eligibility Verification"
subtitle: "California Forest Pest Council (CFPC) — SOP-006"
author: "CFPC Secretary & Executive Committee"
date: "October 2026"
output:
  html_document:
    toc: true
    toc_depth: 3
    toc_float: true
    theme: readable
    highlight: tango
  pdf_document:
    toc: true
    toc_depth: 3
---

# ARTICLE I. PURPOSE AND GOVERNING AUTHORITY

1. **Purpose:** This Standard Operating Procedure (SOP) operationalizes **Section 2.02** (Membership Records), **Section 3.04** (Duties of Secretary), and **Article VI** (Voting Rights and Eligibility) of the California Forest Pest Council (CFPC) Bylaws. It defines the technical procedures for maintaining the master membership database, tracking 2-year rolling voting eligibility, validating Code of Ethics compliance, and executing seamless roster handovers between incoming and outgoing Officers.
2. **Governing Scope:** Applies to the Council Secretary, Executive Committee members, Technical/Administrative Committee Secretaries, registration desk staff, and database administrators.

---

# ARTICLE II. ELIGIBILITY TRACKING AND ROSTER ARCHITECTURE

Pursuant to **Bylaws Section 6.01**, voting rights are non-transferable and valid for a rolling period of **two (2) years**. The Council Secretary shall maintain a secure, centralized **Master Eligibility Roster** tracking two distinct pathways to voting eligibility:

### Section 2.01 Verification Pathways
1. **Attendance-Based Eligibility (§ 6.01a):** Automatic 2-year eligibility granted upon verified attendance at any Council-sponsored event (Annual Meeting, Technical Committee session, field tour, or workshop).
2. **Request & Professional Capacity Eligibility (§ 6.01b):** Granted upon submission of a written/electronic eligibility form or same-day registration demonstrating professional involvement in forest health, forestry, pest management, research, natural resource management, fire protection, or education within an organization supporting CFPC's mission.

### Section 2.02 Master Database Schema
The Master Eligibility Roster shall record the following fields for every participant:

| Data Field | Description / Format | Requirement |
| :--- | :--- | :--- |
| **Member ID** | Unique alphanumeric identifier (e.g., `CFPC-2026-0142`) | System Generated |
| **Full Name** | First and Last Name | Mandatory |
| **Primary Organization** | Agency (CAL FIRE, USFS), Tribal Nation, University, Firm, or Independent | Mandatory |
| **Professional Role / Title** | RPF #, PCA #, Pathologist, Forester, Natural Resources Director, etc. | Mandatory |
| **Contact Email** | Primary professional email address | Mandatory |
| **Ethics Agreement Date** | Date of signed/checked Code of Ethics affirmation (**SOP-001**) | Mandatory |
| **Qualifying Activity Date** | Date of last attended meeting, field tour, or submitted eligibility form | Mandatory |
| **Eligibility Expiration Date** | Calculated as **Qualifying Date + 24 Months** | Auto-Calculated |
| **Voting Status** | `ACTIVE` (Eligible) or `EXPIRED` (Non-Voting Participant) | Auto-Calculated |

---

# ARTICLE III. WORKFLOW FOR ROSTER UPDATES AND SAME-DAY REGISTRATION

To ensure fluid participation during meetings without sacrificing regulatory integrity, roster updates shall follow a three-stage workflow: