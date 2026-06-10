# NT-V-004: Notification Test – Scroll Through Notifications

> **Summary:** Verify that the vendor can scroll through the notification list smoothly.

**Preconditions:**  
- Vendor is logged in.  
- Notifications exist for new orders, cancelled orders, new messages from customers, and completed orders.  
- Notification popup contains multiple notifications.

### Scenario 1: Scroll through notifications

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Click the **Alert (bell)** icon. | Notification popup appears. |
| 2 | Scroll down through the list. | System displays older notifications without lag or cutoff. |
| 3 | Scroll back up. | System displays newer notifications correctly. |

**Actual Result:**  
System allows smooth scrolling through all notifications.  

**Status:**  
Pass ✅  

**Post‑conditions:**  
- All notifications are accessible through scrolling.
