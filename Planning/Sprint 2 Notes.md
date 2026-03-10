# Sprint 2: Medication Tracking and Digital Prescriptions
* **Duration:** Week 3
* **Goal:** Implement hospital data management, medication adherence tracking, and administrative reporting.

---

## Scope of Work
To transition from a scheduling tool to a functional clinical ecosystem, the following features were implemented:

* **Hospital Data Flow:** Doctors can add prescribed medications, create digital prescriptions, and order lab tests.
  
* **Patient Adherence:** Outpatients receive reminders, can mark doses as "Taken," and track lab status (Pending/Completed).
  
* **Alert System:** Automated triggers for missed doses sent to both outpatients and doctors.
  
* **Admin & Analytics:** Real-time dashboards for hospital activities, searchable patient history, and daily hospital report generation.
  
* **Schedule Management:** Enhanced staff controls to block doctor time slots and update appointment statuses (In Progress/Completed).

---

## Challenges and Solutions
| Challenges | Impact | Solutions |
| :--- | :--- | :--- |
| **Data Interdependency** | Tasks could not start until others were finished, causing team idle time. | Identified critical paths early and shifted to parallel work streams where independent UI components could be built. |
| **Prototyping Delays** | Figma prototype completion was delayed, pushing back the final evaluation phase. | Set stricter internal deadlines and increased stakeholder consultation frequency to avoid late-stage reworks. |
| **Logic Complexity** | Ensuring the "Missed Dose" logic synced correctly between Patient and Doctor views. | Conducted focused logic reviews to ensure adherence percentages reflected real-time patient inputs accurately. |

---

## Retrospective
## Sprint Retrospective

### What Went Well
*   **Stakeholder Alignment:** Continuous consultation during the project helped avoid misunderstandings and reduced the need for major reworks.
*   **Prototype Quality:** Despite the delay, the final Figma prototypes are fully interactive, functional, and met all clinical requirements.
*   **Team Synergy:** High levels of cooperation were maintained, with members effectively executing tasks assigned by the Product Owner (PO).

### Areas for Improvement
*   **Schedule Slippage:** The delay in the Figma prototype highlighted a need for better time management and realistic buffer periods.
*   **Task Dependency Management:** Some team members were left waiting for prerequisite tasks, indicating a need for more agile task reassignment.

---

## Continuous Process Improvement (CPI)
As this is the final sprint, the following improvements have been codified for the project hand-off and future scaling:
*   **Timeline Discipline:** Established a clearer, milestone-based timeline for design assets to prevent downstream bottlenecks.
*   **Parallel Workflow Mapping:** Early identification of task dependencies to ensure team resources are utilized efficiently even during design delays.
*   **Proactive Issue Tracking:** Shifted to a weekly progress review model to identify and solve blockers before they impact the sprint deadline.
