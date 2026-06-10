# SM-001: Store Management Testing – Update Store Logo

> **Summary:** Verify that the vendor can update their store logo using the **Update** button.

**Preconditions:**  
- Vendor is logged in.  
- Store settings page is accessible.  
- Store logo section is visible.

### Scenario 1: Update store logo

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Navigate to the **Store Settings** page. | Store logo section is displayed with current logo and **Update** button. |
| 2 | Click the **Update** button. | System should open file picker to select a new image. |
| 3 | Select a valid image file. | System should preview or upload the new logo. |
| 4 | Save changes. | System should update the store logo successfully. |
| 5 | Refresh the page. | Updated logo should appear in the store profile. |
| 6 |  |  |

**Actual Result:**  
Clicking the image or **Update** button does not initiate the image picker or update process.  

**Status:**  
Failed ❌  

**Post‑conditions:**  
- Store logo remains unchanged.  
- No update process triggered.
