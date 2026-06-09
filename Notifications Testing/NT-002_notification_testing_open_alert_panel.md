# NT-002: Notification Testing - Open Alerts Panel

> **Category:** Shop Layout & Menu Interaction  
> **Summary:** Verify that clicking the notification bell icon button successfully opens the shop alerts or notification panel.

**Preconditions:**  
- Customer has opened a specific shop's page.
- The red notification bell icon button is visible in the layout header.

### Scenario 1

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Click the red **Notification Bell** button in the header. | The system registers the click event action. |
| 2 | Observe the interface transition behavior. | A notifications drawer, dropdown, or dedicated modal slides into view. |
| 3 | Verify the displayed list components. | The interface renders recent shop-specific alerts, promotional announcements, or order updates completely. |

**Actual Result:**  
The notification button responds instantly, rendering the store notifications container over the current view smoothly.  

**Status:**  
Pass  

**Post-conditions:**  
- The notifications list remains interactive until closed or dismissed by the user.

---
