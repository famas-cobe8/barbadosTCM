# ORM-008: Order Management – Process Order Action

> **Summary:** Verify that the **Process Order** button correctly accepts and starts processing the order.

**Preconditions:**  
- Vendor is logged in.  
- User is in the **Orders menu page**
- User is in the **Order Requests** tab.  
- Order Actions modal is open for a pending order.

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Click the **Process Order** button. | System accepts the order and updates its status to “Confirmed.” |
| 2 | Verify order list. | Order moves from **Order Requests** to **Running Orders** tab. |
| 3 | Check confirmation message. | System displays success feedback (e.g., “Order processed successfully”). |

**Actual Result:**  
System successfully processes the order and updates its status to “Confirmed.”  

**Status:**  
Pass ✅
