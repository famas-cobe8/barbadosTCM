# DB-005: Dashboard Test – Order Section

> **Summary:** Verify that the dashboard correctly displays all order sections — **Order Requests**, **Running Orders**, and **Order History** — with accurate details and statuses.

**Preconditions:**  
- Vendor is logged in.  
- Orders exist in different statuses: Pending, Confirmed, and Completed.

---

### Scenario 1: Order Requests (Pending Orders)

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Navigate to the **Dashboard** tab. | Dashboard loads successfully. |
| 2 | Observe the **Order Requests** section. | Pending orders are displayed with customer name, order ID, date, amount, and status. |
| 3 | Verify status indicator. | Status label “Pending” is displayed correctly in yellow. |

**Actual Result:**  
System correctly displays pending orders with accurate details and status indicators.  

**Status:**  
Pass ✅  

**Post‑conditions:**  
- Pending orders reflect real-time data and are visually distinguishable.
---

### Scenario 2: Running Orders (Confirmed Orders)

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Navigate to the **Dashboard** tab. | Dashboard loads successfully. |
| 2 | Observe the **Running Orders** section. | Confirmed orders are displayed with customer name, order ID, date, amount, and status. |
| 3 | Verify status indicator. | Status label “Confirmed” is displayed correctly in blue. |

**Actual Result:**  
System correctly displays confirmed orders with accurate details and status indicators.  

**Status:**  
Pass ✅  

**Post‑conditions:**  
- Running orders reflect real-time confirmed transactions.
---

### Scenario 3: Order History (Completed Orders)

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Navigate to the **Dashboard** tab. | Dashboard loads successfully. |
| 2 | Observe the **Order History** section. | Completed orders are displayed with customer name, order ID, date, amount, and status. |
| 3 | Verify status indicator. | Status label “Completed” is displayed correctly in green. |
| 4 |  | |

**Actual Result:**  
Completed orders are displayed correctly.  

**Status:**  
Pass ✅   

**Post‑conditions:**  
- Completed orders appear correctly but are not properly excluded from other order categories.
