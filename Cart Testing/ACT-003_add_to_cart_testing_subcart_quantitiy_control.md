# ATC-003: Add to Cart Testing - Subcart Quantity Controls

> **Category:** Cart Management  
> **Summary:** Verify that changing item quantities directly within the store's inline subcart accurately updates item counts, subtotals, and overall delivery totals.

**Preconditions:**  
- Customer has added an item to their order and the inline subcart section is visible on screen.

### Scenario 1: Inline Quantity Increment

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Click the gray **+** button next to the item quantity. | The quantity text shifts from "2" to "3". |
| 2 | Observe the item price and **Subtotal (3 items)** values. | Subtotal recalculates instantly based on unit item costs. |
| 3 | Verify the **Total** price and **Place Order** button label. | Both price aggregates update seamlessly to include the delivery fee. |

### Scenario 2: Inline Quantity Decrement

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Click the gray **-** button next to the item quantity. | The quantity text shifts from "2" down to "1". |
| 2 | Review the overall bill values displayed on the card layout. | Subtotal, Delivery fee, and final Total values scale downward dynamically. |

**Actual Result:**  
The inline subcart counter adjustments refresh the line-item balances and final receipt sums in real-time.  

**Status:**  
Pass  

**Post-conditions:**  
- Modified order values persist seamlessly across active checkout states.

---
