# Smart Care Sync - Full Test Plan (Final)

### TC-01: User Login

| Scenario | Expected Result | Status |
| :--- | :--- | :--- |
| Login with valid credentials | User is redirected to home page | ✅ PASS |
| Login with wrong password | Error message displayed | ✅ PASS |
| Login with unregistered email | Error message displayed | ✅ PASS |
| Login with empty fields | Validation message shown | ✅ PASS |
| Logout from system | User is redirected to Login Page | ✅ PASS |

### TC-02: Registration

| Scenario | Expected Result | Status |
| :--- | :--- | :--- |
| Register with valid credentials | Account created successfully | ✅ PASS |
| Register using existing email | Error message displayed | ✅ PASS |
| Submit registration form with missing required fields | Validation message shown | ✅ PASS |
| Enter invalid email format | System shows email format error | ✅ PASS |

### TC-03: Appointment Booking

| Scenario | Expected Result | Status |
| :--- | :--- | :--- |
| Book an available appointment slot | Appointment confirmed and saved | ✅ PASS |
| Book an already occupied time slot | System prevents double booking | ✅ PASS |
| Book appointment without selecting date | Validation message displayed | ✅ PASS |
| Book appointment without selecting doctor | Validation message shown | ✅ PASS |
| View booked appointments | All booked appointments displayed correctly | ✅ PASS |
| Cancel existing appointment | Appointment removed successfully | ✅ PASS |
| Reschedule appointment | Updated appointment details saved | ✅ PASS |

### TC-04: Doctor Appointment Calendar

| Scenario | Expected Result | Status |
| :--- | :--- | :--- |
| Doctor views daily schedule | All assigned appointments displayed | ✅ PASS |
| Doctor updates availability | Availability updated successfully | ✅ PASS |
| Doctor approves appointment | Appointment status changed to Approved | ✅ PASS |

### TC-05: Admin Management

| Scenario | Expected Result | Status |
| :--- | :--- | :--- |
| Admin views all appointments | All appointments displayed correctly | ✅ PASS |
| Admin deletes appointment | Appointment removed successfully | ✅ PASS |
| Admin views registered users | User list displayed correctly | ✅ PASS |

### TC-06: Notification

| Scenario | Expected Result | Status |
| :--- | :--- | :--- |
| Booking confirmation notification | Confirmation message displayed | ✅ PASS |
| Cancellation notification | Cancellation message displayed | ✅ PASS |
| Appointment reminder notification | Reminder displayed before appointment time | ✅ PASS |

### TC-07: Appointment Confirmation Interface

| Scenario | Expected Result | Status |
| :--- | :--- | :--- |
| Appointment booking is successful | Confirmation message displayed | ✅ PASS |
| User clicks return to dashboard | User redirected to main control panel | ✅ PASS |
| User refreshes confirmation page | Appointment information remains recorded | ✅ PASS |
| System generates confirmation message | Appointment ID and details are displayed | ✅ PASS |

### TC-08: Digital Prescription Interface

| Scenario | Expected Result | Status |
| :--- | :--- | :--- |
| Doctor enters medication details and submits | Digital prescription is saved successfully | ✅ PASS |
| Doctor leaves required fields empty | System displays validation error | ✅ PASS |
| Doctor submits prescription | Patient can view prescription in system | ✅ PASS |
| Doctor edits prescription details | Updated prescription information saved | ✅ PASS |

### TC-09: Medication Reminder Setup

| Scenario | Expected Result | Status |
| :--- | :--- | :--- |
| User sets medication reminder time | System saves reminder successfully | ✅ PASS |
| Reminder time arrives | System sends reminder notification | ✅ PASS |
| User enters invalid reminder time | System displays error message | ✅ PASS |
| User updates reminder schedule | System saves new reminder time | ✅ PASS |

### TC-10: Laboratory Test Order Interface

| Scenario | Expected Result | Status |
| :--- | :--- | :--- |
| Doctor enters test order details | Test request is recorded in the system | ✅ PASS |
| Doctor leaves test information empty | System shows validation message | ✅ PASS |
| Doctor submits test order | Patient test request appears in lab system | ✅ PASS |
| Doctor sets test priority | System records test priority correctly | ✅ PASS |

### TC-11: Laboratory Test Results Interface

| Scenario | Expected Result | Status |
| :--- | :--- | :--- |
| Patient opens test results page | System displays available test results | ✅ PASS |
| Lab uploads new result | Result becomes visible to patient | ✅ PASS |
| Test result not yet available | System shows “Pending” status | ✅ PASS |
| Patient views results | Detailed test report is displayed | ✅ PASS |

### TC-12: Patient Medical Records Interface

| Scenario | Expected Result | Status |
| :--- | :--- | :--- |
| Doctor searches patient by name | System displays matching patient records | ✅ PASS |
| Doctor searches using phone number | Correct patient information appears | ✅ PASS |
| Patient record not found | System displays “No record found” message | ✅ PASS |
| Doctor opens patient record | Medical history information is displayed | ✅ PASS |

### TC-13: Medication Adherence Monitoring

| Scenario | Expected Result | Status |
| :--- | :--- | :--- |
| Doctor opens adherence dashboard | Patient medication adherence rates displayed | ✅ PASS |
| Patient misses medication reminder | System marks missed dose | ✅ PASS |
| Patient follows reminder schedule | Adherence rate updates correctly | ✅ PASS |
| Doctor reviews patient adherence | System shows adherence statistics | ✅ PASS |

### TC-14: Administrative Appointment Management

| Scenario | Expected Result | Status |
| :--- | :--- | :--- |
| Admin opens appointment dashboard | System displays all appointment records | ✅ PASS |
| Admin approves appointment | Appointment status updated to approved | ✅ PASS |
| Admin rejects appointment | Appointment status updated to rejected | ✅ PASS |
| Admin marks appointment completed | Status updated to completed | ✅ PASS |

### TC-15: Daily Appointment Reports

| Scenario | Expected Result | Status |
| :--- | :--- | :--- |
| Admin opens daily report | System displays summary of appointments | ✅ PASS |
| Admin checks completed appointments | Completed appointments list displayed | ✅ PASS |
| Admin checks cancelled appointments | Cancelled appointment list displayed | ✅ PASS |
| System generates daily report | Report shows appointment statistics | ✅ PASS |
