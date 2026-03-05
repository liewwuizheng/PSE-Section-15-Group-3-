## User Testing Report (Sprint 1)

### Testing Overview
* **System Version:** v0.1 - Prototype
* **Participants:** 3 user prototypes (outpatient, doctor, administrator)
* **Method:** "Normal Process" drill, focusing on the end-to-end appointment lifecycle.

### Key Findings and Iterations

#### 1. Outpatient Experience (Appointment Process)
* **User Feedback:** Users are very satisfied with the linear, step-by-step appointment process.
* **Safety Net Issue:** Testers were uneasy because clicking the "Cancel" button immediately deleted data without warning.
* **Measures Taken:**
**Implemented a **forced confirmation dialog** for all operations (cancellation/deletion) that could cause data loss.**
**Added a **success message** to provide immediate feedback after appointment confirmation.**

#### 2. Doctor's Schedule (Readability)
* **User Feedback:** Doctors appreciate the clean daily view but find the interface slightly "labile" on small screens.
* **Small Font Issue:** The appointment module is too crowded, and the font is too small, making it difficult to quickly browse during patient breaks.
* **Measures Taken:**
**Optimized **layout hierarchy**: Increased font size and color contrast to improve accessibility.

#### 3. Management Dashboard (Data Management)
* **User Feedback:** The table layout is praised for its simplicity and efficiency.
* **Status Blind Spot Issue:** The uniform black/italic font used for "Approved," "Rejected," and "Pending" statuses leads to visual fatigue and errors.
* **Measures Taken:**
* Implemented **semantic color coding**: 🟢 Green (Approved), 🔴 Red (Denied), 🟡 Yellow (Pending).
* Enhanced Navigation: Integrated **global search bar** allows staff to quickly filter by patient name (e.g., "Jerry Nelson").

---

### Evaluation Results: [PASS]
The core infrastructure is now **stable**. All critical navigation and feedback issues identified during testing have been resolved.

**Next milestone:** Sprint 2 will transition to **Medication synchronization** functionality.
