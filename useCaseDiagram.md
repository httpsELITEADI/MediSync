# Use Case Diagram

```mermaid
usecaseDiagram
actor Patient
actor Doctor
actor Admin

Patient --> (Register/Login)
Patient --> (Book Appointment)
Patient --> (View Prescriptions)
Patient --> (Upload Medical Records)
Patient --> (Check Symptoms)

Doctor --> (Login)
Doctor --> (Manage Schedule)
Doctor --> (View Appointments)
Doctor --> (Write Prescription)
Doctor --> (Access Patient Records)

Admin --> (Manage Users)
Admin --> (Manage Doctors)
Admin --> (System Monitoring)

(Book Appointment) --> (Appointment Calendar)
(Check Symptoms) --> (AI Symptom Checker)
