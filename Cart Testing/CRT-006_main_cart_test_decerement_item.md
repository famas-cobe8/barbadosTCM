# CRT-006: Main Cart Test - Decrement Item Quantity

> **Category:** Cart Management  
> **Summary:** Verify that clicking the inline minus (-) button on a cart item row decreases its count value and updates the subtotal.

**Preconditions:**  
- Customer is on the main Cart dashboard page.
- An item row with an active quantity value of "2" is displayed.

### Scenario 1

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Click the gray **-** button element once on the item row. | The quantity text count drops cleanly from "2" down to "1". |
| 2 | Observe the item price and store **Subtotal** values. | The prices scale downward instantly to match the single item unit cost. |

**Actual Result:**  
The minus button reduces the counter accurately and adjusts all receipt subtotal balances dynamically.  

**Status:**  
Pass  

**Post-conditions:**  
- The reduced item count persists accurately inside the session basket database rows.

---