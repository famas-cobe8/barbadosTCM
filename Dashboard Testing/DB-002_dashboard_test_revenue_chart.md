# DB-002: Dashboard Test – Monthly Revenue Chart

> **Summary:** Verify that the **Monthly Revenue** chart displays accurate daily breakdown and total revenue.

**Preconditions:**  
- Vendor is logged in.  
- Revenue data exists for the selected month.

### Scenario 1: View monthly revenue chart

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Navigate to the **Dashboard** tab. | Dashboard loads successfully. |
| 2 | Observe the **Monthly Revenue** section. | Chart displays daily revenue breakdown for the selected month. |
| 3 | Hover over a data point. | Tooltip shows correct day and revenue value. |
| 4 | Verify total revenue. | Total revenue matches the sum of daily entries. |

**Actual Result:**  
System accurately displays daily revenue breakdown and total monthly revenue.  

**Status:**  
Pass ✅  

**Post‑conditions:**  
- Revenue chart updates dynamically based on selected month.
