# 5.4 System Wireframe Design

This section illustrates the user interface design for the Smart Care Sync system. Each wireframe is mapped to specific functional requirements to ensure the interface supports the necessary clinical and administrative workflows.

---

## 5.4.1 User Access & Identity Management
These screens handle the secure entry and onboarding process for all system users.


| Screen Name | Wireframe & Functional Description |
| :--- | :--- |
| **Login Portal** | <img src="./assets/login_wireframe.png" width="1440" /> <br><br> **Description:** Secure entry point for all roles. Supports encrypted authentication and session management (Requirement 2). |
| **User Registration** | <img src="./assets/register_wireframe.png" width="1440" /> <br><br> **Description:** Allows outpatients and staff to create accounts, capturing essential credentials and personal data (Requirement 1). |

---

## 5.4.2 Outpatient Portal & Appointment Scheduling
The following interfaces empower patients to manage their consultations and navigate the hospital's services.


| Screen Name | Wireframe & Functional Description |
| :--- | :--- |
| **Patient Dashboard** | <img src="./assets/patientdashboard_wireframe.png" width="1440" /> <br><br> **Description:** A central summary for outpatients to view upcoming visits and health alerts (Requirement 23). |
| **Appointment Booking** | <img src="./assets/bookappointment1_wireframe.png" width="1440" /> <br> <img src="./assets/bookappointment2_wireframe.png" width="1440" /> <br><br> **Description:** A two-step workflow for selecting departments, doctors, and available time slots (Requirement 4). |
| **View Upcoming Visits** | <img src="./assets/viewupcomingappointment_wireframe.png" width="1440" /> <br><br> **Description:** Displays a chronological list of scheduled consultations for the patient (Requirement 3). |
| **Modify Appointments** | <img src="./assets/cancelorrescheduleappointment_wireframe.png" width="1440" /> <br><br> **Description:** Interface for patients to cancel or move appointments with real-time slot updates (Requirement 5). |

---

## 5.4.3 Medication Tracking & Clinical Records
These screens focus on Sprint 2 requirements regarding treatment adherence and digital prescriptions.


| Screen Name | Wireframe & Functional Description |
| :--- | :--- |
| **Medication Reminders** | <img src="./assets/setmedicationreminder_wireframe.png" width="1440" /> <br><br> **Description:** Allows outpatients to customize daily notification schedules for their dosages (Requirement 10). |
| **Digital Prescriptions** | <img src="./assets/viewdigitalprescription_wireframe.png" width="1440" /> <br><br> **Description:** A patient-facing view to access and download digital prescriptions (Requirement 15). |
| **Lab Status Tracking** | <img src="./assets/tracklabstatus_wireframe.png" width="1440" /> <br><br> **Description:** Provides real-time status updates ("Pending" or "Completed") for laboratory investigations (Requirement 17). |
| **Adherence Monitoring** | <img src="./assets/doctorviewadherence_wireframe.png" width="1440" /> <br><br> **Description:** A doctor-facing analytics dashboard showing patient medication compliance percentages (Requirement 13). |

---

## 5.4.4 Doctor’s Clinical Workflow
The following designs optimize the physician's experience during daily consultations and patient management.


| Screen Name | Wireframe & Functional Description |
| :--- | :--- |
| **Doctor Dashboard** | <img src="./assets/doctor_dashboard_wireframe.png" width="1440" /> <br><br> **Description:** A high-level overview of daily tasks, pending lab results, and adherence alerts (Requirement 23). |
| **Daily Patient Queue** | <img src="./assets/doctordailyappointment_wireframe.png" width="1440" /> <br><br> **Description:** A dedicated clinical view for doctors to manage the current day's patient list (Requirement 6). |
| **Prescription Entry** | <img src="./assets/addprescribedmedication_wireframe.png" width="1440" /> <br><br> **Description:** Interface for doctors to input medications and dosages into patient digital records (Requirement 9 & 14). |
| **Lab Test Ordering** | <img src="./assets/labtestorder_wireframe.png" width="1440" /> <br><br> **Description:** Enables doctors to digitally request blood tests or imaging during a visit (Requirement 16). |

---

## 5.4.5 Hospital Administration & Operations
These screens provide the tools for staff to manage hospital-wide activities and generate insights.


| Screen Name | Wireframe & Functional Description |
| :--- | :--- |
| **Schedule Management** | <img src="./assets/managedoctorschedule_wireframe.png" width="1440" /> <br><br> **Description:** Allows staff to configure doctor availability and block specific time slots (Requirement 20). |
| **System Notifications** | <img src="./assets/notification_wireframe.png" width="1440" /> <br> <img src="./assets/doctorappointmentnotification_wireframe.png" width="1440" /> <br><br> **Description:** Managing confirmation alerts and follow-up reminders for both doctors and patients (Requirement 7 & 18). |
| **Patient Record Search** | <img src="./assets/searchpatientrecord_wireframe.png" width="400" /> <br><br> **Description:** A search interface for staff to quickly locate patient files via Name or ID (Requirement 25). |
| **Patient History View** | <img src="./assets/viewpatienthistory_wireframe.png" width="400" /> <br><br> **Description:** A comprehensive log of a patient's previous medical visits and medication history (Requirement 24). |
| **Operational Reports** | <img src="./assets/generatedailyreport_wireframe.png" width="400" /> <br><br> **Description:** Administrative tool to generate and export summaries of daily hospital appointment metrics (Requirement 22). |
