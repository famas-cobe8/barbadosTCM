# DB-001: Dashboard Test – Order Summary Display

> **Summary:** Verify that the dashboard correctly displays the order summary with accurate counts and percentages.

**Preconditions:**  
- Vendor is logged in.  
- Orders exist in different statuses (Pending, Running, Completed).

### Scenario 1: Display order summary

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Navigate to the **Dashboard** tab. | Dashboard loads successfully. |
| 2 | Observe the **Order Summary** section. | Pending, Running, and Completed orders are displayed with correct counts and percentages. |
| 3 | Verify visual indicators. | Progress bars reflect accurate proportions for each order type. |
| 4 | Validate data separation. | Completed orders should be excluded from Pending and Running counts. |

**Actual Result:**  
Completed orders are included in the Pending and Running order counts, causing inaccurate percentage distribution.  

**Status:**  
Fail ❌  

**Post‑conditions:**  
- Order summary displays incorrect data due to overlapping counts.
