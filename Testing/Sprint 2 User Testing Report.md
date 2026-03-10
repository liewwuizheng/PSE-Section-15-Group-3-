## User Testing Report (Sprint 2)

### Testing Overview
* **System Version:** v0.2 - Final Prototype
* **Participants:** 3 user prototypes (outpatient, doctor, administrator)
* **Method:** "Hospital Data Flow" drill, focusing on the end-to-end medication lifecycle, lab tracking, and daily reporting.

---

### Key Findings and Iterations

#### 1. Outpatient Experience (Medication and Lab Tracking)
*   **User Feedback:** Testers highly praised the **Mark as "Taken"** check-in system for its ease of use. The **Prescription Summary** was noted for providing much-needed clarity on dosage instructions.
*   **Data Visibility Issue:** While users could see a "Completed" status for labs, they expressed frustration at not being able to download the actual clinical results.
*   **Measures Taken:** Integrated a **"Download Result"** button within the Lab Status interface, allowing outpatients to access and save their digital laboratory reports directly.

#### 2. Doctor's Schedule (Prescription and Adherence)
*   **User Feedback:** The **Adherence Dashboard** was cited as a critical tool for identifying non-compliant patients. **Digital Prescriptions** significantly reduced manual paperwork time.
*   **Efficiency & Risk Issue:** Doctors found re-entering repeat prescriptions for long-term patients tedious. Furthermore, the dashboard failed to distinguish between a single missed dose and high-risk frequent missing.
*   **Measures Taken:** 
    *   Implemented a **"Repeat Last Prescription"** shortcut for one-click renewals.
    *   Refined analytics with a **"Risk Level" color indicator** (e.g., Red flags for frequent misses) to help doctors prioritize critical follow-ups.


#### 3. Management Dashboard (Reporting and Search)
*   **User Feedback:** Staff confirmed that the **Search Patient Records** feature (via name and phone number) is now highly optimized for speed and accuracy.
*   **Analytical Gap Issue:** The **Daily Reports** tool provided comprehensive raw data but lacked a visual summary for quick executive review by hospital management.
*   **Measures Taken:** Added a **Visual Analytics toggle** that generates instant bar charts for appointment volume and adherence trends.

---

### Evaluation Results: [PASS]
The Smart Care Sync platform has successfully transitioned from a "Stable Foundation" in Sprint 1 to a **fully integrated hospital platform** in Sprint 2. All hospital data flows—from prescription generation to adherence tracking—are verified as logically sound.

**Final Milestone:** The system is now **Feature Complete**. All critical feedback from both sprints has been addressed, and the prototype is ready for **final project handover and deployment**.
