# SM-006: Store Management Testing – Remove Phone Number

> **Summary:** Verify that the vendor can successfully remove a phone number from the list.

**Preconditions:**  
- Vendor is logged in.  
- Store settings page is accessible.  
- At least one phone number is listed.

### Scenario 1: Remove phone number

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Navigate to the **Store Settings** page. | Phone number list is displayed with **Remove** options. |
| 2 | Click **Remove** beside a phone number. | System immediately deletes the selected number from the list without confirmation. |
| 3 | Observe the phone number list. | Deleted number disappears instantly without page refresh. |
| 4 | Verify remaining numbers. | Other numbers remain unaffected. |
| 5 |  |  |
| 6 |  |  |

**Actual Result:**  
System successfully removes the selected phone number instantly without confirmation or page refresh.  

**Status:**  
Pass ✅  

**Post‑conditions:**  
- Phone number list updates dynamically.  
- Removed number is no longer visible immediately after deletion.
