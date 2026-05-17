# Subscription

> **Who uses this**: Doctor, Counselor, Chief, ClinicManager, Admin
> **Connected to Mobile**: When a subscription is active, recurring medicine orders are automatically created and appear in the patient's Orders tab on the mobile app. The patient pays for these using the standard payment flow.

## Overview

A subscription is a recurring medicine delivery plan for a patient. Once set up, it automatically generates a medicine order for the patient on a regular schedule (every 20 to 360 days), without staff needing to create each order manually.

Subscriptions are managed from within a patient's medical record, under a specific appointment.

---

## How to Access

1. Go to **Patient Management** → search for the patient
2. Click **View Medical Record**
3. Open the patient's latest appointment record
4. Click the **Subscription** tab

> **Note**: The Subscription tab only appears on the **most recent** appointment for the patient. It is not visible on older appointment records.

---

## Subscription States

| State | What it means |
|-------|---------------|
| **No Subscription** | The patient does not have an active or paused subscription |
| **Active** | A subscription is running; orders are generated on schedule |
| **Paused** | The subscription is temporarily suspended; no orders will be generated during the pause |
| **Deleted** | The subscription has been canceled |

---

## Creating a Subscription

> **Rule**: A patient can only have **one** active or paused subscription at a time. Attempting to create a second one will show a conflict error.

1. On the Subscription tab, click **Subscription Start**
2. A medicine selection screen appears

**Step 1 — Select Medicines**
- A paginated list of medicines available for this patient appears
- Check the checkbox next to each medicine you want to include
- For each selected medicine, enter the **quantity** (minimum 1, maximum available quantity)

**Step 2 — Configure Payment Settings**

| Setting | Options | Notes |
|---------|---------|-------|
| Payment Cycle | 20, 25, 30, 35, … up to 360 days | How many days between each automatic order |
| Discount Type | None, Percentage (%), Fixed Yen (¥) | Type of discount to apply |
| Discount Value | A number | The percentage or yen amount of the discount (only shown when a discount type is selected) |

**Step 3 — Review the Summary**

The system automatically calculates:

| Line | Description |
|------|-------------|
| Subtotal | Total cost of selected medicines after any discount |
| Discount | Amount deducted based on the discount settings |
| Shipping | Fixed shipping fee of ¥520 |
| Grand Total | Subtotal − Discount + Shipping |

3. Click **Subscription Start**
4. A confirmation dialog shows the list of selected medicines — review it carefully
5. Click **Confirm** to start the subscription

The subscription is now **Active**. The first medicine order will be generated according to the payment cycle.

---

## Managing an Active Subscription

Once a subscription is running, the Subscription tab shows the current status and available actions.

### Pause a Subscription

Pausing stops future charges for a set number of payment cycles.

1. Click **Pause**
2. A dialog opens asking how many charges you want to skip
3. Select the number (e.g., entering "2" skips the next 2 scheduled payments)
4. Click **Confirm**

The subscription status changes to **Paused**. It will resume automatically after the skipped cycles.

### Change the Next Payment Date

Move the date when the next medicine order will be generated.

1. Click **Change Next Payment Date**
2. A date picker dialog opens
3. Select the new date
4. Click **Confirm**

### Delete a Subscription

Cancels the subscription entirely.

1. Click **Delete**
2. A confirmation dialog appears
3. Click **Confirm Delete**

The subscription status changes to **Deleted**. No further orders will be generated. A new subscription can be created from this appointment if needed.

---

## Viewing Subscription Order Details

When a subscription is Active or Paused, the Subscription tab shows:

- List of medicines included, with quantities and per-item cost
- The next scheduled payment date
- The total amount for each cycle

---

## Error Messages

| Message | What it means | What to do |
|---------|---------------|------------|
| "A subscription already exists for this patient" | The patient already has an Active or Paused subscription | Pause or delete the existing subscription before creating a new one |
| "Subscription not found" | The subscription record could not be located | Refresh the page; contact support if the problem persists |
| "Invalid argument" | A form field contains an invalid value | Check the quantity, cycle, and discount values for errors |

---

## Tips & Notes

- The patient is **not** notified about the subscription setup on the web — they will see new orders appear in their mobile app Orders tab when each cycle generates an order
- Subscription orders appear and are paid by the patient the same way as regular medicine orders (bank transfer, card, or free delivery)
- If a patient has unpaid subscription orders, new orders may not generate until payment is resolved
