# SM-009: Store Management Testing – Store Profile Close Button

> **Summary:** Verify that the **Close** button successfully exits the store profile editing modal without saving changes.

**Preconditions:**  
- Vendor is logged in.  
- Store profile editing modal is open.  
- Unsaved changes may exist.

### Scenario 1: Close store profile modal

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Navigate to the **Store Profile** section. | Store profile modal is accessible with **Close** and **Save changes** buttons. |
| 2 | Click the **Close** button. | Modal closes immediately without saving any unsaved changes. |
| 3 | Verify store profile data. | Original information remains unchanged. |
| 4 | Reopen the modal. | Previous unsaved edits are not retained. |
| 5 |  |  |
| 6 |  |  |

**Actual Result:**  
System successfully closes the modal without saving changes.  

**Status:**  
Pass ✅  

**Post‑conditions:**  
- Store profile remains unchanged.  
- Modal closes smoothly.
