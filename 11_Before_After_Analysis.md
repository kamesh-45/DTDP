# CAPSTONE 6 — DPDP Act and Data Privacy Awareness for Students

**Student Name:** Kamesh  
**Degree & Branch:** B.E. Computer Science and Engineering (CSE)  
**Year of Study:** 3rd Year  
**Register Number:** 410724104044  
**Institution:** Dhanalakshmi College of Engineering  
**Project Question:** How can AI help explain data privacy rights and responsibilities in simple language for students?

---
## Topic 13: Before / After Analysis — Transforming Complex Legal & Raw AI Text into Student-Friendly Guidance

A core goal of **Capstone 6** is answering: *"How can AI help explain data privacy rights and responsibilities in simple language for students?"* This Before/After analysis demonstrates how raw statutory legalese and unverified first-draft AI outputs were systematically transformed into clear, accurate, and actionable student guidance.

---

### Comparison 1: Translating Statutory Legalese into Plain Campus Language (Section 6 Consent)

| Dimension | BEFORE (Raw Statutory Text — DPDP Act 2023, Sec 6(1)) | AFTER (AI-Assisted Plain-Language Student Version) |
| :--- | :--- | :--- |
| **Text** | *"The consent given by the Data Principal shall be free, specific, informed, unconditional and unambiguous with a clear affirmative action, and shall signify an agreement to the processing of her personal data for the specified purpose and be limited to such personal data as is necessary for such specified purpose."* | **"Only Say Yes to What the App Actually Needs!"** When an app asks for your data, it cannot trick you with pre-ticked boxes or bundle unrelated permissions. If a scientific calculator app asks for your **Contacts list**, say **No**—because your friends' phone numbers are not needed to solve math equations! |
| **Reading Level** | Formal legislative drafting (Grade 16+ legal English) | Conversational campus English (Grade 8–10, instant comprehension) |
| **Student Impact** | Students skip reading and click "Accept All" | Students immediately know *which* permission to deny and *why* |

---

### Comparison 2: Correcting Hallucinations in AI Summaries (Before vs. After Verification)

| Dimension | BEFORE (Unverified Generic Prompt Output) | AFTER (Grounded & Verified Output via NotebookLM + MeitY PDF) |
| :--- | :--- | :--- |
| **Prompt Used** | *"Tell me about India's data privacy law for students."* | *"Using the uploaded MeitY DPDP Act 2023 Gazette PDF, explain student rights under Sections 11–14 and duties under Section 15."* |
| **Output Produced** | *"India's PDP Bill categorises student health and financial data as Sensitive Personal Data and gives students the Right to Data Portability and the Right to be Forgotten. Companies must store critical data in India and face fines of 4% of global turnover."* | *"India's enacted **DPDP Act, 2023** applies uniformly to all digital personal data. It grants students 5 core rights: **Access (Sec 11)**, **Correction & Erasure (Sec 12)**, **Withdraw Consent (Sec 6(4))**, **Grievance Redressal (Sec 13)**, and **Nomination (Sec 14)**. It also imposes **Student Duties (Sec 15)** with fines up to **₹10,000** for impersonation or false complaints, while Data Fiduciaries face fines up to **₹250 Crore**."* |
| **Audit Verdict** | **FAILED:** Hallucinated 4% turnover fine (from GDPR), cited withdrawn 2019 PDP Bill tiers, and missed Section 15 student duties. | **PASSED (100% Grounded):** Every section number, right, duty, and rupee penalty matches the official August 11, 2023 Gazette notification. |

---

### Comparison 3: Transforming a Student Club Symposium Google Form

| Element | BEFORE (Typical Unprotected Student Club Form) | AFTER (DPDP Act 2023 Compliant Club Form) |
| :--- | :--- | :--- |
| **Header Notice** | *"Register now for TechFest 2026! Fill all fields below."* (Zero privacy notice) | **DPDP Section 5 Privacy Notice:** *"We collect your Name, Roll No, and College Email solely for TechFest 2026 registration and digital certificates. Your data will be deleted 15 days after the event. To withdraw consent or fix details, email `techfest_privacy@dce.edu.in`."* |
| **Fields Collected** | Name, Mobile, Personal Email, Date of Birth, Home Address, Blood Group, Aadhaar Scan | Name, Roll No, Department, Official College Email, Mobile Number (for WhatsApp event alerts only) |
| **Sponsor Sharing** | Mandatory hidden clause: *"By registering, you agree to receive calls from our coaching sponsors."* | Optional, unchecked box: *"[ ] Optional: I consent to share my email with our event coding partner for internship updates."* |
| **Storage Security** | Google Sheet link set to *"Anyone with the link can view"* in a 300-member WhatsApp group | Restricted Google Sheet accessible only to 4 core faculty/student coordinators; deleted 15 days post-event |
