# ClearView Green â€” Job Tracking Log Template

**Instructions:** Copy this template to a new row in your tracking spreadsheet (Google Sheets or Excel) for every completed job. Maintain one tab per month.

---

## Column Headers

| # | Date | Customer Name | Address | ZIP | Res/Comm | Services Performed | Quoted $ | Actual $ | Add-Ons | Payment Method | Paid? | Recurring? | Review Requested | Review Received | Follow-Up Date | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| 1 | | | | | | | | | | | | | | | | |
| 2 | | | | | | | | | | | | | | | | |

---

## Field Definitions

| Field | Description |
|---|---|
| **#** | Sequential job number (e.g., 001, 002...) |
| **Date** | Date service was performed |
| **Customer Name** | First and last name |
| **Address** | Full street address |
| **ZIP** | ZIP code (for territory tracking) |
| **Res/Comm** | R = Residential, C = Commercial |
| **Services Performed** | List all services (e.g., "Ext windows + screens") |
| **Quoted $** | Amount quoted before job |
| **Actual $** | Amount collected |
| **Add-Ons** | Any add-on services added on-site |
| **Payment Method** | Card / Cash / Venmo / Zelle / Check |
| **Paid?** | Y / N / Pending (Net-7) |
| **Recurring?** | Y â€“ Monthly / Y â€“ Quarterly / N |
| **Review Requested** | Y / N |
| **Review Received** | Y / N |
| **Follow-Up Date** | Date to re-contact for rebooking (typically +60 days) |
| **Notes** | Damage found, special access, rescheduled, etc. |

---

## Monthly Summary Tab

Maintain a summary tab with these calculated fields:

| Metric | Formula |
|---|---|
| Total Jobs | COUNT of completed rows |
| Gross Revenue | SUM of Actual $ column |
| Average Ticket | Gross Revenue Ã· Total Jobs |
| Residential Revenue | SUMIF Res/Comm = R |
| Commercial Revenue | SUMIF Res/Comm = C |
| Recurring Customers | COUNTIF Recurring = Y |
| Recurring Revenue % | Recurring Revenue Ã· Total Revenue |
| Reviews Collected | COUNTIF Review Received = Y |
| Unpaid Invoices | COUNTIF Paid = N |

---

## Annual Tracker Summary

Keep a running annual summary tab:

| Month | Jobs | Gross Revenue | Expenses | Net Profit | New Customers | Recurring Customers | Reviews |
|---|---|---|---|---|---|---|---|
| January | | | | | | | |
| February | | | | | | | |
| March | | | | | | | |
| April | | | | | | | |
| May | | | | | | | |
| June | | | | | | | |
| July | | | | | | | |
| August | | | | | | | |
| September | | | | | | | |
| October | | | | | | | |
| November | | | | | | | |
| December | | | | | | | |
| **TOTAL** | | | | | | | |

---

*ClearView Green â€” Streak-Free. Chemical-Free. Worry-Free.*
