# ORM-010: Order Management – Update Order Status Actions

> **Summary:** Verify that the **Order Actions** modal inside the **Running Orders** tab allows the vendor to update the order status correctly.

**Preconditions:**  
- Vendor is logged in.  
- User is in the **Orders menu page**.  
- User is inside the **Running Orders** tab.  
- Order Actions modal is open for a confirmed order.

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Click **Confirmed**. | System retains the current status as “Confirmed.” |
| 2 | Click **Stand By**. | System updates order status to “Stand By.” |
| 3 | Click **Preparing**. | System updates order status to “Preparing.” |
| 4 | Click **Ready for Pickup**. | System updates order status to “Ready for Pickup.” |
| 5 | Verify order list. | Updated status reflects correctly in the **Running Orders** table. |
| 6 | Check if it reflects in display. | System displays success status update displayed. |

**Actual Result:**  
System successfully updates and displays the correct order status for each action.  

**Status:**  
Pass ✅
