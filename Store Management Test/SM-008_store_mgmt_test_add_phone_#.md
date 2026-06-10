# SM-008: Store Management Testing – Add Phone Number

> **Summary:** Verify that the vendor can successfully add a new phone number and that a form space appears upon clicking **Add phone number** when more than one number exists.

**Preconditions:**  
- Vendor is logged in.  
- Store settings page is accessible.  
- At least one phone number is already listed.

### Scenario 1: Add phone number

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Navigate to the **Store Settings** page. | Phone number list is displayed with **Add phone number** option. |
| 2 | Click **Add phone number**. | System creates a new input field for entering another number. |
| 3 | Enter a valid phone number. | Field accepts input correctly. |
| 4 | Save changes. | System adds the new number to the list. |
| 5 | Refresh the page. | Newly added number appears in the list. |
| 6 |  |  |

**Actual Result:**  
System successfully adds a new phone number and displays a new form space upon clicking **Add phone number**.  

**Status:**  
Pass ✅  

**Post‑conditions:**  
- New phone number is added and visible.  
- Form dynamically expands when adding multiple numbers.
