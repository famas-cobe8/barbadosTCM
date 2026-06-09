# ATC-001: Add to Cart Testing - Quantity Increment and Decrement

> **Summary:** Verify that clicking the plus (+) and minus (-) buttons updates the item quantity and recalculates subtotals correctly, ensuring the quantity never drops below one.

**Preconditions:**  
- The add item customization popup window is actively displayed on the screen.
- Initial item quantity is set to its baseline value of "1".

### Scenario 1: Increment Quantity

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Click the orange **+** button element once. | Quantity text value changes from "1" to "2". |
| 2 | Observe the **Subtotal** monetary label value. | Price updates instantly from "₱74.00" to "₱148.00". |
| 3 | Observe the **Add to Order** button text value. | Button price updates instantly to match the new subtotal value. |

### Scenario 2: Decrement Quantity with Baseline Clamp Check

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | While the quantity displays "2", click the **-** button element once. | Quantity decreases cleanly from "2" back to "1". |
| 2 | Confirm that the subtotal and main button values revert accurately to "₱74.00". | Pricing blocks update dynamically to reflect the single-item baseline cost. |
| 3 | Click the **-** button element again while the quantity displays "1". | System blocks the decrease; quantity remains locked at a value of "1". |
| 4 | Check for any graphical or logical errors in the interaction window. | The item count cannot fall below one; minus button may visually change to a disabled state. |

**Actual Result:**  
The calculation counter increases and decreases smoothly while strictly clamping the quantity value to prevent it from ever dropping lower than one.  

**Status:**  
Pass  

**Post-conditions:**  
- Configured item values are ready for commitment to the cart object.

---
