# NT-004: Notification Testing - Non-clickable Alert Elements

> **Summary:** Ensure that static UI components within the active notifications layout (like card tiles or text descriptions) do not respond to click actions or trigger unintended page redirects.

**Preconditions:**  
- Customer is viewing the notification panel listing active items (e.g., "Out for Delivery", "Order Confirmed").

### Scenario 1

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Hover over or click directly on the text or body of an individual notification row element. | The cursor does not change to a pointer style, and clicking yields no screen updates. |
| 2 | Click on the unread status indicator block (the orange dot component). | The element behaves as a static asset, keeping the dot visible without firing routing side-effects. |
| 3 | Observe the application state after performing these click entries. | The view remains firmly fixed on the notifications dropdown, proving text components are static. |

**Actual Result:**  
Static card elements cleanly ignore hover changes or click events without generating unintended navigation sequences or UI glitches.  

**Status:**  
Pass  

**Post-conditions:**  
- The notifications view context remains stable and completely uninterrupted for the customer.
