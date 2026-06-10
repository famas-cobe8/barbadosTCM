# NT-V-003: Notification Test – Refresh Button

> **Summary:** Verify that the **Refresh** button updates the notification list correctly when vendor is logged in.

**Preconditions:**  
- Vendor is logged in.  
- Notifications exist for new orders, cancelled orders, new messages from customers, and completed orders.  
- Notification popup is open.

### Scenario 1: Refresh notifications

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Click the **Alert (bell)** icon. | Notification popup appears. |
| 2 | Click the **Refresh** button. | System reloads the notification list. |
| 3 | Observe the list. | New notifications appear if available; timestamps update accordingly. |

**Actual Result:**  
System successfully refreshes and updates the notification list.  

**Status:**  
Pass ✅  

**Post‑conditions:**  
- Notification list reflects the latest updates.
