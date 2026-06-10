# SM-002: Store Management Testing – Delete Store Logo

> **Summary:** Verify that the vendor can remove their store logo using the **Delete** button.

**Preconditions:**  
- Vendor is logged in.  
- Store settings page is accessible.  
- Store logo section is visible.

### Scenario 1: Delete store logo

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Navigate to the **Store Settings** page. | Store logo section is displayed with current logo and **Delete** button. |
| 2 | Click the **Delete** button. | System should prompt confirmation before removing the logo. |
| 3 | Confirm removal. | System should remove the logo and display a placeholder image. |
| 4 | Refresh the page. | Placeholder or default logo should appear. |
| 5 |  |  |
| 6 |  |  |

**Actual Result:**  
Clicking the **Delete** button does not remove the logo or trigger any confirmation prompt.  

**Status:**  
Failed ❌  

**Post‑conditions:**  
- Store logo remains visible.  
- No removal process executed.
