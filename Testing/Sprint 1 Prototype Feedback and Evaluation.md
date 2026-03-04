# Prototype Feedback and Evaluation (Sprint 1)
* **Project:** Smart Care Sync
* **Focus:** Core Foundation and Role-Based Access

## Evaluation Objective
The primary goal was to validate the "Happy Path" for three distinct user archetypes(Outpatient, Doctor, Hospital Administrative Staff) and ensure the appointment lifecycle was logically sound before moving to medical features in Sprint 2.

## Stakeholder Feedback

### Outpatient Module
* **Advantages:** Users appreciated the linear booking flow and the clarity of available time slots.
* **Disadvantages:** Lack of a "safety net" (confirmation pop-up) when cancelling an appointment, and no confirmation message after successfully booking an appointment.
* **Improvements:** Added a mandatory confirmation dialog box and prominent notification information.

### Doctor Module
* **Advantages:** The daily schedule clearly displays the day's work arrangements.
* **Disadvantages:** Text readability in the appointment blocks was too small.
* **Improvements:** Increased font size/contrast.

### Hospital Administrative Staff##
* **Advantages:** The table layout is highly efficient, clearly displaying patient, date, time, and status information in a single line for easy browsing.
* **Disadvantages:** All statuses (Approved, Rejected, Pending) use the same black italic font, making them difficult to distinguish. The "Sync/Refresh" icon is ambiguous.
* **Improvements:** Color coding has been introduced (green for approved, red for rejected), and a "Search" bar has been added for quick access to specific patients, such as "Jerry Nelson".

## Conclusion
The prototype successfully moved from "Wireframe" to "Stable Foundation." By resolving the navigation and feedback issues identified here, the system is now ready for the **Medication Sync** features in Sprint 2.
