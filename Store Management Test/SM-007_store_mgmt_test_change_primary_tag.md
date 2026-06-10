# SM-007: Store Management Testing – Primary Tag Functionality

> **Summary:** Verify that the vendor can set a phone number as **Primary** and that the tag does not duplicate.

**Preconditions:**  
- Vendor is logged in.  
- Store settings page is accessible.  
- Multiple phone numbers exist.

### Scenario 1: Set primary phone number

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Navigate to the **Store Settings** page. | Phone number list is displayed with **Primary** tags. |
| 2 | Click **Primary** beside a phone number. | System marks the selected number as primary. |
| 3 | Verify other numbers. | Only one number has the **Primary** tag. |
| 4 | Refresh the page. | Primary tag remains correctly assigned. |
| 5 |  |  |
| 6 |  |  |

**Actual Result:**  
System correctly assigns the **Primary** tag to one number and prevents duplication.  

**Status:**  
Pass ✅  

**Post‑conditions:**  
- Only one phone number is marked as primary.  
- Primary tag persists after refresh.
