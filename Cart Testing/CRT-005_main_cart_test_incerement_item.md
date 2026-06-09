# CRT-005: Main Cart Test - Increment Item Quantity

> **Category:** Cart Management  
> **Summary:** Verify that clicking the inline plus (+) button on a cart item row increases its count value and updates the subtotal.

**Preconditions:**  
- Customer is on the main Cart dashboard page.
- An item row with a baseline quantity value of "2" is displayed.

### Scenario 1

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Click the orange **+** button element once on the item row. | The quantity text count jumps cleanly from "2" to "3". |
| 2 | Observe the item price and store **Subtotal** values. | The prices recalculate instantly to reflect the added item unit cost. |

**Actual Result:**  
The plus button updates the item count data state and updates the subtotal value string in real-time.  

**Status:**  
Pass  

**Post-conditions:**  
- The updated item quantity saves directly to the customer's live cart object.

---