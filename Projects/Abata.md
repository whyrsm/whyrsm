# Abata PMB System

> **PMB** = Penerimaan Murid Baru (New Student Enrollment)

A full-stack student registration and enrollment management system for **Abata/LKBW** educational institutions (KB, TK, SD, SMP levels).

---

## Business & Product Context

### About Abata/LKBW

Abata/LKBW is an educational institution in Indonesia offering programs across multiple levels:
- **KB** (Kelompok Bermain) – Playgroup
- **TK** (Taman Kanak-kanak) – Kindergarten (TK A & TK B)
- **SD** (Sekolah Dasar) – Elementary School (Grades 1-6)
- **SMP** (Sekolah Menengah Pertama) – Junior High School (Grades 7-9)

The institution operates under **Yayasan ABACU** and uses **Bank Syariah Indonesia** for payment processing.

### Business Problem

Before this system, the student enrollment process was manual and fragmented:
- Parents had to visit the school physically to register
- Payment tracking was done via spreadsheets
- Observation scheduling relied on phone calls and paper records
- Announcement of results was slow and error-prone
- No centralized view of enrollment pipeline for administrators

### Product Vision

The PMB System digitizes the entire enrollment journey from initial registration to final enrollment, providing:
- **Self-service portal** for parents to register and track their children's enrollment status
- **Centralized dashboard** for administrators to manage the enrollment pipeline
- **Automated notifications** via WhatsApp to keep parents informed
- **Payment tracking** with evidence upload and verification workflow
- **Document generation** for acceptance letters, biodata, and receipts

### Target Users

| User Type | Description | Primary Actions |
|-----------|-------------|-----------------|
| **Wali Murid (Parents)** | Parents/guardians registering their children | Register, upload payments, track status, confirm enrollment |
| **Staff Pendidikan** | Education staff handling day-to-day operations | Manage registrations, schedule observations, process results |
| **Staff TU** | Administrative staff | Data entry, document management |
| **Finance** | Finance team | Verify payments, manage payment schemes, generate invoices |
| **CS (Customer Service)** | Front-line support | Assist parents, answer inquiries |
| **Manager Pendidikan** | Education manager | Approve announcements, oversee enrollment process |
| **Admin/IT** | System administrators | Full system access, user management, permissions |

### Key Business Metrics

The system tracks and enables reporting on:
- Registration volume by academic year, jenjang (level), and period
- Payment verification turnaround time
- Observation attendance rates
- Pass/fail ratios per observation period
- Enrollment conversion rates (registered → enrolled)

### Academic Year & Registration Periods

Registrations are organized by:
- **Academic Year**: e.g., 2025/2026, 2026/2027
- **Payment Period**: Early Bird, Gelombang 1, Gelombang 2, Gelombang 3 (each with different pricing)

### Payment Structure

The enrollment fee structure includes:
- **Base Education Fee** – varies by grade level and payment period
- **Discounts**: Loyalty program, event discounts, full payment discount, group discount
- **Cash Contribution** – optional contribution from parents
- **Payment Options**: Full payment or installment (up to 4 installments)
