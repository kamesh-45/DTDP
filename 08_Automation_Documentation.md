# CAPSTONE 6 — DPDP Act and Data Privacy Awareness for Students

**Student Name:** Kamesh  
**Degree & Branch:** B.E. Computer Science and Engineering (CSE)  
**Year of Study:** 3rd Year  
**Register Number:** 410724104044  
**Institution:** Dhanalakshmi College of Engineering  
**Project Question:** How can AI help explain data privacy rights and responsibilities in simple language for students?

---
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
