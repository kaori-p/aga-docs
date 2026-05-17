# Patient Registration

> **Who uses this**: Concierge, Counselor, MedicalTeam, Chief, ClinicManager, Admin
> **Connected to Mobile**: When a patient submits a registration request through the mobile app, they appear in this queue.

## Overview

The Patient Registration screen shows a queue of people who have applied to become patients through the mobile app. Staff review each application, contact the applicant, and formally register them as patients in the system.

---

## How to Access

Click **Patient Registration** in the top navigation bar.

---

## What You See

The screen displays a table of registration applicants with the following columns:

| Column | Description |
|--------|-------------|
| Application Date | When the person submitted their registration request |
| Desired Consultation Period | When the applicant would like to have their first appointment |
| Preferred Location | Which clinic location they prefer |
| Name / Alternative Name | Applicant's name |
| Gender | Applicant's gender |
| Contact Information | Phone number and email |
| Affiliate ID | Referral or affiliate code, if provided |
| Coupon Code | Discount coupon, if provided |
| Registration Status | Whether the applicant has been registered (checkmark icon) |
| Contact Status | Whether staff have successfully contacted the applicant (dropdown) |
| Notes | Staff notes about this applicant |

---

## Filtering the List

Use the filter buttons at the top of the list to narrow down the applicants:

| Filter | Shows |
|--------|-------|
| Show All | Every applicant |
| Incomplete | Applicants who have not been successfully contacted yet (includes: not called, called once without answer, called twice without answer, etc.) |
| Canceled | Applicants who have been marked as canceled |
| Complete | Applicants who have been successfully contacted and registered |
| No Count | Applicants excluded from the regular count |

---

## Sorting

Click the **Application Date** column header to sort the list:
- Click once: oldest first
- Click again: newest first

---

## Updating the Contact Status

When you call an applicant, update their contact status using the dropdown in their row:

Available statuses:
- Not Called
- Called — No Answer (1st attempt)
- Called — No Answer (2nd attempt)
- Called — No Answer (3rd attempt)
- Called — Connected
- Canceled

The status updates immediately when you select it from the dropdown.

---

## Adding a Note

To record information about an applicant (e.g., scheduling preferences, notes from a phone call):

1. Click the **Notes** icon in the applicant's row
2. A dialog opens with a text area
3. Type your note
4. Click **Save**

Notes are visible to all staff who view this registration.

---

## Registering an Applicant as a Patient

Once you have contacted the applicant and confirmed they want to proceed:

**Individual registration:**
1. Find the applicant in the list
2. Click the **Register** button in their row
3. Confirm the registration

**Bulk registration** (register multiple applicants at once):
1. Check the checkboxes next to the applicants you want to register
2. Click **Select All** to check all visible applicants, if needed
3. Click the **Register Selected** button at the top
4. Confirm the action

After registration:
- The applicant's **Registration Status** column shows a checkmark
- Their patient profile is created in the system
- The applicant can now be found in the [Patient Management](03-patient-management.md) section
- A link to their patient profile appears in the registration row

---

## Already-Registered Patients

If an applicant has already been registered, their row shows a link to their existing patient profile instead of a Register button. Click the link to open their patient details.

---

## Error Messages

| Message | What it means | What to do |
|---------|---------------|------------|
| "Registration failed" | An error occurred during registration | Check the patient's information for errors, then try again |

---

## Tips & Notes

- New applicants appear at the top of the list (sorted by application date descending by default)
- The desired consultation period and preferred location are the applicant's preferences — they are not confirmed appointments yet
- Always contact the applicant to confirm before registering — the registration process creates their patient record and cannot be easily undone
