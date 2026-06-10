# NT-V-001: Notification Test – Variation of Notification Type and Icon

> **Summary:** Verify that different notification types display distinct icons and messages correctly when vendor is logged in.

**Preconditions:**  
- Vendor is logged in.  
- Notifications exist for new orders, cancelled orders, new messages from customers, and completed orders.

### Scenario 1: Display notification types

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Click the **Alert (bell)** icon. | Notification popup appears showing various notification types. |
| 2 | Observe each notification entry. | Each type displays a unique icon (e.g., shopping bag for new orders, cross mark for cancelled orders, chat bubble for new messages, check mark for completed orders). |
| 3 | Verify message content and timestamp. | Text and time are displayed correctly for each notification. |

**Actual Result:**  
System displays distinct icons and messages for each notification type.  

**Status:**  
Pass ✅  

**Post‑conditions:**  
- Notification types are visually differentiated and readable.
