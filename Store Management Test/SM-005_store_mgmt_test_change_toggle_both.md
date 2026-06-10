# SM-005: Store Management Testing – Delivery Option (Both)

> **Summary:** Verify that the vendor can successfully select **Both** as the delivery option.

**Preconditions:**  
- Vendor is logged in.  
- Store settings page is accessible.  
- Delivery options section is visible.

### Scenario 1: Select Both option

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Navigate to the **Store Settings** page. | Delivery options section is displayed. |
| 2 | Click on **Both** toggle. | System highlights Both and deselects other options. |
| 3 | Save changes. | System saves Both as the active delivery method. |
| 4 | Refresh the page. | Both remains selected. |
| 5 |  |  |
| 6 |  |  |

**Actual Result:**  
System successfully updates and retains Both selection.  

**Status:**  
Pass ✅  

**Post‑conditions:**  
- Both Pick‑up and Food Delivery are enabled for the store.
