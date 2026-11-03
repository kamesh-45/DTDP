# CAPSTONE 6 — DPDP Act and Data Privacy Awareness for Students

**Student Name:** Kamesh  
**Degree & Branch:** B.E. Computer Science and Engineering (CSE)  
**Year of Study:** 3rd Year  
**Register Number:** 410724104044  
**Institution:** Dhanalakshmi College of Engineering  
**Project Question:** How can AI help explain data privacy rights and responsibilities in simple language for students?

---
## Topic 11: Documented Prompt Library (Across All 8 Required AI Skills)

This prompt library documents the exact, structured prompts engineered for **Capstone 6**, demonstrating mastery of **8 AI skills** (Research, Prompting, Writing, Legal-Text Summarisation, Verification, Image Generation, Quiz Design, and Responsible AI) while strictly enforcing **zero Personal Identifiable Information (PII)** in prompts.

---

### Prompt 1 — Skill: Legal-Text Summarisation & Research (Used in NotebookLM & Perplexity)
```text
Role: Act as an Indian Cyber Law and Data Privacy Educator.
Context: I have uploaded the official Gazette of India PDF of the Digital Personal Data Protection Act, 2023 (No. 22 of 2023) published by MeitY.
Task: Extract and summarise:
1. All rights granted to a "Data Principal" under Chapter III (Sections 11 to 14) and Section 6(4).
2. All duties imposed on a "Data Principal" under Section 15.
3. The exact financial penalties listed in the Schedule to the Act (Section 33).
Constraints:
- Cite the exact Section and sub-section numbers from the 2023 Act only.
- Do NOT use terms or provisions from the withdrawn 2019 or 2022 draft bills.
- Explain each provision in 2 plain-English sentences suitable for 3rd-year engineering students.
```

---

### Prompt 2 — Skill: Comparative Legal Analysis & Writing (Used in Gemini & Claude)
```text
Role: Plain-Language Technology Law Writer for Indian Undergraduate Students.
Task: Write a structured 1,000-word plain-language explainer comparing India's Digital Personal Data Protection Act, 2023 (and DPDP Rules, 2025) with the European Union's General Data Protection Regulation (GDPR, Regulation (EU) 2016/679).
Target Audience: College students (18–22 years) and student-club volunteers at an engineering college in Chennai.
Required Sections:
1. Core terminology (Data Principal/Fiduciary vs. Data Subject/Controller).
2. Material scope (Digital & digitised data vs. automated & filing systems; uniform personal data vs. GDPR Article 9 special categories).
3. Lawful basis comparison (DPDP Section 6 Consent + Section 7 Legitimate Uses vs. GDPR Article 6 six legal bases including Legitimate Interests).
4. Student & child protection (Under-18 verifiable parental consent & ad-tracking ban under Section 9 vs. GDPR Article 8).
5. Individual rights & India's unique Section 15 student duties (₹10,000 fine).
6. Side-by-side Markdown comparison table.
Constraints: Avoid dense legalese; use everyday campus examples (Google Forms, hackathons, EdTech apps).
```

---

### Prompt 3 — Skill: Scenario Design & Applied Prompting (Used in ChatGPT & Gemini)
```text
Role: Campus Cybersecurity & Privacy Mentor.
Task: Create 6 realistic everyday privacy scenarios faced by Indian college students and student-club volunteers:
1. Mobile utility/calculator app requesting Contacts and Microphone permissions.
2. Hackathon registration form with a pre-checked sponsor marketing consent box.
3. Student-club symposium coordinator sharing a participant Google Sheet via an open WhatsApp link.
4. Student paying semester exam fees over open public café Wi-Fi.
5. EdTech course portal refusing to delete student resume/phone number after course completion.
6. Hostel prank entering a classmate's phone number on spam websites.
Output Format for Each Scenario:
- Everyday Situation
- Privacy Risk
- Unsafe Choice vs. Privacy-Safe Choice
- Exact legal citation from DPDP Act 2023 (Sections 5, 6, 8, 12, 13, 15) or CERT-In Safe Internet Guidelines.
```

---

### Prompt 4 — Skill: Fact Verification & Hallucination Auditing (Used in Perplexity & Claude)
```text
Role: Legal Fact-Checker and AI Hallucination Auditor.
Task: Audit the following AI-generated draft on the DPDP Act 2023 for legal hallucinations, outdated provisions from the withdrawn 2019 Personal Data Protection Bill, or unsafe advice:
[Inserted Draft Text]
Check Specifically For:
1. Did the AI falsely claim the DPDP Act 2023 has a separate "Sensitive Personal Data" or "Critical Personal Data" tier? (Verify against Section 2(t) and Section 3 of the 2023 Act).
2. Did the AI claim the DPDP Act gives a "Right to Data Portability" or "Right to be Forgotten" under those exact names? (Verify against Sections 11–14).
3. Did the AI state that students can complain to the Data Protection Board *before* contacting the Data Fiduciary's Grievance Officer? (Verify against Section 13(3)).
Output a structured Verification Table listing: Claim Tested | AI Error Found | Official Statutory Reality | Corrected Text.
```

---

### Prompt 5 — Skill: Visual Infographic & Poster Generation (Used in Image Generation Tool)
```text
A modern, clean educational infographic poster titled "MY DATA RIGHTS - DPDP ACT 2023" designed for college students. Navy blue, teal, and crisp white color palette. Shows 5 clear icon sections with bold labels: "1. Right to Access Information", "2. Right to Correction & Erasure", "3. Right to Withdraw Consent", "4. Right to Grievance Redressal", "5. Right to Nominate". Clean flat vector graphic design, high contrast typography, university campus awareness poster style.
```

---

### Prompt 6 — Skill: Assessment & Quiz Design (Used in ChatGPT & Gemini)
```text
Role: University Curriculum Designer in Cyber Law & Ethics.
Task: Create a 10-question multiple-choice quiz (4 options A–D per question) testing college students on:
- Key definitions & scope of India's DPDP Act 2023 (Sections 2, 3, 5, 6, 9, 11–15, 33).
- Core differences between DPDP Act 2023 and EU GDPR.
- CERT-In public Wi-Fi and identity protection guidelines.
- Responsible AI ethics (no PII in prompts, AI is not legal advice).
Include a separate Answer Key table explaining *why* the correct option is right with the exact statutory citation.
```

---

### Prompt 7 — Skill: Workflow Automation Scripting (Used in Gemini)
```text
Role: Python Automation Engineer.
Task: Write a standalone Python 3 script (`generate_weekly_privacy_tips.py`) that reads a JSON file of student privacy checklist items (`checklist_source.json`) and automatically generates an 8-week schedule of:
1. Short, engaging WhatsApp/Telegram broadcast messages for a college student club.
2. Formatted email newsletter drafts with subject lines, 2-minute action steps, DPDP Act section citations, and an automated Responsible AI / Non-Legal-Advice disclaimer.
```

---

### Prompt 8 — Skill: Responsible AI & Anonymisation Guardrail Prompt
```text
Role: Data Privacy Anonymisation Filter.
Instruction: Before I ask you to draft our student club's post-event feedback summary, confirm that my input contains ZERO Personal Identifiable Information (no student names, register numbers, phone numbers, email addresses, or payment IDs). If any PII pattern (such as a 10-digit Indian mobile number, 12-digit register/Aadhaar number, or `@` email address) appears in the text, halt immediately and instruct the user to replace it with synthetic tokens (`[STUDENT_01]`). Always append an educational disclaimer stating that AI-generated privacy summaries do not constitute formal legal advice.
```
