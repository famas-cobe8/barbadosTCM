# SM-003: Store Management Testing – Delivery Option (Pick‑up)

> **Summary:** Verify that the vendor can successfully select **Pick‑up** as the delivery option.

**Preconditions:**  
- Vendor is logged in.  
- Store settings page is accessible.  
- Delivery options section is visible.

### Scenario 1: Select Pick‑up option

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Navigate to the **Store Settings** page. | Delivery options section is displayed. |
| 2 | Click on **Pick‑up** toggle. | System highlights Pick‑up and deselects other options. |
| 3 | Save changes. | System saves Pick‑up as the active delivery method. |
| 4 | Refresh the page. | Pick‑up remains selected. |
| 5 |  |  |
| 6 |  |  |

**Actual Result:**  
System successfully updates and retains Pick‑up selection.  

**Status:**  
Pass ✅  

**Post‑conditions:**  
- Pick‑up is set as the active delivery method.
