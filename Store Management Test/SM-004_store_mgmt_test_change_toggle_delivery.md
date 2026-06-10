# SM-004: Store Management Testing – Delivery Option (Food Delivery)

> **Summary:** Verify that the vendor can successfully select **Food Delivery** as the delivery option.

**Preconditions:**  
- Vendor is logged in.  
- Store settings page is accessible.  
- Delivery options section is visible.

### Scenario 1: Select Food Delivery option

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Navigate to the **Store Settings** page. | Delivery options section is displayed. |
| 2 | Click on **Food Delivery** toggle. | System highlights Food Delivery and deselects other options. |
| 3 | Save changes. | System saves Food Delivery as the active delivery method. |
| 4 | Refresh the page. | Food Delivery remains selected. |
| 5 |  |  |
| 6 |  |  |

**Actual Result:**  
System successfully updates and retains Food Delivery selection.  

**Status:**  
Pass ✅  

**Post‑conditions:**  
- Food Delivery is set as the active delivery method.
