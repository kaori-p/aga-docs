# Patient Management

> **Who uses this**: Concierge, Counselor, Doctor, MedicalTeam, Chief, ClinicManager, Admin
> **Connected to Mobile**: Appointment details entered here appear in the patient's mobile app. Interview sheet answers submitted by the patient on mobile are viewable here.

## Overview

The Patient Management section lets staff search for patients, view their profiles and medical records, create new patients, and manage their appointments. It is the central hub for all patient-related operations.

---

## How to Access

Click **Patients** in the top navigation bar.

---

## Patient Search

The search screen shows a list of patients and a search bar at the top.

### Basic Search

Type a patient's **name**, **phone number**, or **email address** into the search box. The list filters as you type.

### Advanced Search Filters

> **Note**: Advanced filters are only visible to certain roles (Chief, Doctor, Counselor, ClinicManager, Admin).

Click **Filter** to expand the advanced filter options:

| Filter | What it does |
|--------|--------------|
| Ongoing Treatment | Shows only patients currently receiving treatment |
| Follow | Shows only patients flagged for follow-up |
| Doctor Checked | Shows only patients whose doctor review is complete |
| Clinic | Filter by specific clinic location |

After setting filters, click **Apply** to update the list.  
Click **Clear** to remove all filters and show all patients.

### Patient List Columns

| Column | Description |
|--------|-------------|
| Name / Alternative Name | Patient's registered name |
| Date of Birth / Age | Patient's age and birth date |
| Phone Number | Contact number |
| Activity Status | Whether the patient is currently logged into the mobile app |
| Patient Status | Current treatment status (shown as a label) |

### Actions per Patient (buttons on the right of each row)

| Button | What it does |
|--------|--------------|
| Create Appointment | Opens the appointment creation wizard (only shown if no appointment is currently scheduled) |
| Edit Appointment | Opens the existing scheduled appointment for editing (shown if an appointment exists) |
| View Patient Details | Opens the patient's full profile in a new tab |
| View Medical Record | Opens the patient's medical record in a new tab |
| Blood Examination | Opens the blood test results page in a new tab |

> **Important**: If a patient has **unpaid orders**, you will see a warning notification and the **Create Appointment** button will be blocked until the outstanding payment is resolved.

### Pagination

The list loads a limited number of patients at a time. Scroll to the bottom and click **Load More** to see additional results.

---

## Adding a New Patient

1. Click the **Add New Patient** button (top right of the patient list)
2. A multi-step form opens — fill in the patient's personal information:
   - Full name (required)
   - Alternative name (optional)
   - Date of birth (required)
   - Gender (required)
   - Phone number (required)
   - Email address (optional)
   - Address
3. Accept the **Terms of Service** checkbox on behalf of the patient (required)
4. Click **Save**

The new patient appears in the patient list immediately.

---

## Patient Details

Click **View Patient Details** for a patient to open their profile. From here you can:

- View all personal information
- Edit any details by clicking **Edit** and saving your changes
- See a summary of past and upcoming appointments
- Access links to the medical record and other patient sections

---

## Creating an Appointment

1. On the patient search screen, click **Create Appointment** next to the patient's name
2. The **Appointment Wizard** opens — it has multiple steps:

**Step 1 — Basic Information**
- Select **appointment type** (required)
- Select **date and time** (required)
- Assign a **staff member / doctor** (required; on small screens, a doctor selection modal appears)
- Select **clinic location** (required)

**Step 2 — Additional details** (varies by appointment type)

3. Review the summary
4. Click **Save** to create the appointment

The appointment now appears on the Calendar and in the patient's mobile app.

### Appointment Validation Rules

- The appointment date cannot be in the past
- All required fields must be filled before the wizard will proceed to the next step
- A patient cannot have two appointments scheduled at the same time

---

## Editing an Appointment

1. On the patient search screen, click **Edit Appointment**
2. The same Appointment Wizard opens, pre-filled with existing information
3. Make changes to any step
4. Click **Save**

---

## Medical Record

Each patient has a medical record containing:

- **Appointment Records**: History of all consultations with notes
- **Interview Sheets**: Health questionnaire answers submitted by the patient via mobile
- **Blood Examination Results**: Lab test data
- **Orders & Prescriptions**: Medicine orders and prescriptions
- **Media Library**: Clinical photos and images
- **Appointment Images**: Photos taken during consultations

Click **View Medical Record** from the patient search screen or patient details page to access these sections.

---

## Call Screen

The Call Screen shows telephony information for contacting a patient.

Access: Patient Details → **Call Screen** tab or button

---

## Blood Examination

View and enter blood test results for a specific patient.

Access: Patient search → **Blood Examination** button (opens in new tab)

---

## Orders & Prescriptions

View a patient's prescription and medicine order history.

Access: Medical Record → **Orders & Prescriptions** tab

---

## Media Library

Upload and manage clinical photos for a patient.

Access: Medical Record → **Media Library** tab

- Click **Upload** to add new photos
- Photos are organized by date
- Click a photo to view it full size

---

## Appointment Images

View photos taken during a specific consultation.

Access: Medical Record → **Appointment Images** tab

---

## Tips & Notes

- Opening patient details and medical records from the search list always opens them in a **new browser tab**, so you do not lose your search results
- The unpaid orders warning appears as a red notification banner at the top of the screen — resolve the payment before creating new appointments
- Interview sheet answers filled in by the patient on their mobile app are visible under the patient's medical record automatically
