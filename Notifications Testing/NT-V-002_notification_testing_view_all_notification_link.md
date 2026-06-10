# NT-V-002: Notification Test – View All Notifications Link

> **Summary:** Verify that the **View all notifications** link redirects correctly to the full notification page when vendor is logged in.

**Preconditions:**  
- Vendor is logged in.  
- Notifications exist for new orders, cancelled orders, new messages from customers, and completed orders.  
- Notification popup is open.

### Scenario 1: Click “View all notifications”

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Click the **Alert (bell)** icon. | Notification popup appears. |
| 2 | Scroll to the bottom of the popup. | “View all notifications” link is visible. |
| 3 | Click the link. | System should redirect to the full notification page. |
| 4 | Verify redirection. | Page fails to load or does not redirect properly. |

**Actual Result:**  
Clicking the link does not redirect to the full notification page.  

**Status:**  
Fail ❌  

**Post‑conditions:**  
- No redirection occurs; vendor remains on the same page.
