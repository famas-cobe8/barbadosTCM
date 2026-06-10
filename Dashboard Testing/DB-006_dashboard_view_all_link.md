# DB-006: Dashboard Test – View All Link Functionality

> **Summary:** Verify that the **View all** link in each order section redirects correctly to the full list of corresponding orders.

**Preconditions:**  
- Vendor is logged in.  
- Orders exist in different statuses: Pending, Confirmed, and Completed.  
- Dashboard is accessible.

### Scenario 1: View All Link Redirection

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Navigate to the **Dashboard** tab. | Dashboard loads successfully. |
| 2 | Click **View all** link in **Order Requests** section. | System redirects to the full list of pending orders. |
| 3 | Click **View all** link in **Running Orders** section. | System redirects to the full list of confirmed orders. |
| 4 | Click **View all** link in **Order History** section. | System redirects to the full list of completed orders. |
| 5 | Verify page content. | Each redirected page displays the correct corresponding order list. |

**Actual Result:**  
System successfully redirects to the correct order lists for each section.  

**Status:**  
Pass ✅  

**Post‑conditions:**  
- “View all” links function correctly and lead to their respective order pages.
