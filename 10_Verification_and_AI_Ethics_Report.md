# CAPSTONE 6 — DPDP Act and Data Privacy Awareness for Students

**Student Name:** Kamesh  
**Degree & Branch:** B.E. Computer Science and Engineering (CSE)  
**Year of Study:** 3rd Year  
**Register Number:** 410724104044  
**Institution:** Dhanalakshmi College of Engineering  
**Project Question:** How can AI help explain data privacy rights and responsibilities in simple language for students?

---
## Topic 10 & 12: Hallucination Verification Report & Responsible AI Ethics Framework

### Part 1: Testing AI Outputs for Hallucinations, Unsafe Advice & Outdated Law Summaries (Step 10)
Because large language models (LLMs) are trained on historical web snapshots, ungrounded AI prompts frequently confuse the enacted **Digital Personal Data Protection Act, 2023** ([MeitY Gazette PDF](https://www.meity.gov.in/static/uploads/2024/06/2bf1f0e9f04e6fb4f8fef35e82c42aa5.pdf)) with India's older, **withdrawn 2019 Personal Data Protection Bill** or **EU GDPR provisions**.

During our testing across free AI models, we deliberately stress-tested raw AI outputs and caught **5 critical hallucinations / outdated legal errors**, which were corrected using **Google NotebookLM** (grounded in the official 2023 Gazette PDF) and **Perplexity AI**:

| Test # | Raw Unverified AI Output (Hallucination / Outdated Claim) | Error Type | Verified Truth (MeitY DPDP Act 2023 / CERT-In) | How We Fixed It in Our Final Deliverables |
| :-: | :--- | :--- | :--- | :--- |
| **1** | *"Under the DPDP Act 2023, biometric, health, and financial data are classified as 'Sensitive Personal Data' and 'Critical Personal Data' must be stored only on servers inside India."* | **Outdated Law Summary** (Confused with withdrawn 2019 PDP Bill) | The enacted **DPDP Act 2023** removed the "Sensitive/Critical Personal Data" sub-tiers and applies uniform protection to all digital personal data. Cross-border transfers are permitted unless restricted to a notified country (Section 16). | Explicitly clarified in the Explainer and Quiz that the 2023 Act uses a single uniform personal data tier. |
| **2** | *"Indian students have a 'Right to Data Portability' under the DPDP Act to export their social media graph to another app."* | **Cross-Jurisdiction Hallucination** (Confused GDPR Art 20 with DPDP Act) | While **EU GDPR Article 20** grants a Right to Data Portability, **India's DPDP Act 2023 (Sections 11–14)** does **not** include a data portability right; instead, it grants the **Right to Nominate (Section 14)** and **Consent Managers (Section 6(7))**. | Highlighted this exact distinction in the DPDP vs. GDPR Comparison Matrix and Quiz Question 8. |
| **3** | *"If an app misuses your data, you can immediately file a complaint with the Data Protection Board of India on Day 1."* | **Procedural Error / Unsafe Advice** | **Section 13(3) of the DPDP Act 2023** strictly mandates that a Data Principal *shall exhaust the opportunity of redressing her grievance* with the Data Fiduciary or Consent Manager **before** approaching the Data Protection Board. | Added "Contact Grievance Officer First" as Step 18 of our Checklist and Scenario 5. |
| **4** | *"Only companies need to worry about fines under the DPDP Act; students cannot be fined."* | **Unsafe Advice / Omission** | **Section 15 & Schedule Entry 5** of the DPDP Act impose binding duties on Data Principals (no impersonation, no fake documents, no frivolous complaints) backed by a penalty of **up to ₹10,000**. | Featured the ₹10,000 Section 15 student duty warning on the Poster, Presentation, Checklist, and Scenario 6. |
| **5** | *"The DPDP Act 2023 has no rules notified yet and the Data Protection Board does not exist."* | **Stale Training Cut-off Error** | The Government of India notified the **DPDP Rules, 2025** and established the **Data Protection Board of India** in November 2025 ([PIB Press Note](https://www.pib.gov.in/PressNoteDetails.aspx?NoteId=156054&ModuleId=3&reg=3&lang=2)). | Updated all project timelines using live verified search results from PIB and MeitY. |

---

### Part 2: Responsible AI & Ethics Framework for Student Privacy Projects (Step 12)

To ensure that AI is used ethically and safely when educating students about data privacy, this project enforces **Three Non-Negotiable Ethical Guardrails**:

#### Guardrail 1: AI is for Educational Awareness — NEVER Formal Legal Advice
- **Why it matters:** AI models predict probable text patterns; they do not possess legal accountability, cannot evaluate specific contractual liabilities, and may miss nuanced judicial interpretations or sector-specific RBI/SEBI/UGC circulars.
- **Project Policy:** Every deliverable, checklist, presentation slide, and automated weekly email generated in this project carries an explicit disclaimer: *"This content is created for student data-privacy awareness and educational purposes only and does not constitute formal legal advice. For actual data breach remediation or legal disputes, consult a qualified legal professional or official MeitY/CERT-In advisories."*

#### Guardrail 2: Zero Real Personal Data (PII) in Public AI Prompts
- **Why it matters:** Pasting real student registration sheets, phone numbers, email addresses, roll numbers, or Aadhaar details into consumer AI chat interfaces (ChatGPT, Gemini, Claude, etc.) exposes personal data to external servers and potential model-training pipelines—violating the spirit of **Section 8 (Data Security)** of the DPDP Act 2023.
- **Project Policy:**
  - Never upload real club attendance CSVs or student records to any AI tool.
  - Use strictly **synthetic dummy placeholders** (e.g., `student_demo@example.com`, `9999900000`, `[STUDENT_NAME]`) when testing prompts or automation scripts.
  - Note: The author's academic identification (`Kamesh, B.E. CSE 3rd Year, Reg No: 410724104044, Dhanalakshmi College of Engineering`) is attached exclusively as the required project authorship header for academic submission grading.

#### Guardrail 3: Mandatory Source Pinning & Outdated Law Flagging
- **Why it matters:** India's data protection journey spanned multiple draft bills (2018 Justice Srikrishna Draft, 2019 PDP Bill, 2022 Draft Bill) before the **DPDP Act, 2023** was enacted on August 11, 2023, followed by the **DPDP Rules, 2025**. Generic AI prompts often blend provisions across these versions.
- **Project Policy:**
  - Always upload the official primary PDF (MeitY Gazette PDF of Act No. 22 of 2023) into a grounded tool like **NotebookLM** before summarising.
  - Flag and reject any AI summary that fails to cite exact section numbers or references repealed/withdrawn provisions.
