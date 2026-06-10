# ORM-009: Order Management – Decline Order Action

> **Summary:** Verify that the **Decline Order** button correctly rejects the order request.

**Preconditions:**  
- Vendor is logged in.  
- User is in the **Orders menu page**.
- User is in the **Order Requests** tab.  
- Order Actions modal is open for a pending order.

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Click the **Decline Order** button. | System rejects the order and updates its status to “Cancelled.” |
| 2 | Verify order list. | Declined order is removed from **Order Requests** tab. |
| 3 | Check confirmation message. | System displays success feedback (e.g., “Order declined successfully”). |

**Actual Result:**  
System successfully declines the order and updates its status to “Cancelled.”  

**Status:**  
Pass ✅
