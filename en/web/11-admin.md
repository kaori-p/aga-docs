# Admin

> **Who uses this**: Admin only
> **Connected to Mobile**: Push notifications created here are sent to patients' mobile devices. Coupon codes created here can be entered by patients during registration on mobile.

## Overview

The Admin panel provides system-wide controls for managing clinics, coupons, push notifications, income statistics, and treatment rooms. Only users with the **Admin** role can access this section.

---

## How to Access

Click **Admin** in the top navigation bar. This option is only visible to Admin-role users.

---

## Clinic Management

### What You Can Do

- Create new clinic locations
- Edit existing clinic details
- Configure clinic-specific settings

### Adding a Clinic

1. Click **Clinics** in the Admin menu
2. Click **Add Clinic**
3. Fill in:
   - Clinic name (required)
   - Address (required)
   - Contact phone number (required)
   - Any other clinic-specific settings
4. Click **Save**

### Editing a Clinic

1. Find the clinic in the list
2. Click **Edit**
3. Update the details
4. Click **Save**

---

## Coupons

Coupons give patients a discount when they register. Patients enter the coupon code in the mobile app during registration.

### Creating a Coupon

1. Click **Coupons** in the Admin menu
2. Click **Create Coupon**
3. Fill in:
   - **Coupon Code** (required): The code patients will enter (e.g., WELCOME10)
   - **Discount Amount** (required): The discount value
   - **Discount Type**: Percentage or fixed yen amount
   - **Expiration Date** (required): When the coupon stops being valid
   - Any usage limits, if applicable
4. Click **Save**

The coupon is now active. Share the code with patients through your usual communication channels.

### Editing a Coupon

1. Find the coupon in the list
2. Click **Edit**
3. Update the details (e.g., extend the expiration date)
4. Click **Save**

### Deleting a Coupon

1. Find the coupon in the list
2. Click **Delete** and confirm

Deleted coupons can no longer be used by patients.

---

## Push Notifications

Send notifications that appear on patients' mobile devices.

### Creating a Notification

1. Click **Notifications** in the Admin menu
2. Click **Create Notification**
3. Fill in:
   - **Title** (required): The notification headline
   - **Message** (required): The notification body text
   - **Target**: Which patients or patient group receives the notification (e.g., all patients, specific clinic patients, specific role)
   - **Send Time**: When to deliver the notification (immediately, or scheduled for a future date/time)
4. Click **Send** (or **Schedule** if a future time is set)

### Editing a Scheduled Notification

Notifications scheduled for the future can be edited before they are sent.

1. Find the notification in the list
2. Click **Edit**
3. Make changes and click **Save**

### Deleting a Notification

1. Find the notification in the list
2. Click **Delete** and confirm

Only notifications that have not yet been sent can be deleted.

---

## Income Statistics

View revenue data by clinic and time period.

1. Click **Income Statistics** in the Admin menu
2. Select a **clinic** from the dropdown
3. Select a **date range** (start date and end date)
4. The screen displays:
   - Total revenue for the selected period
   - Breakdown by category (if applicable)

The data is read-only — no changes can be made from this screen.

---

## Room Management

Create and manage the treatment rooms available at each clinic.

### Adding a Room

1. Click **Rooms** in the Admin menu
2. Click **Add Room**
3. Fill in:
   - Room name or number (required)
   - Clinic location (required) — which clinic the room belongs to
   - Capacity or description (optional)
4. Click **Save**

### Editing a Room

1. Find the room in the list
2. Click **Edit**, update the details, and click **Save**

### Deleting a Room

1. Find the room in the list
2. Click **Delete** and confirm

> **Note**: Rooms with upcoming scheduled events cannot be deleted. Reassign or cancel those events first.

---

## Tips & Notes

- Admin actions affect all clinics in the system — take care when making changes
- Coupon codes are case-sensitive; share the exact code format with patients
- Push notifications are delivered immediately or at the scheduled time — once sent, they cannot be recalled
- Income statistics show completed payment data and may have a short delay for recent transactions
