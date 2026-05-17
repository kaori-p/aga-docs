# Shipment

> **Who uses this**: Concierge, ClinicManager, Admin
> **Connected to Mobile**: When an order is marked as shipped here, the patient's order status on the mobile app updates to "Shipped."

## Overview

The Shipment screen shows all medicine orders that are ready to be shipped to patients. Staff can select orders, print shipping labels and packaging slips, export order data, and mark orders as shipped.

---

## How to Access

Click **Shipment** in the top navigation bar.

---

## What You See

A table of orders pending shipment. Each row shows:

| Column | Description |
|--------|-------------|
| Checkbox | Select this order for bulk actions |
| Patient Name | Name of the patient who placed the order |
| Address | Delivery address |
| Phone Number | Patient contact number |
| Medicines | List of medicines in the order (click Show/Hide to expand) |
| Total Price | The total cost of the order |
| Error Indicator | A red X icon appears if the order has an issue (hover to see the error detail) |

---

## Expanding Medicine Details

Each order row shows a summary. Click **Show** next to an order to expand the full list of medicines and quantities. Click **Hide** to collapse it.

---

## Selecting Orders

- Check the **checkbox** next to individual orders to select them
- Click **Select All** at the top to select all currently visible orders
- Uncheck the **Select All** checkbox to deselect all

> **Note**: There is a maximum number of orders you can select at once. If you exceed the limit, a warning message appears and excess selections will not be added.

---

## Actions When Orders Are Selected

Once one or more orders are checked, the following action buttons appear at the top:

| Button | What it does |
|--------|--------------|
| **Print Shipments** | Prints the packaging slips for selected orders |
| **Print Orders** | Prints order detail sheets for selected orders |
| **Print Labels** | Prints shipping labels for selected orders |
| **Export to CSV** | Downloads a CSV file of the selected orders' data |
| **Shipment Complete** | Marks the selected orders as shipped and removes them from this list |

---

## Actions When No Orders Are Selected (Bulk Actions)

When nothing is selected, the top buttons apply to **all orders** in the current list:

| Button | What it does |
|--------|--------------|
| **Print All Shipments** | Prints packaging slips for every order in the list |
| **Print All Orders** | Prints order details for every order in the list |
| **Print All Labels** | Prints shipping labels for every order |
| **Export All to CSV** | Downloads a CSV of all orders |

---

## Marking Orders as Shipped

After physically shipping the orders:

1. Select the orders you shipped (or select all if you shipped everything in the list)
2. Click **Shipment Complete**
3. Confirm the action

The selected orders disappear from the shipment list. The patient's mobile app order status updates to **Shipped**.

---

## Error Orders

If an order has a problem that prevents shipping (e.g., missing address, payment issue), a **red X icon** appears in that order's row.

- **Hover** over the red X to read the specific error message
- Resolve the issue before including that order in a shipment

---

## Pagination

The list loads a limited number of orders at a time. Click **Load More** at the bottom to see additional pending orders.

---

## CSV Export

Exported CSV files contain all order details useful for logistics or record-keeping. If an export encounters an error, a notification message will appear explaining the issue.

---

## Tips & Notes

- Always verify the patient's address before printing labels — it is displayed in the table
- Orders with errors (red X) will still appear in the list until the error is resolved; they cannot be marked as complete while the error exists
- Shipment Complete is irreversible — make sure the correct orders are selected before confirming
