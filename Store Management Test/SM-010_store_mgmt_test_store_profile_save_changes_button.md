# SM-V-010: Store Management Testing – Store Profile Save Changes Button

> **Summary:** Verify that the **Save changes** button successfully updates store profile information and displays a success message.

**Preconditions:**  
- Vendor is logged in.  
- Store profile editing modal is open.  
- Valid changes are made to store information.

### Scenario 1: Save store profile changes

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Navigate to the **Store Profile** section. | Store profile modal is accessible with **Close** and **Save changes** buttons. |
| 2 | Modify store information fields. | Fields accept valid input. |
| 3 | Click **Save changes**. | System validates input and updates store information. |
| 4 | Observe confirmation message. | Success message appears: “✓ Store information updated successfully!” |
| 5 | Verify updated data. | Store profile reflects the saved changes. |
| 6 |  |  |

**Actual Result:**  
System successfully saves the changes and displays a success message confirming the update.  

**Status:**  
Pass ✅  

**Post‑conditions:**  
- Store information is updated and displayed correctly.  
- Success message confirms completion.
