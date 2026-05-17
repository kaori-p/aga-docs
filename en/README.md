# AGA User Manual — Overview

Welcome to the AGA platform user manual. This guide explains how to use the AGA hair clinic management system.

---

## About AGA

AGA is a hair clinic platform made up of **two separate apps** that work together:

| App | Who uses it | What it's for |
|-----|-------------|---------------|
| **Web App** | Clinic staff (concierges, counselors, doctors, managers, admins) | Managing patients, appointments, schedules, shipments, and clinic operations |
| **Mobile App** | Patients | Booking appointments, joining video consultations, ordering medicines, and making payments |

Staff manage everything from the web browser. Patients use the mobile app on their phone.

---

## How the Two Apps Are Connected

Actions taken in one app often affect what the other person sees. Here is a summary of how they connect:

| When staff does this on the Web App… | …this happens on the patient's Mobile App |
|--------------------------------------|-------------------------------------------|
| Creates an available appointment slot on the Calendar | Patient can see and book that time slot |
| Marks an appointment as "Started" | Patient sees a **Join Video Call** button appear |
| Marks a staff member as "Unavailable for Mobile" | Patient cannot book with that staff member |
| Ships a medicine order | Patient's order status changes to **Shipped** |
| Creates a medicine subscription for the patient | Recurring orders appear automatically in the patient's Orders tab |
| Pauses or cancels a subscription | No further orders are generated |
| Sends a push notification from Admin | Patient receives a notification on their phone |
| Creates a coupon code in Admin | Patient can use that code when registering |
| Doctor prescribes medicines | Patient sees those medicines available to order |

| When a patient does this on the Mobile App… | …this appears on the Web App for staff |
|----------------------------------------------|----------------------------------------|
| Submits a registration request (interview sheet) | Staff see the patient in the **Patient Registration** queue |
| Fills out an interview sheet | Staff can view the answers in the patient's medical record |
| Books an appointment | Appointment appears on the staff Calendar |
| Makes a payment | Order payment status updates for staff |

---

## Documentation Structure

### Web App (for Clinic Staff)
- [Roles & Access](web/00-roles-and-access.md) — Who can see and do what
- [Login](web/01-login.md) — Signing in, resetting password
- [Calendar & Scheduling](web/02-calendar.md) — Managing appointments and staff schedules
- [Patient Management](web/03-patient-management.md) — Patient search, records, appointments
- [Patient Registration](web/04-patient-registration.md) — Processing new patient applications
- [Room Schedules](web/05-room-schedules.md) — Managing treatment room bookings
- [Work Shift](web/06-work-shift.md) — Managing staff weekly shifts
- [Blood Appointments](web/07-blood-appointments.md) — Blood test scheduling
- [Shipment](web/08-shipment.md) — Processing and shipping medicine orders
- [Subscription](web/09-subscription.md) — Setting up recurring medicine subscriptions
- [Staff Management](web/10-staff-management.md) — Managing staff, medicines, non-working days
- [Admin](web/11-admin.md) — Clinic settings, coupons, notifications, statistics

### Mobile App (for Patients)
- [Getting Started](mobile/00-getting-started.md) — Download, first launch
- [Login](mobile/01-login.md) — Signing in with phone number
- [Appointments](mobile/02-appointments.md) — Booking and managing consultations
- [Interview Sheet](mobile/03-interview-sheet.md) — Filling out health questionnaires
- [Video Call](mobile/04-video-call.md) — Joining online consultations
- [Medicine Orders](mobile/05-medicine-orders.md) — Ordering prescribed medicines
- [Payment](mobile/06-payment.md) — Paying for medicine orders
- [Notifications](mobile/07-notifications.md) — Viewing clinic messages
- [Profile](mobile/08-profile.md) — Managing your account information

---

## Key Terms

| Term | Meaning |
|------|---------|
| Appointment | A consultation session with a clinic staff member |
| Subscription | A recurring medicine delivery plan set up by staff |
| Order | A one-time or recurring medicine delivery request |
| Interview Sheet | A health questionnaire patients fill in before a consultation |
| Reception Card | A card showing clinic location and appointment details |
