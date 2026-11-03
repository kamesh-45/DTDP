# CAPSTONE 6 — DPDP Act and Data Privacy Awareness for Students

**Student Name:** Kamesh  
**Degree & Branch:** B.E. Computer Science and Engineering (CSE)  
**Year of Study:** 3rd Year  
**Register Number:** 410724104044  
**Institution:** Dhanalakshmi College of Engineering  
**Project Question:** How can AI help explain data privacy rights and responsibilities in simple language for students?

---
## Topic 1, 2, 3 & 4A: Target Audience, Multi-Tool AI Research & Research Summary Report

### 1. Target Audience Selection & Campus Profile
This project specifically targets two primary groups at **Dhanalakshmi College of Engineering** and similar Indian higher-education campuses:
1. **Undergraduate College Students (18–22 years, B.E./B.Tech across all branches):**
   - **Digital Footprint:** Use 15–30 mobile apps daily (UPI payments, EdTech platforms, coding portals, food delivery, social media, and utility apps).
   - **Key Vulnerability:** Habitually click "Accept All" or "Allow" on app permissions and web cookies without reading privacy notices due to dense legal jargon ("consent fatigue").
2. **Student-Club Volunteers & Symposium/Fest Organizers (IEEE, CSI, Coding Clubs, Cultural Committees):**
   - **Digital Footprint:** Collect hundreds of student records via Google Forms, WhatsApp groups, and Excel sheets during hackathons, workshops, and college symposiums (names, roll numbers, phone numbers, email IDs, college ID scans, and UPI transaction screenshots).
   - **Key Vulnerability:** Act as informal data collectors without realizing that sharing open Google Sheet links or repurposing event registration lists for sponsor promotions violates core principles of India's **Digital Personal Data Protection Act, 2023 (DPDP Act)**.

### 2. Multi-Tool AI Research Methodology (5 Free AI Tools Used)
To ensure comprehensive coverage and eliminate single-model bias, five free AI tools were used across different stages of research and creation:

| AI Tool Used | Primary Role in Capstone Project | Key Strength Observed | Verification Needed |
| :--- | :--- | :--- | :--- |
| **Google Gemini** | Statutory synthesis, DPDP vs. GDPR comparison matrix, and Python automation script generation | Fast structured tables, accurate section mapping for DPDP Act 2023 | Cross-checked DPDP Rules 2025 enforcement timelines |
| **Perplexity AI** | Citation-backed discovery of official MeitY gazette notifications, EUR-Lex GDPR articles, and CERT-In advisories | Direct clickable links to `.gov.in` and `.europa.eu` primary sources | Verified exact PDF URLs on MeitY and CERT-In portals |
| **ChatGPT (Free Tier)** | Rewriting complex statutory provisions into plain-language campus scenarios and quiz drafting | Accessible conversational tone for 1st-to-4th year college students | Corrected initial confusion between 2019 draft bill and 2023 Act |
| **Google NotebookLM** | Uploading the official MeitY DPDP Act 2023 Gazette PDF and CERT-In booklet for zero-hallucination Q&A | Strictly grounded answers citing exact sections and illustrations from uploaded PDFs | Ensured external GDPR context was added separately |
| **Claude (Free Tier)** | Ethical review, readability refinement, and before/after legal-to-student translation | Strong nuance in explaining "Legitimate Uses" vs. "Consent" | Verified Indian statutory terminology ("Data Principal" vs "Data Subject") |

### 3. Verified Official & Authoritative Sources Collected
All claims in this project are grounded in three primary regulatory pillars:
1. **Ministry of Electronics and Information Technology (MeitY) — Official Gazette Text:**
   - **The Digital Personal Data Protection Act, 2023 (No. 22 of 2023):** Enacted by Parliament and published in the Gazette of India Extraordinary on August 11, 2023. Official PDF: https://www.meity.gov.in/static/uploads/2024/06/2bf1f0e9f04e6fb4f8fef35e82c42aa5.pdf
   - **MeitY Act & Policy Portal:** https://www.meity.gov.in/content/digital-personal-data-protection-act-2023
   - **DPDP Rules, 2025 & Data Protection Board Notification (PIB / MeitY):** Operationalising consent managers, breach intimation, and the Data Protection Board of India: https://www.pib.gov.in/PressNoteDetails.aspx?NoteId=156054&ModuleId=3&reg=3&lang=2
2. **European Union Official GDPR Portal (EUR-Lex & GDPR-Info):**
   - **Regulation (EU) 2016/679 (General Data Protection Regulation):** Official EUR-Lex Legal Text: https://eur-lex.europa.eu/eli/reg/2016/679/oj/eng
   - **EUR-Lex Official Summary of GDPR:** https://eur-lex.europa.eu/EN/legal-content/summary/general-data-protection-regulation-gdpr.html
   - **GDPR Article-by-Article Reference:** https://gdpr-info.eu/
3. **Indian Computer Emergency Response Team (CERT-In):**
   - **CERT-In Official Portal (MeitY):** https://www.cert-in.org.in/
   - **CERT-In Safe Internet Best Practices Booklet for Digital Nagriks:** https://www.csk.gov.in/documents/CERT-In_Safe_Internet-Best_Practices_Booklet.pdf
   - **CERT-In Information Security Guidelines:** https://www.cert-in.org.in/s2cMainServlet?pageid=GUIDLNVIEW01

### 4. Executive Research Summary
India's **Digital Personal Data Protection Act, 2023 (DPDP Act)** establishes a modern framework governing the processing of digital personal data (data collected online or collected offline and subsequently digitised). Unlike older legalese-heavy regulations, the DPDP Act uses gender-inclusive language ("she/her") and built-in real-life illustrations.

- **Key Terminology:**
  - **Data Principal (Section 2(j)):** The individual to whom the personal data relates (e.g., a college student). For a child (<18 years), it includes parents or lawful guardians.
  - **Data Fiduciary (Section 2(i)):** Any person, company, startup, EdTech platform, or institution that determines the purpose and means of processing personal data.
  - **Data Processor (Section 2(k)):** Any entity that processes data on behalf of a Data Fiduciary (e.g., cloud hosting or form provider).
  - **Consent Manager (Section 6(7)–(9)):** A registered platform enabling a Data Principal to give, manage, review, and withdraw consent through an accessible, transparent, and interoperable platform.
- **Core Legal Architecture:**
  - Personal data may only be processed for a lawful purpose either with the **free, specific, informed, unconditional, and unambiguous consent** of the Data Principal (Section 6) or for **Certain Legitimate Uses** (Section 7, such as voluntary sharing for a specified service, medical emergencies, or statutory functions).
  - Every consent request must be accompanied or preceded by a clear **Notice (Section 5)** itemising the data collected, the specific purpose, and how to withdraw consent or file a grievance—available in English and all 22 languages in the Eighth Schedule of the Constitution.
  - Data Fiduciaries face financial penalties of up to **₹250 Crore** (Schedule to the Act, Section 33) for failing to maintain reasonable security safeguards to prevent personal data breaches (Section 8(5)).


## Topic 4B: Personal Data Privacy Checklist for College Students & Club Volunteers

This 20-point actionable checklist translates the statutory mandates of the **DPDP Act, 2023** ([MeitY Gazette PDF](https://www.meity.gov.in/static/uploads/2024/06/2bf1f0e9f04e6fb4f8fef35e82c42aa5.pdf)) and **CERT-In Cyber Hygiene Guidelines** ([CERT-In Booklet](https://www.csk.gov.in/documents/CERT-In_Safe_Internet-Best_Practices_Booklet.pdf)) into daily habits for students and student-club volunteers at **Dhanalakshmi College of Engineering**.

### Part A: Smartphone & App Permission Hygiene (For All Students)
- [ ] **1. Audit "Calculator" & Utility Apps:** Revoke Contacts, Call Logs, SMS, and Microphone permissions from PDF scanners, calculators, flashlights, and timetable apps (`Settings > Privacy > Permission Manager`).
- [ ] **2. Choose "Allow Only While Using the App":** Never grant "Allow All the Time" location access to food delivery, ride-sharing, or campus event apps.
- [ ] **3. Use Approximate Location When Possible:** Toggle off "Precise Location" for weather, news, and general social apps that do not require street-level GPS coordinates.
- [ ] **4. Reject Bundled Marketing Consent (DPDP Section 6):** When signing up for coding platforms or mock-test portals, uncheck optional checkboxes that share your phone number and email with "partner coaching institutes or sponsors."
- [ ] **5. Read the Section 5 Notice Summary:** Before clicking "I Agree," check three things required under Section 5 of the DPDP Act: *What data is collected? Why is it needed? How can I delete it later?*

### Part B: Identity Documents, Banking & Network Safety (CERT-In Standards)
- [ ] **6. Never Share Unmasked Aadhaar for Informal Events:** Do not upload full Aadhaar card PDFs on unofficial Google Forms for college fests or private hostels; use Virtual ID (VID) or masked Aadhaar where identity proof is genuinely required.
- [ ] **7. Avoid Financial Transactions on Open Public Wi-Fi:** Per [CERT-In Safe Internet Guidelines](https://www.csk.gov.in/documents/CERT-In_Safe_Internet-Best_Practices_Booklet.pdf), never perform UPI/NetBanking transactions or log into primary email accounts on unsecured café, railway, or open hotspot Wi-Fi.
- [ ] **8. Enable Multi-Factor Authentication (MFA):** Turn on authenticator-app MFA on your college email, GitHub, LinkedIn, and primary Google accounts.
- [ ] **9. Check for HTTPS & Domain Spoofing:** Verify the exact domain URL before entering credentials on scholarship, internship, or exam result portals to prevent phishing harvesting.
- [ ] **10. Exercise Your Right to Erasure on Dormant Accounts (DPDP Section 12):** Once an online course, internship application cycle, or semester trial ends, formally request account and personal data deletion rather than simply uninstalling the app.

### Part C: Student-Club Volunteer & Event Organizer Checklist (Fiduciary Responsibility)
- [ ] **11. Apply Data Minimisation on Registration Forms:** Collect only what is strictly necessary for the symposium or hackathon (e.g., Name, College Email, Roll No, Department). Do not ask for Date of Birth, Home Address, or Parent's Income unless legally required.
- [ ] **12. Add a Clear Purpose & Deletion Notice to Google Forms:** Include a 3-line DPDP Notice at the top of every club Google Form stating: *(a) Data collected, (b) Purpose (event coordination & certificates only), and (c) Deletion date (e.g., "All registration data will be permanently deleted 15 days after the symposium").*
- [ ] **13. Lock Down Shared Spreadsheets:** Never set participant Google Sheets to *"Anyone with the link can view/edit."* Restrict access strictly to verified core committee email addresses.
- [ ] **14. Separate Sponsor Opt-In:** If an event sponsor requests participant resumes or contact lists, make sponsor sharing a **separate, non-mandatory opt-in checkbox**—never bundle it as a condition for event entry.
- [ ] **15. Obtain Explicit Media & Photo Consent:** Include a clear opt-out option for students who do not wish to have their close-up photographs posted on public club Instagram/LinkedIn pages.
- [ ] **16. Purge Local CSV Downloads After Certificate Generation:** Delete downloaded participant `.csv` and `.xlsx` files from personal laptops and WhatsApp transfer groups once certificates are dispatched.

### Part D: Exercising Rights & Respecting Duties (DPDP Sections 11–15)
- [ ] **17. Keep a Record of Consent Withdrawals (Section 6(4)):** Screenshot or save confirmation emails when withdrawing consent or unsubscribing from aggressive EdTech telemarketing.
- [ ] **18. Use the Grievance Redressal Channel First (Section 13):** If a platform refuses to delete your data, email their designated Data Protection Officer (DPO) or Grievance Officer before escalating to the Data Protection Board of India.
- [ ] **19. Configure a Digital Nominee (Section 14):** Where supported on major digital and financial accounts, nominate a trusted parent or family member to manage or close your account in case of incapacitation.
- [ ] **20. Obey Section 15 Student Duties (Avoid ₹10,000 Penalty):** Never register friends' phone numbers/emails for pranks, never submit fake identity proofs, and never file frivolous complaints—violating Section 15 duties carries a penalty of up to **₹10,000**.


## Topic 5: Plain-Language Explainer — Comparing India's DPDP Act 2023 and EU GDPR Basics for Students

### Why Should a College Student Care About Data Privacy Laws?
Every day on campus—from scanning a QR code at the canteen and registering for a national coding hackathon to installing a free PDF scanner before semester exams—you leave behind a trail of personal information. Your name, mobile number, roll number, location history, device ID, and resume are valuable digital assets. For years, apps and websites collected this information behind 40-page "Terms and Conditions" that nobody read, often selling student contact lists to coaching centres, loan apps, and data brokers.

To stop the misuse of personal information while still allowing digital innovation, governments enacted comprehensive data protection laws. The two most important frameworks for Indian engineering students to understand are **India's Digital Personal Data Protection Act, 2023 (DPDP Act)** ([MeitY Official Gazette](https://www.meity.gov.in/static/uploads/2024/06/2bf1f0e9f04e6fb4f8fef35e82c42aa5.pdf))—operationalised alongside the **DPDP Rules, 2025** ([PIB Notification](https://www.pib.gov.in/PressNoteDetails.aspx?NoteId=156054&ModuleId=3&reg=3&lang=2))—and the **European Union's General Data Protection Regulation (GDPR, Regulation (EU) 2016/679)** ([EUR-Lex Official Text](https://eur-lex.europa.eu/eli/reg/2016/679/oj/eng)). Whether you are protecting your own smartphone privacy or building a full-stack project as a Computer Science student, understanding how these two laws work—and how they differ—is an essential life and career skill.

---

### 1. The Core Vocabulary: Who is Who?
Both laws regulate the relationship between the individual whose data is collected and the organisation that collects it, though they use slightly different names:
- **You (The Student):** Under India's DPDP Act (Section 2(j)), you are called the **Data Principal**. Under the EU GDPR (Article 4(1)), you are called the **Data Subject**.
- **The App, College, or Company:** Under the DPDP Act (Section 2(i)), the entity that decides *why* and *how* your personal data is processed is called a **Data Fiduciary**—highlighting a relationship of trust. Under the GDPR (Article 4(7)), this entity is called a **Data Controller**.
- **The Cloud or Service Provider:** Both laws use the term **Data Processor** for third-party services (like AWS, Google Forms, or an email dispatch service) that process data strictly on instructions from the Fiduciary/Controller.

---

### 2. What Data is Covered? (Material Scope)
India's DPDP Act (Section 3) is intentionally focused on the digital economy. It applies to **digital personal data**—meaning personal data collected in digital form (such as an online form or mobile app) *or* personal data collected offline on paper (such as a physical symposium registration register) and later **digitised** (typed into Excel or scanned). If a notebook remains purely on paper and is never digitised, the DPDP Act does not apply. Furthermore, unlike earlier Indian rules that separated "personal data" from "sensitive personal data," the DPDP Act applies strict protection across **all** digital personal data uniformly.

By contrast, the EU GDPR (Article 2 and Article 9) covers both automated digital data and structured paper filing systems, and it creates a separate, stricter tier for **"Special Categories of Personal Data"** (such as health records, biometric data, racial or ethnic origin, political opinions, and trade union membership), which generally cannot be processed without explicit consent or narrow statutory exceptions.

---

### 3. How Can Apps Legally Use Your Data? (Consent vs. Legal Bases)
Under India's **DPDP Act (Sections 4, 6, and 7)**, Consent is the primary pillar. A Data Fiduciary can only process your personal data if:
1. **You give Consent (Section 6):** Your consent must be *free, specific, informed, unconditional, and unambiguous* with a clear affirmative action. It is limited strictly to the purpose specified in the **Notice (Section 5)**. For example, if a bank or EdTech app asks for consent to access your phone's contact list just to open a basic student account, that bundled consent is invalid to the extent it is unnecessary for the core service. Better still, the DPDP Act requires notices to be available in **English and all 22 Indian languages** in the Eighth Schedule, and introduces **Consent Managers**—centralised dashboards where you can view and revoke permissions across apps in one place.
2. **Certain Legitimate Uses (Section 7):** In specific, practical situations where asking for separate formal consent is unnecessary—such as when you voluntarily hand over your email ID to receive a pharmacy receipt, during a medical emergency, disaster response, or for government benefits—data may be processed without a separate consent banner.

Under the **EU GDPR (Article 6)**, consent is only **one of six equal legal bases**. Companies in Europe frequently rely on **"Legitimate Interests"** (Article 6(1)(f)) or **"Performance of a Contract"** (Article 6(1)(b)) to process user data without asking for consent, provided they balance their business interest against the user's privacy rights. India deliberately omitted a broad "business legitimate interest" loophole in the DPDP Act 2023 to prevent companies from bypassing user consent.

---

### 4. Your Rights as a Student (Data Principal Rights)
Both laws give you strong legal tools to control your data:
- **Right to Access Information (DPDP Section 11 / GDPR Article 15):** You can ask any app or platform for a summary of all personal data they hold about you, the processing activities performed, and a list of all other Data Fiduciaries or Processors with whom your data has been shared.
- **Right to Correction and Erasure (DPDP Section 12 / GDPR Articles 16 & 17):** You can demand correction of inaccurate or misleading records, completion of incomplete data, and erasure (deletion) of your personal data once the original purpose (like a completed online course or symposium) is no longer served.
- **Right to Withdraw Consent (DPDP Section 6(4) / GDPR Article 7(3)):** Withdrawing your consent must be **just as easy** as giving it. If an app let you sign up with one tap, it cannot force you to mail a physical letter to delete your account.
- **Right to Grievance Redressal (DPDP Section 13 / GDPR Article 77):** Under the DPDP Act, you must first file a complaint with the Data Fiduciary's grievance system, which must respond within the prescribed timeline before you escalate to the **Data Protection Board of India (DPBI)**. Under the GDPR, you can complain directly to an EU Data Protection Authority.
- **Unique Rights in Each Law:** India's DPDP Act grants a unique **Right to Nominate (Section 14)**, allowing you to appoint a family member or nominee to exercise your data rights in the event of death or incapacity. The EU GDPR grants a **Right to Data Portability (Article 20)** (downloading data in machine-readable format to move to a competitor) and a **Right Not to be Subject to Automated Decision-Making/Profiling (Article 22)**.

---

### 5. Unique Indian Feature: Student Duties & Penalties (Section 15)
A distinctive feature of India's DPDP Act—absent in the EU GDPR—is **Section 15: Duties of Data Principals**. In India, rights come paired with civic responsibilities. As a student Data Principal, you must:
1. Not impersonate another person while providing personal data (e.g., entering a classmate's phone number or roll number on an app or prank form).
2. Not suppress material information while providing identity documents.
3. Not register false or frivolous grievances or complaints with a Data Fiduciary or the Data Protection Board.
4. Furnish only verifiably authentic information when exercising your right to correction or erasure.
Violating these duties can result in a personal financial penalty of up to **₹10,000** (Schedule, Entry 5).

---

### 6. Side-by-Side Comparison Matrix: DPDP Act 2023 vs. EU GDPR

| Feature / Dimension | India DPDP Act, 2023 (& Rules 2025) | EU GDPR (Regulation 2016/679) | Practical Takeaway for Students |
| :--- | :--- | :--- | :--- |
| **Individual & Entity Terms** | **Data Principal** & **Data Fiduciary** | **Data Subject** & **Data Controller** | "Fiduciary" emphasises duty of trust toward your data |
| **Material Scope** | Digital personal data + offline data later digitised (Sec 3) | Automated personal data + structured paper files (Art 2) | Club Excel sheets typed from paper registers are covered |
| **Data Categorisation** | Single uniform tier for all personal data | Standard Personal Data vs. Special Categories (Art 9) | Every piece of digital personal data gets full protection |
| **Lawful Grounds** | **Consent** (Sec 6) + **Certain Legitimate Uses** (Sec 7) | **6 Legal Bases** including "Legitimate Interests" (Art 6) | Indian apps cannot hide behind vague "business interest" |
| **Language of Notice** | English + **22 Indian Languages** (Eighth Schedule, Sec 5(3)) | Clear and plain language in relevant EU language (Art 12) | Students can read privacy notices in Tamil, Hindi, etc. |
| **Child / Minor Protection** | Under **18 years**; verifiable parent consent; no tracking/ads (Sec 9) | **13 to 16 years** (varies by EU Member State, Art 8) | High-school & 17-year-old 1st-year students get child shield |
| **Unique Individual Right** | **Right to Nominate** (Sec 14) & **Consent Managers** (Sec 6(7)) | **Data Portability** (Art 20) & **Anti-Profiling** (Art 22) | Indians get unified Consent Manager dashboards |
| **User Duties & Fines** | Explicit **Data Principal Duties** (Sec 15); up to **₹10,000** fine | No monetary fines on individual Data Subjects | Never impersonate peers or file fake complaints |
| **Breach Notification** | Notify **Data Protection Board & every affected user** (Sec 8(6)) + CERT-In (6 hrs) | Notify Regulator within **72 hours**; users only if "high risk" (Art 33–34) | In India, every affected student must be informed of a breach |
| **Maximum Corporate Fine** | Up to **₹250 Crore** per breach of security safeguards (Schedule) | Up to **€20 Million** or **4% of global annual turnover** (Art 83) | Massive deterrence against careless data handling |

*(Word Count: ~1,060 words — Verified against MeitY Gazette Act No. 22 of 2023 and EUR-Lex Regulation 2016/679)*


## Topic 6: Six Everyday Student Privacy Scenarios with Privacy-Safe Choices

These six real-world campus scenarios illustrate how students and student-club volunteers at **Dhanalakshmi College of Engineering** can apply the **DPDP Act, 2023** ([MeitY Gazette PDF](https://www.meity.gov.in/static/uploads/2024/06/2bf1f0e9f04e6fb4f8fef35e82c42aa5.pdf)) and **CERT-In Guidelines** ([CERT-In Booklet](https://www.csk.gov.in/documents/CERT-In_Safe_Internet-Best_Practices_Booklet.pdf)) in everyday decisions.

---

### Scenario 1: The "Free Exam Scanner & Scientific Calculator" App Permissions Trap
- **Everyday Situation:** The night before semester exams, a 3rd-year CSE student downloads a free "Fast PDF Scanner & Scientific Calculator" app from the app store. Upon opening, the app pops up four permission prompts: *Camera, Storage, Read Contacts, and Record Microphone Audio*.
- **The Privacy Risk:** While Camera and Storage are needed to scan notes, **Contacts** and **Microphone** have zero connection to scanning PDFs or calculating equations. Dishonest apps harvest contact lists to spam your classmates or sell student directories to telemarketers.
- **Unsafe Choice:** Tapping "Allow" on all four prompts just to scan the notes quickly.
- **Privacy-Safe Choice (Recommended):** Grant **Camera** permission ("Only while using the app") and **deny Contacts and Microphone** permissions. If the app refuses to work without your Contacts list, uninstall it immediately and use built-in OS scanners (Google Drive scan / iOS Notes).
- **Legal Grounding (DPDP Act 2023):** **Section 6(1) (Purpose Limitation & Specific Consent):** Consent is valid only for the personal data necessary for the specified purpose. Just as the Act's official illustration notes that a bank cannot force contact-list access to open a bank account, a scanner app cannot bundle contact-list harvesting with PDF scanning.

---

### Scenario 2: The National Hackathon & Coaching Sponsor Bundled Consent Form
- **Everyday Situation:** You register online for a free inter-college coding hackathon. At the bottom of the registration page, there is a single pre-checked box that reads: *"I agree to the Hackathon Rules and consent to share my resume, mobile number, and email ID with our 15 EdTech & Study-Abroad Sponsors for promotional calls and WhatsApp updates."*
- **The Privacy Risk:** Pre-checked boxes violate the rule of affirmative consent, and bundling event participation with third-party marketing leads to relentless spam calls and data brokering.
- **Unsafe Choice:** Leaving the box checked and submitting your primary personal mobile number and full resume.
- **Privacy-Safe Choice (Recommended):** Uncheck the sponsor marketing box before submitting. If the form illegally makes marketing consent mandatory, email the organizer's Grievance Contact citing Section 6 of the DPDP Act, or use a secondary email alias and never include your home address or Aadhaar number on a hackathon resume.
- **Legal Grounding (DPDP Act 2023):** **Section 6(1) & Section 5:** Consent must be **free, specific, informed, unconditional, and unambiguous with a clear affirmative action**. Pre-ticked boxes and forced bundling of non-essential marketing with core service delivery are invalid.

---

### Scenario 3: The College Symposium Volunteer & Open Google Sheet Leak
- **Everyday Situation:** As a student-club volunteer organizing a department symposium at Dhanalakshmi College of Engineering, you collect 450 student registrations (Name, Roll No, College, Mobile Number, Email ID, and UPI Transaction ID) in a Google Sheet. To help 12 volunteer coordinators check attendance at the gate, someone changes the Google Sheet sharing setting to *"Anyone with the link can view"* and posts the link in a 300-member WhatsApp group.
- **The Privacy Risk:** Anyone in that WhatsApp group—or anyone who finds the forwarded link—can download all 450 students' personal phone numbers, emails, and payment details, creating a textbook **Personal Data Breach (Section 2(u))**.
- **Unsafe Choice:** Sharing an open public Google Sheet link or dumping raw Excel files into large WhatsApp groups.
- **Privacy-Safe Choice (Recommended):** Set the Google Sheet to **Restricted** and grant View-only access specifically to the 12 verified coordinator email addresses. Create a separate filtered attendance view showing only *Name, College, and Registration ID* (masking phone numbers and UPI IDs), and delete the sheet 15 days after certificates are issued.
- **Legal Grounding (DPDP Act 2023):** **Section 8(5) (Reasonable Security Safeguards) & Section 8(7) (Data Retention/Erasure):** Data Fiduciaries must protect personal data against unauthorised disclosure and erase data once the specified purpose is completed.

---

### Scenario 4: The Free Café Wi-Fi & Urgent Semester Fee Payment
- **Everyday Situation:** While sitting at a coffee shop near Tambaram with low mobile battery, you connect to an open Wi-Fi network named `"Free_HighSpeed_Cafe_WiFi"` (no password required) and open your NetBanking portal to pay your semester exam fee.
- **The Privacy Risk:** Open, unencrypted Wi-Fi networks are vulnerable to **Man-in-the-Middle (MitM) packet sniffing** and **"Evil Twin" rogue hotspots**, allowing attackers on the same network to intercept session tokens, DNS queries, or credentials.
- **Unsafe Choice:** Logging into NetBanking, UPI apps, or primary email accounts over an open public Wi-Fi network.
- **Privacy-Safe Choice (Recommended):** Disconnect from the open café Wi-Fi immediately. Use your own **mobile cellular data (4G/5G)**—or a trusted personal hotspot—whenever performing banking transactions or entering login passwords, and verify the `https://` padlock and official university payment gateway URL.
- **Legal Grounding (CERT-In Guidelines):** **[CERT-In Safe Internet Best Practices Booklet](https://www.csk.gov.in/documents/CERT-In_Safe_Internet-Best_Practices_Booklet.pdf):** Explicitly advises citizens: *"Always use a secured internet connection. Avoid using public Wi-Fi for doing financial transactions."*

---

### Scenario 5: The Completed EdTech Course That Refuses to Delete Your Profile
- **Everyday Situation:** Six months ago, you signed up for a 4-week online placement preparation course, uploading your resume, phone number, and college ID. The course is over, but the company still calls you three times a week to buy a ₹45,000 masterclass and refuses to delete your account when you ask their sales caller.
- **The Privacy Risk:** Indefinite retention of your personal data increases your exposure if the EdTech startup suffers a database breach, and subjects you to unwanted profiling.
- **Unsafe Choice:** Simply blocking individual phone numbers while leaving your resume, college ID, and personal data permanently stored in their database.
- **Privacy-Safe Choice (Recommended):** Send a formal written email to the platform's **Data Protection Officer / Grievance Officer** exercising your **Right to Withdraw Consent (Section 6(4))** and **Right to Erasure (Section 12(1))**, demanding written confirmation that your account, resume, and phone number have been purged. If they fail to respond within the prescribed timeline, escalate to the **Data Protection Board of India (Section 13)**.
- **Legal Grounding (DPDP Act 2023):** **Section 6(6) & Section 12(1):** Once a Data Principal withdraws consent or requests erasure after the specified purpose is fulfilled, the Data Fiduciary must cease processing and erase the personal data (and instruct its Data Processors to do the same) unless retention is mandated by another law.

---

### Scenario 6: The Campus Prank Registration & Impersonation Trap
- **Everyday Situation:** As a joke in the hostel, a student takes a classmate's mobile number and college email ID and signs them up on 20 different loan inquiry websites, property portals, and a fake grievance complaint form.
- **The Privacy Risk:** Apart from harassing a classmate with spam calls, impersonating another individual when submitting personal data or filing a false grievance is a direct statutory violation in India.
- **Unsafe Choice:** Entering a friend's or classmate's personal data without their permission, or submitting fake complaints to test a system.
- **Privacy-Safe Choice (Recommended):** Never input another person's mobile number, email ID, or identity details on any digital form, and use only synthetic dummy data (e.g., `student_demo@example.com`, `9999900000`) when testing software projects or AI prompts.
- **Legal Grounding (DPDP Act 2023):** **Section 15 (Duties of Data Principal) & Schedule Entry 5:** Section 15(b) strictly prohibits impersonating another person while providing personal data, and Section 15(d) prohibits registering false or frivolous grievances. Breach of Section 15 duties attracts a financial penalty of up to **₹10,000**.

---

### Summary Table of the 6 Everyday Scenarios

| # | Campus Scenario | Primary Risk | Privacy-Safe Action | DPDP / CERT-In Citation |
| :-: | :--- | :--- | :--- | :--- |
| **1** | Calculator/Scanner App asks for Contacts & Mic | Contact harvesting & background spying | Deny Contacts/Mic; allow Camera only while in use | DPDP Act Sec 6(1) (Purpose Limitation) |
| **2** | Hackathon Form bundles Sponsor Marketing | Unsolicited telemarketing & resume brokering | Uncheck sponsor opt-in; never share Aadhaar/home address | DPDP Act Sec 5 & Sec 6(1) (Unbundled Consent) |
| **3** | Club Volunteer shares open Google Sheet on WhatsApp | Mass leak of 450 students' phones & UPI IDs | Restrict sheet to coordinator emails; delete 15 days post-event | DPDP Act Sec 8(5) (Security) & Sec 8(7) (Erasure) |
| **4** | Paying Exam Fee on Open Café Wi-Fi | Packet sniffing & Evil Twin credential theft | Switch to 4G/5G cellular data for all banking & logins | CERT-In Safe Internet Best Practices Booklet |
| **5** | EdTech Portal retains data after course ends | Endless spam calls & future breach exposure | Email Grievance Officer invoking Sec 6(4) & Sec 12 Erasure | DPDP Act Sec 6(6), Sec 12(1) & Sec 13 |
| **6** | Hostel prank signing up friend's phone number | Harassment & statutory offence | Never submit others' PII; use dummy data for testing | DPDP Act Sec 15(b)/(d) & Schedule (₹10,000 fine) |


## Topic 7: Poster & Infographic Guide — "My Data Rights Under the DPDP Act, 2023"

*(Note: This folder contains both the visual infographic poster image `My_Data_Rights_Poster.jpg` and the high-resolution print-ready A4 PDF poster `My_Data_Rights_Infographic_Poster.pdf` designed for campus noticeboards at Dhanalakshmi College of Engineering.)*

### Visual Hierarchy & 5 Core Rights Featured on the Poster

#### 1. Right to Access Information (Section 11)
- **What it means in plain language:** You have the right to ask any app, website, or institution what personal data of yours they hold, why they are processing it, and which third parties or processors they have shared it with.
- **Student Action:** Request a data summary from apps you use daily.

#### 2. Right to Correction & Erasure (Section 12)
- **What it means in plain language:** You can demand that a Data Fiduciary correct inaccurate or misleading data, complete incomplete records, update outdated details, and **erase (delete)** your personal data once the original purpose is over.
- **Student Action:** Ask EdTech portals and old event platforms to delete your resume and phone number after the course ends.

#### 3. Right to Withdraw Consent (Section 6(4) & 6(7))
- **What it means in plain language:** If you previously said "Yes" to data collection, you can change your mind and say "No" at any time. The law states that **withdrawing consent must be just as easy as giving consent**, and you can manage permissions through registered **Consent Managers**.
- **Student Action:** Revoke unnecessary app permissions and marketing consents immediately.

#### 4. Right to Grievance Redressal (Section 13)
- **What it means in plain language:** Every Data Fiduciary must provide a clear, accessible grievance redressal mechanism and Data Protection Officer contact. If they do not resolve your complaint within the prescribed period, you can file a digital complaint with the **Data Protection Board of India (DPBI)**.
- **Student Action:** Always email the platform's Grievance Officer first and keep the ticket reference before escalating to the Board.

#### 5. Right to Nominate (Section 14)
- **What it means in plain language:** You have the right to nominate another trusted individual (such as a parent or sibling) who can exercise your data rights (access, correction, or erasure) on your behalf in the event of death or incapacity.
- **Student Action:** Set up account recovery and digital nominees on primary email and financial platforms.

---

### Mandatory Student Reminder Box: Your Duties Under Section 15
While the DPDP Act empowers you with 5 strong rights, **Section 15** imposes strict duties on every Data Principal (with fines up to **₹10,000** for violations):
- **Do NOT impersonate** classmates or friends when filling out online forms.
- **Do NOT submit fake or forged documents** or suppress material identity facts.
- **Do NOT file false or frivolous complaints** with a Data Fiduciary or the Data Protection Board.


## Topic 8B: 10-Question Data Privacy & DPDP Act Quiz with Detailed Answer Key

This 10-question multiple-choice quiz is designed for college students and student-club volunteers at **Dhanalakshmi College of Engineering** to test their practical understanding of **India's DPDP Act, 2023**, **EU GDPR basics**, and **CERT-In cyber hygiene**.

---

### Part 1: Student Assessment Quiz (10 Questions — 10 Marks)

**Q1. Under India's Digital Personal Data Protection (DPDP) Act, 2023, what is the legal term for the individual (such as a college student) to whom the personal data relates?**  
A) Data Controller  
B) Data Principal  
C) Data Fiduciary  
D) Data Custodian  

**Q2. A student-club volunteer collects participant names and mobile numbers in a physical paper notebook at the college gate and later types them into a Google Sheet to email certificates. Does the DPDP Act, 2023 apply to that Google Sheet?**  
A) No, because the data was originally written on paper offline.  
B) Yes, because Section 3 of the DPDP Act covers personal data collected offline if it is subsequently digitised.  
C) Only if the student club is registered as a private limited company.  
D) Only if the students are citizens of the European Union.  

**Q3. Under Section 5(3) of the DPDP Act, 2023, a Data Fiduciary must give the Data Principal the option to access the privacy consent notice in English or in any language specified in which part of the Indian Constitution?**  
A) Seventh Schedule (Union and State Lists)  
B) Eighth Schedule (22 Recognised Indian Languages, including Tamil, Hindi, Telugu, etc.)  
C) Ninth Schedule  
D) Preamble  

**Q4. You download a free "Engineering Unit Converter" app that refuses to open unless you grant it permission to read your Contacts and Call Logs. How does Section 6 of the DPDP Act treat this consent request?**  
A) It is completely legal because the app is free of cost.  
B) It violates the requirement of specific,necessary, and unbundled consent, as Contacts and Call Logs are not required to convert engineering units.  
C) It is valid as long as the requirement is buried on page 35 of the Terms of Service.  
D) The DPDP Act does not apply to mobile smartphone apps.  

**Q5. Under Section 9 of the DPDP Act, 2023, what is the age threshold below which an individual is legally classified as a "Child" requiring verifiable parental consent and protection from behavioural tracking or targeted advertising?**  
A) Below 13 years  
B) Below 16 years  
C) Below 18 years  
D) Below 21 years  

**Q6. How does the EU GDPR (Article 6) differ from India's DPDP Act, 2023 regarding the legal grounds for processing personal data?**  
A) GDPR only allows processing with explicit user consent, whereas the DPDP Act has no consent rule.  
B) GDPR includes six legal bases—including a broad "Legitimate Interests" ground for businesses—whereas India's DPDP Act relies on Consent (Section 6) and specific statutory "Certain Legitimate Uses" (Section 7).  
C) GDPR only applies to government agencies, not private companies.  
D) GDPR imposes no financial penalties for data breaches.  

**Q7. If an EdTech platform refuses to delete your personal data after your course ends and you wish to seek legal redress under Section 13 of the DPDP Act, 2023, what is the mandatory first step before approaching the Data Protection Board of India?**  
A) File a Public Interest Litigation (PIL) directly in the Supreme Court.  
B) Exhaust the opportunity of redressing your grievance directly with the Data Fiduciary's Grievance Officer / Data Protection Officer.  
C) Post about the company on social media and wait 90 days.  
D) Report the company to the European Data Protection Board.  

**Q8. Which section of the DPDP Act, 2023 allows a student to appoint a parent or family member to exercise their data privacy rights in the event of death or incapacity?**  
A) Section 4 — Right to Data Portability  
B) Section 11 — Right to Information  
C) Section 14 — Right to Nominate  
D) Section 22 — Right Against Automated Profiling  

**Q9. As a hostel prank, a student enters a classmate's mobile number and roll number on multiple spam loan portals and files a fake privacy grievance in their name. Under Section 15 and the Schedule to the DPDP Act, 2023, what is the maximum penalty that can be imposed on the student for breaching Data Principal duties?**  
A) No penalty, because only companies can be fined under the DPDP Act.  
B) Up to ₹10,000 financial penalty.  
C) Up to ₹250 Crore financial penalty.  
D) Automatic suspension of university degree by MeitY.  

**Q10. When using a generative AI tool (such as ChatGPT, Gemini, or Claude) to draft a student-club event report or check a privacy policy, which of the following is a mandatory Responsible AI & Ethics rule?**  
A) Paste the entire Excel sheet of 500 students' names, phone numbers, and Aadhaar numbers into the public AI prompt to format it faster.  
B) Treat the AI's summary as binding legal advice without checking the official MeitY Gazette PDF.  
C) Never input real personal data (PII) into public AI prompts, verify all legal citations against official sources (as AI can hallucinate or cite withdrawn 2019/2022 bills), and state clearly that AI output is not legal advice.  
D) Assume any AI model always knows yesterday's government notifications without web verification.  

---

### Part 2: Official Answer Key & Statutory Explanations

| Q# | Correct Option | Detailed Statutory & Practical Explanation |
| :-: | :-: | :--- |
| **Q1** | **B** | **Data Principal (Section 2(j) of DPDP Act, 2023):** India's Act uses "Data Principal" for the individual and "Data Fiduciary" (Section 2(i)) for the entity determining the purpose and means of processing. ("Data Subject" and "Data Controller" are EU GDPR terms). |
| **Q2** | **B** | **Digitised Offline Data (Section 3(a)(ii) of DPDP Act, 2023):** The Act applies to digital personal data collected in digital form *and* personal data collected in non-digital form and **subsequently digitised** (such as typing a paper register into a Google Sheet). |
| **Q3** | **B** | **Eighth Schedule Languages (Section 5(3) of DPDP Act, 2023):** To ensure accessibility across India, Data Fiduciaries must offer the consent notice in English or any of the **22 languages specified in the Eighth Schedule** to the Constitution. |
| **Q4** | **B** | **Specific & Unbundled Consent (Section 6(1) of DPDP Act, 2023):** Consent must be free, specific, informed, and limited to such personal data as is necessary for the specified purpose. Bundling unnecessary permissions (Contacts/Call Logs for a unit converter) is invalid. |
| **Q5** | **C** | **Child Definition (Section 2(f) & Section 9 of DPDP Act, 2023):** A "child" means an individual who has not completed the age of **18 years**. Processing a child's data requires verifiable parental consent and strictly prohibits tracking, behavioural monitoring, or targeted advertising directed at children. |
| **Q6** | **B** | **Consent vs. Six Legal Bases (DPDP Sections 6–7 vs. GDPR Article 6):** The EU GDPR provides 6 lawful bases including a flexible "Legitimate Interests" ground for controllers. India's DPDP Act intentionally omitted "legitimate business interest" and restricts processing to Consent (Sec 6) or enumerated "Certain Legitimate Uses" (Sec 7). |
| **Q7** | **B** | **Exhausting Fiduciary Grievance Redressal (Section 13(3) of DPDP Act, 2023):** A Data Principal *shall exhaust the opportunity of redressing her grievance* under the Data Fiduciary's or Consent Manager's grievance mechanism before approaching the Data Protection Board of India. |
| **Q8** | **C** | **Right to Nominate (Section 14 of DPDP Act, 2023):** Section 14 grants every Data Principal the right to nominate one or more individuals to exercise their rights under the Act in the event of death or incapacity. |
| **Q9** | **B** | **Duties of Data Principal (Section 15 & Schedule Entry 5 of DPDP Act, 2023):** Section 15 prohibits impersonation and filing false/frivolous complaints. Under Entry 5 of the Schedule, breach of Section 15 duties by a Data Principal carries a penalty of **up to ₹10,000** (whereas ₹250 Crore is the maximum penalty for Data Fiduciaries breaching security safeguards). |
| **Q10** | **C** | **Responsible AI Ethics:** Public AI prompts must never contain real Personal Identifiable Information (PII), AI legal summaries must be verified against official gazette texts to catch hallucinations or outdated 2019/2022 draft bills, and AI outputs are educational awareness—never formal legal advice. |


## Topic 9: Automation Workflow — Weekly Privacy Tip Drafts from the Checklist

### 1. Overview of the Automated Step
To satisfy **Step 9 ("Automate one step, e.g. weekly privacy tip drafts from the checklist")**, we built a deterministic Python automation pipeline (`generate_weekly_privacy_tips.py`) paired with a structured JSON checklist repository (`checklist_source.json`) and a zero-cost **Make.com / Google Apps Script** schedule blueprint.

Instead of a student-club volunteer manually writing privacy reminders every Monday morning, the automation pipeline transforms each checklist rule into:
1. **A formatted WhatsApp / Telegram Student-Club Broadcast message** (with a 2-minute action step and exact DPDP Act 2023 section citation).
2. **A ready-to-send Campus Email Newsletter draft** with a pre-attached "Not Legal Advice" ethics disclaimer.

### 2. Three-Stage Automation Architecture
1. **Input Layer (`checklist_source.json`):** Stores verified checklist items mapped to `week`, `category`, `checklist_item`, `dpdp_section`, `action_step`, and `club_tip`.
2. **Transformation Engine (`generate_weekly_privacy_tips.py`):** Iterates across the checklist items, calculates weekly publication dates, injects mandatory statutory citations and disclaimers, and writes the formatted 8-week campaign output (`Generated_8_Week_Privacy_Tips_Output.md`).
3. **Zero-Cost Cloud Trigger (Make.com / Google Sheets Cron Blueprint):**
   - **Trigger:** Every Monday at 08:30 AM IST, Make.com (Free Tier) reads the next row of the Checklist Google Sheet matching the current week number.
   - **Filter / Guardrail:** Verifies that the `verified_by_human` column equals `TRUE` (preventing unverified AI text from auto-publishing).
   - **Action:** Creates a Gmail Draft for the CSE Student Club Coordinator at Dhanalakshmi College of Engineering for 1-click review and dispatch.


# Automated 8-Week Campus Privacy Tip Digests (Generated Output)

**Generated By:** `generate_weekly_privacy_tips.py` (Automated Workflow Step 9)  
**Student:** Kamesh | B.E. CSE, 3rd Year | Reg No: 410724104044  
**Institution:** Dhanalakshmi College of Engineering  

> **Disclaimer:** Automated educational awareness drafts based on the Digital Personal Data Protection Act, 2023 (MeitY) and CERT-In guidelines. This is not formal legal advice.

---

## Week 1 Digest (02 November 2026) — App Permissions

- **Checklist Source Item:** Audit Calculator & Utility Apps for unnecessary Contacts/Mic access
- **Legal / Regulatory Anchor:** Section 6(1) — Purpose Limitation & Specific Consent

### 1. Ready-to-Post WhatsApp / Telegram Club Broadcast
> **[DCE Cyber & Privacy Club — Weekly Tip #1]**  
> **Topic:** App Permissions  
> Before installing any exam-prep or scanner app this week, deny Contacts and Microphone access. Under Section 6(1) of the DPDP Act 2023, apps can only request data strictly necessary for their core function!  
> **2-Minute Action:** Open Settings > Privacy > Permission Manager > Contacts and revoke access for all non-communication apps.  
> *Law Reference: Section 6(1) — Purpose Limitation & Specific Consent | Stay safe, DCEians!*

### 2. Ready-to-Send Student Club Email Draft
- **Subject:** [DCE Privacy Tip #1] Audit Calculator & Utility Apps for unnecessary Contacts/Mic access
- **Body:** Dear Students of Dhanalakshmi College of Engineering, this week's 2-minute privacy check focuses on **App Permissions**. Before installing any exam-prep or scanner app this week, deny Contacts and Microphone access. Under Section 6(1) of the DPDP Act 2023, apps can only request data strictly necessary for their core function! **Your Action Step:** Open Settings > Privacy > Permission Manager > Contacts and revoke access for all non-communication apps. *(Grounded in Section 6(1) — Purpose Limitation & Specific Consent)*.

---

## Week 2 Digest (09 November 2026) — Network & Payment Security

- **Checklist Source Item:** Avoid UPI/NetBanking on open public Wi-Fi networks
- **Legal / Regulatory Anchor:** CERT-In Safe Internet Best Practices Guidelines

### 1. Ready-to-Post WhatsApp / Telegram Club Broadcast
> **[DCE Cyber & Privacy Club — Weekly Tip #2]**  
> **Topic:** Network & Payment Security  
> Sitting at a café near campus? Never pay semester fees or enter banking passwords over open public Wi-Fi. CERT-In warns that open hotspots expose your traffic to packet sniffing!  
> **2-Minute Action:** Turn off 'Auto-Connect to Open Wi-Fi' on your smartphone and switch to 4G/5G cellular data before paying fees.  
> *Law Reference: CERT-In Safe Internet Best Practices Guidelines | Stay safe, DCEians!*

### 2. Ready-to-Send Student Club Email Draft
- **Subject:** [DCE Privacy Tip #2] Avoid UPI/NetBanking on open public Wi-Fi networks
- **Body:** Dear Students of Dhanalakshmi College of Engineering, this week's 2-minute privacy check focuses on **Network & Payment Security**. Sitting at a café near campus? Never pay semester fees or enter banking passwords over open public Wi-Fi. CERT-In warns that open hotspots expose your traffic to packet sniffing! **Your Action Step:** Turn off 'Auto-Connect to Open Wi-Fi' on your smartphone and switch to 4G/5G cellular data before paying fees. *(Grounded in CERT-In Safe Internet Best Practices Guidelines)*.

---

## Week 3 Digest (16 November 2026) — Symposium & Club Forms

- **Checklist Source Item:** Apply Data Minimisation and Purpose Notices on Google Forms
- **Legal / Regulatory Anchor:** Section 5 (Notice) & Section 8(7) (Erasure upon Purpose Completion)

### 1. Ready-to-Post WhatsApp / Telegram Club Broadcast
> **[DCE Cyber & Privacy Club — Weekly Tip #3]**  
> **Topic:** Symposium & Club Forms  
> Organizing a department workshop at Dhanalakshmi College of Engineering? Only collect Name, Roll No, and College Email—never ask for Aadhaar scans, and lock your Google Sheet permissions!  
> **2-Minute Action:** Add a 3-line Privacy Notice at the top of every club registration form and schedule data deletion 15 days post-event.  
> *Law Reference: Section 5 (Notice) & Section 8(7) (Erasure upon Purpose Completion) | Stay safe, DCEians!*

### 2. Ready-to-Send Student Club Email Draft
- **Subject:** [DCE Privacy Tip #3] Apply Data Minimisation and Purpose Notices on Google Forms
- **Body:** Dear Students of Dhanalakshmi College of Engineering, this week's 2-minute privacy check focuses on **Symposium & Club Forms**. Organizing a department workshop at Dhanalakshmi College of Engineering? Only collect Name, Roll No, and College Email—never ask for Aadhaar scans, and lock your Google Sheet permissions! **Your Action Step:** Add a 3-line Privacy Notice at the top of every club registration form and schedule data deletion 15 days post-event. *(Grounded in Section 5 (Notice) & Section 8(7) (Erasure upon Purpose Completion))*.

---

## Week 4 Digest (23 November 2026) — Identity Protection

- **Checklist Source Item:** Use Masked Aadhaar or Virtual ID (VID) instead of full Aadhaar photocopies
- **Legal / Regulatory Anchor:** CERT-In Identity Protection & UIDAI Guidelines

### 1. Ready-to-Post WhatsApp / Telegram Club Broadcast
> **[DCE Cyber & Privacy Club — Weekly Tip #4]**  
> **Topic:** Identity Protection  
> Stop storing unmasked Aadhaar PDFs in your WhatsApp media folder! Download a Masked Aadhaar showing only the last 4 digits whenever identity verification is needed.  
> **2-Minute Action:** Download a Masked Aadhaar (showing only the last 4 digits) from myaadhaar.uidai.gov.in for hostel or travel verification.  
> *Law Reference: CERT-In Identity Protection & UIDAI Guidelines | Stay safe, DCEians!*

### 2. Ready-to-Send Student Club Email Draft
- **Subject:** [DCE Privacy Tip #4] Use Masked Aadhaar or Virtual ID (VID) instead of full Aadhaar photocopies
- **Body:** Dear Students of Dhanalakshmi College of Engineering, this week's 2-minute privacy check focuses on **Identity Protection**. Stop storing unmasked Aadhaar PDFs in your WhatsApp media folder! Download a Masked Aadhaar showing only the last 4 digits whenever identity verification is needed. **Your Action Step:** Download a Masked Aadhaar (showing only the last 4 digits) from myaadhaar.uidai.gov.in for hostel or travel verification. *(Grounded in CERT-In Identity Protection & UIDAI Guidelines)*.

---

## Week 5 Digest (30 November 2026) — Right to Erasure

- **Checklist Source Item:** Delete dormant EdTech and placement portal accounts
- **Legal / Regulatory Anchor:** Section 12(1) (Right to Erasure) & Section 6(4) (Withdrawal of Consent)

### 1. Ready-to-Post WhatsApp / Telegram Club Broadcast
> **[DCE Cyber & Privacy Club — Weekly Tip #5]**  
> **Topic:** Right to Erasure  
> Uninstalling an app does NOT delete your data from its servers! Exercise your Right to Erasure under Section 12 of the DPDP Act 2023 by requesting account deletion once a course ends.  
> **2-Minute Action:** Email the Grievance Officer of 2 old platforms you no longer use and request complete account and resume erasure.  
> *Law Reference: Section 12(1) (Right to Erasure) & Section 6(4) (Withdrawal of Consent) | Stay safe, DCEians!*

### 2. Ready-to-Send Student Club Email Draft
- **Subject:** [DCE Privacy Tip #5] Delete dormant EdTech and placement portal accounts
- **Body:** Dear Students of Dhanalakshmi College of Engineering, this week's 2-minute privacy check focuses on **Right to Erasure**. Uninstalling an app does NOT delete your data from its servers! Exercise your Right to Erasure under Section 12 of the DPDP Act 2023 by requesting account deletion once a course ends. **Your Action Step:** Email the Grievance Officer of 2 old platforms you no longer use and request complete account and resume erasure. *(Grounded in Section 12(1) (Right to Erasure) & Section 6(4) (Withdrawal of Consent))*.

---

## Week 6 Digest (07 December 2026) — Hackathon & Sponsor Consent

- **Checklist Source Item:** Uncheck bundled third-party sponsor marketing checkboxes
- **Legal / Regulatory Anchor:** Section 6(1) — Free, Specific, Informed & Unconditional Consent

### 1. Ready-to-Post WhatsApp / Telegram Club Broadcast
> **[DCE Cyber & Privacy Club — Weekly Tip #6]**  
> **Topic:** Hackathon & Sponsor Consent  
> Signing up for a weekend hackathon? Read the checkboxes carefully! Uncheck third-party sponsor marketing consent so your phone number and resume aren't sold to telemarketers.  
> **2-Minute Action:** Uncheck optional 'Share my details with sponsors/partners' boxes when registering for coding contests.  
> *Law Reference: Section 6(1) — Free, Specific, Informed & Unconditional Consent | Stay safe, DCEians!*

### 2. Ready-to-Send Student Club Email Draft
- **Subject:** [DCE Privacy Tip #6] Uncheck bundled third-party sponsor marketing checkboxes
- **Body:** Dear Students of Dhanalakshmi College of Engineering, this week's 2-minute privacy check focuses on **Hackathon & Sponsor Consent**. Signing up for a weekend hackathon? Read the checkboxes carefully! Uncheck third-party sponsor marketing consent so your phone number and resume aren't sold to telemarketers. **Your Action Step:** Uncheck optional 'Share my details with sponsors/partners' boxes when registering for coding contests. *(Grounded in Section 6(1) — Free, Specific, Informed & Unconditional Consent)*.

---

## Week 7 Digest (14 December 2026) — Student Duties

- **Checklist Source Item:** Never impersonate classmates or file fake complaints
- **Legal / Regulatory Anchor:** Section 15 (Duties of Data Principal) & Schedule Entry 5 (Up to ₹10,000 Fine)

### 1. Ready-to-Post WhatsApp / Telegram Club Broadcast
> **[DCE Cyber & Privacy Club — Weekly Tip #7]**  
> **Topic:** Student Duties  
> Did you know the DPDP Act 2023 also fines individuals? Under Section 15, entering a friend's mobile number on spam sites as a prank or filing a fake complaint can cost you up to ₹10,000!  
> **2-Minute Action:** Use only synthetic dummy emails (demo@example.com) when testing college software projects or AI prompts.  
> *Law Reference: Section 15 (Duties of Data Principal) & Schedule Entry 5 (Up to ₹10,000 Fine) | Stay safe, DCEians!*

### 2. Ready-to-Send Student Club Email Draft
- **Subject:** [DCE Privacy Tip #7] Never impersonate classmates or file fake complaints
- **Body:** Dear Students of Dhanalakshmi College of Engineering, this week's 2-minute privacy check focuses on **Student Duties**. Did you know the DPDP Act 2023 also fines individuals? Under Section 15, entering a friend's mobile number on spam sites as a prank or filing a fake complaint can cost you up to ₹10,000! **Your Action Step:** Use only synthetic dummy emails (demo@example.com) when testing college software projects or AI prompts. *(Grounded in Section 15 (Duties of Data Principal) & Schedule Entry 5 (Up to ₹10,000 Fine))*.

---

## Week 8 Digest (21 December 2026) — Responsible AI Hygiene

- **Checklist Source Item:** Zero Personal Identifiable Information (PII) in AI Prompts
- **Legal / Regulatory Anchor:** AI Ethics & Data Minimisation Policy

### 1. Ready-to-Post WhatsApp / Telegram Club Broadcast
> **[DCE Cyber & Privacy Club — Weekly Tip #8]**  
> **Topic:** Responsible AI Hygiene  
> Using AI to format a club attendance list or draft an email? Strip out all student names, register numbers, and phone numbers first—never feed real campus PII into public AI prompts!  
> **2-Minute Action:** Anonymise all names, roll numbers, and phone numbers before pasting club data into ChatGPT, Gemini, or Claude.  
> *Law Reference: AI Ethics & Data Minimisation Policy | Stay safe, DCEians!*

### 2. Ready-to-Send Student Club Email Draft
- **Subject:** [DCE Privacy Tip #8] Zero Personal Identifiable Information (PII) in AI Prompts
- **Body:** Dear Students of Dhanalakshmi College of Engineering, this week's 2-minute privacy check focuses on **Responsible AI Hygiene**. Using AI to format a club attendance list or draft an email? Strip out all student names, register numbers, and phone numbers first—never feed real campus PII into public AI prompts! **Your Action Step:** Anonymise all names, roll numbers, and phone numbers before pasting club data into ChatGPT, Gemini, or Claude. *(Grounded in AI Ethics & Data Minimisation Policy)*.

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


## Topic 14: Final Demo Guide & Complete Capstone 6 Submission Inventory

### 1. Project Submission Verification Checklist (100 Marks Weightage)
Every requirement specified in **Capstone 6 — DPDP Act and Data Privacy Awareness for Students** has been created, verified against official primary sources, organised into its own dedicated topic folder, and combined into the master submission package `Capstone_6_DPDP_Act_Kamesh_410724104044`:

| Folder # | Topic Folder Name | Capstone 6 Requirement Covered | Files Included Inside Folder |
| :-: | :--- | :--- | :--- |
| **01** | `01_Target_Audience_and_Research_Report` | Steps 1, 2, 3, 4A (Audience, 5 AI Tools, Verified Sources, Research Summary) | `01_Research_Report.md`, `01_Research_Report.docx` |
| **02** | `02_Personal_Data_Privacy_Checklist` | Step 4B (20-Point Student & Club Volunteer Privacy Checklist) | `02_Personal_Data_Privacy_Checklist.md`, `02_Personal_Data_Privacy_Checklist.docx` |
| **03** | `03_Plain_Language_Explainer_DPDP_vs_GDPR` | Step 5 (~1,060-Word Plain-Language Explainer: DPDP Act vs. GDPR) | `03_Explainer_DPDP_vs_GDPR.md`, `03_Explainer_DPDP_vs_GDPR.docx` |
| **04** | `04_Everyday_Privacy_Scenarios` | Step 6 (6 Campus Privacy Scenarios with Safe Choices & Citations) | `04_Six_Everyday_Privacy_Scenarios.md`, `04_Six_Everyday_Privacy_Scenarios.docx` |
| **05** | `05_Infographic_My_Data_Rights` | Step 7 ("My Data Rights" Visual Poster & Printable A4 PDF Infographic) | `My_Data_Rights_Poster.jpg`, `My_Data_Rights_Infographic_Poster.pdf`, `05_Infographic_Guide.md`, `05_Infographic_Guide.docx` |
| **06** | `06_Quiz_and_Answer_Key` | Step 8B (10-Question Multiple-Choice Quiz + Detailed Answer Key) | `06_Quiz_and_Answer_Key.md`, `06_Quiz_and_Answer_Key.docx` |
| **07** | `07_Presentation_6_Slides` | Step 8A (6-Slide Presentation Deck in PPTX & PDF formats) | `DPDP_Act_Privacy_Presentation_6_Slides.pptx`, `DPDP_Act_Privacy_Presentation_6_Slides.pdf`, `07_Presentation_Notes.md` |
| **08** | `08_Automation_Weekly_Privacy_Tips` | Step 9 (Automated Weekly Privacy Tip Generator Script + 8-Week Output) | `generate_weekly_privacy_tips.py`, `checklist_source.json`, `Generated_8_Week_Privacy_Tips_Output.md`, `08_Automation_Documentation.md`, `08_Automation_Documentation.docx` |
| **09** | `09_Prompt_Library` | Step 11 (Documented Prompt Library across 8 Required AI Skills) | `09_Prompt_Library.md`, `09_Prompt_Library.docx` |
| **10** | `10_Verification_and_AI_Ethics_Report` | Steps 10 & 12 (Hallucination Testing Log + AI Ethics Framework) | `10_Verification_and_AI_Ethics_Report.md`, `10_Verification_and_AI_Ethics_Report.docx` |
| **11** | `11_Before_After_Analysis` | Final Submission Item 11 (Before/After Legal-to-Student & Verification Analysis) | `11_Before_After_Analysis.md`, `11_Before_After_Analysis.docx` |
| **12** | `12_Final_Demo_and_Master_Submission` | Final Demo Script + Complete Consolidated Master Report (PDF & DOCX) | `Capstone_6_Master_Report_Kamesh_410724104044.pdf`, `Capstone_6_Master_Report_Kamesh_410724104044.docx`, `12_Final_Demo_Guide.md` |

---

### 2. 5-Minute Final Demo Viva / Presentation Script for Kamesh

- **Minute 1 — Introduction & Problem Statement (Slide 1):**
  > *"Good morning faculty and peers. I am Kamesh (Reg No: 410724104044, 3rd Year B.E. CSE, Dhanalakshmi College of Engineering). My Capstone 6 project addresses how AI can translate complex data privacy laws—specifically India's Digital Personal Data Protection (DPDP) Act, 2023 and the EU GDPR—into simple, actionable habits for college students and student-club volunteers."*
- **Minute 2 — Student Rights & Duties under the DPDP Act 2023 (Slide 2 & Poster):**
  > *"Using official MeitY Gazette texts verified via NotebookLM and Perplexity, I designed the 'My Data Rights' campus infographic highlighting 5 core rights: Access (Sec 11), Correction & Erasure (Sec 12), Consent Withdrawal (Sec 6(4)), Grievance Redressal (Sec 13), and Nomination (Sec 14). Crucially, I also highlighted Section 15 Student Duties—warning students that impersonating classmates on forms or filing fake complaints carries a fine of up to ₹10,000."*
- **Minute 3 — Global Comparison & 6 Campus Scenarios (Slides 3 & 4):**
  > *"In my 1,000-word plain-language explainer, I compared the DPDP Act with the EU GDPR—showing how India avoids GDPR's broad 'business legitimate interest' loophole and protects everyone under 18 from targeted ad tracking. I then translated the law into 6 everyday campus scenarios, including denying Contacts access to calculator apps, unchecking hackathon sponsor marketing boxes, and locking down symposium Google Sheets."*
- **Minute 4 — Live Automation Demo (`generate_weekly_privacy_tips.py`) (Slide 5):**
  > *"To automate ongoing awareness for our college clubs, I built a Python automation script (`generate_weekly_privacy_tips.py`) that reads our 20-point privacy checklist from JSON and automatically generates 8 weeks of ready-to-post WhatsApp broadcasts and email newsletters complete with DPDP Act citations."*
- **Minute 5 — AI Verification, Ethics & Conclusion (Slides 5 & 6):**
  > *"Finally, I audited raw AI outputs and caught 5 major hallucinations—such as AI models confusing the withdrawn 2019 Bill's 'Sensitive Data' tiers with the enacted 2023 Act. Throughout the project, I enforced three AI Ethics rules: AI is educational awareness (not legal advice), zero student PII was entered into prompts, and every claim is grounded in MeitY, EUR-Lex, and CERT-In sources. Thank you!"*
