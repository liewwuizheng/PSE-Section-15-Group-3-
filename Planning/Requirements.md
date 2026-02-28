## 1. Introduction
### 1.1 Project Overview
**Smart Care Sync** is a digital healthcare solution that designed to bridge a gap between hospital vists and home-based rehabilitation. This project directly supports the **Sustainable Developmet Goal 3: Good Health and Well-Being** by improving medication adherence and simplifying outpatient management.

### 1.2 Purpose 
This document details the functional and non-functional requirements of the **Smart Care Sync** prototype system. It served as the primary reference for system design, development, and testing during our four-week agile development cycle.

### 1.3 Project Goal
By providing a seamless digital ecosystem, we improve outpatient health outcomes and ensure 100% patient adherence to follow-up appointments and medication plans.

---

## 2. Scope and Definition
### 2.1 Scope 
* **In-Scope:** Online appointment booking and follow-up scheduling for outpatients, automated medication reminders and adherence tracking, digital access to doctor prescriptions and lab orders, dashboards for doctors and administrative staff to monitor patient progress and schedules

* **Out-Scope:** Billing, payment, and insurance claim management, inpatient ward or emergency department management, pharmacy inventory or supply chain systems, advanced diagnostic tools or AI-based medical recommendations

### 2.2 Definitions
* **Outpatient:** Refers to patients who can visit a hospital without hospitalization.

* **Medication Adherence:** Refers to the degree to which patients take medication as prescribed.

* **Sprint:** Refers to a one-week development cycle using the Agile Scrum methodology.

---

## 3. User Personas


| Persona | Role | Primary Need |
| :--- | :--- | :---|
| Sam | Outpatient | Needs a "one-click" way to log medication and view upcoming appointment or follow-up. |
| Dr.Bruce | Doctor | Needs a path to monitor if patients are sticking to their medication at home. |
| Tony Stank | Admin Staff | Needs to organize doctor's schedule efficiently to reduce missed appointments and follow-up. |

---

## 4. Functional Requirements
### 🏃‍➡️ Sprint 1: Appointment and Foloow-Up Management
Focuses on user access and core appointment scheduling.

| NO | Feature | Description |
| :--- | :--- | :--- |
| 1 | User Registration | The system shall allow outpatients, doctors and admin staff to register secure accounts. |
| 2 | Log in and Log out | Users can securely access their personalized dashboard. |
| 3 | View Upcoming Appointments | Outpatients can view a list of their next doctor visits. |
| 4 | Book Appointment | Outpatients can select a preferred doctor, date and available time slot. |
| 5 | Cancel/Reschedule Appointment | The system shall be flexible for outpatients to modify their booking with real-time slot updates. |
| 6 | Doctor Daily Appointments | A dedicated view for doctors to view the current patient list. |
| 7 | Appointment Notifications | The system shall automatically send booking confirmations and reminders of upcoming follow-up. |
| 8 | Staff Manage Appointments | Hosptial administrative staff has the authority to approve, override, move or delete appointments. |

### 🏃‍➡️ Sprint 2: Medication Tracking and Digital Prescriptions
Focuses on clinical data, adherence, and hospital reports.

| NO | Feature | Description |
| :--- | :--- | :--- |
| 9 | Add Prescribed Medications | Doctors can input medications into patients records. |
| 10 | Set Medication Reminders | Outpatients can customize daily notifications for their dozes. |
| 11 | Mark as **"Taken"** | A simple daily dose adherence check-in system for outpatients. |
| 12 | Missed Dose Alerts | The system shall trigger missed medication doses to outpatient and doctor. |
| 13 | Doctor View Adherence | The system shall generate the analytics dashboard displays the percentage of outpatients taking the prescribed dosage. |
| 14 | Create Digital Prescription | Doctors generate electronic prescriptions within the system. |
| 15 | View Digital Prescription | Outpatients can view or download their prescriptions at any time.. |
| 16 | Lab Test Orders | Doctors can request blood tests or digital imaging examinations for their patients. |
| 17 | Track Lab Status | Outpatients can see if their lab results are "Pending" or "Done". |
| 18 | Prescription Notifications | When a new or updated prescription is added, the system should send a notification to the outpatient. |
| 19 | Prescription Summary | After the consultation, the system should immediately generate and display a comprehensive summary of all medications, dosages, and doctor's instructions for the patient to record and save. |
| 20 | Manage Doctor Schedule | The system shall allow hospital staff to configure doctors' appointment times and block specific time slots to prevent excessive appointments or overlapping appointment times. |
| 21 | Update Appointment Status | The system shall allow hospital administrative staff to mark the appointment as "Completed", "Not Present", or "In Progress". |
| 22 | Generate Daily Reports | Admin can generate and export a summary of hospital daily appointments report. |
| 23 | Dashboard Overview | The system shall provide a centralized, real-time visual summary of daily clinical activities, including appointments, pending laboratory results, and key medication adherence alerts. |
| 24 | View Patient History | Doctors and hospital staffs can access a full log of previous visits and medications. |
| 25 | Search Patient Records | The system shall allow hospital staff to quickly find outpatients information by name or ID. |

---

## 5. Non-Functional Requirements
* **NFR1 (Ease of Use):** High-contrast user interface, easy for elderly users.

* **NFR2 (Performance):** Page load time less than 2 seconds, improving clinical efficiency.

* **NFR3 (Security):** Role-based access control (RBAC) protects patient privacy.

---

## 5. Success Metrics
These Key Performance Indicators (KPIs) will be used to evaluate the effectiveness of the Smart Care Sync prototype in its final evaluation during week four.

* **📈 Medication Adherence:** Achieve an **85% dose "check-in" rate** during internal user testing of the tracking module.

* **⏱️ Appointment Efficiency:** Reduce the average time to schedule follow-up appointments from **5 minutes (manual)** to under 60 seconds (digital).

* **🚫 Zero Overlap:** Achieve 0% scheduling conflicts or duplicate appointments after implementing **Physician Schedule Management (FR20)**.

* **✅ Task Completion Rate:** Achieve a 100% success rate in generating **electronic prescriptions (FR14)** within 2 minutes during the demonstration.

--- 

## 6. System Constraints
These constraints define the technical and operational boundaries of our 4-week academic project.

* **Limited Development Time:** All functionality must be completed within two 1-week iteration cycles.

* **Figma Prototype Only:** This system is a high-fidelity functional prototype; it does not connect to an actual Hospital Information System (HIS) or a real pharmacy API.

* **No Financial Processing Included:** To stay within the 4-week timeframe, the system **does not include** medical billing, insurance claims, and payment gateways.

* **Simulated Data:** All patient and clinical records used for the demonstration are **virtual data** created for academic purposes.

---

## 7. Assumptions
To ensure the system functions as designed, the following assumptions are made:

* **Network Connectivity:** Users (patients, doctors, and staff) have continuous access to a modern web browser and a stable internet connection.

* **Digital Literacy:** Outpatients possess basic smartphone skills, enabling them to view notifications and mark medication usage.

* **Manual Data Entry:** In this prototype system, we assume that doctors/staff will **manually enter** prescriptions and lab data, rather than synchronizing them with external medical devices.

* **Language Support:** The initial prototype system is designed only in **English** to support the primary user group.
