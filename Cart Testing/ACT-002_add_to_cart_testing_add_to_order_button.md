# ATC-002: Add to Cart Testing - Commit to Order Button

> **Category:** Cart Management  
> **Summary:** Verify that clicking the "Add to Order" button successfully submits the configured item payload, saves it to the cart, and automatically closes the popup window.

**Preconditions:**  
- The item customization popup window is open with a valid selected item state active.

### Scenario 1

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Configure desired item parameters (e.g., quantity value set to "1"). | Subtotal displays the accurate total price value of "₱74.00". |
| 2 | Click the primary orange **Add to Order - ₱74.00** button component. | System processes the basket insertion operation event cleanly. |
| 3 | Monitor the immediate visibility changes of the modal popup layer. | The customization popup window closes and un-dims the screen instantly. |
| 4 | Inspect the persistent persistent cart tracker utility on the main storefront view. | Cart updates with the newly committed item block details. |

**Actual Result:**  
The main button interaction commits the current item and quantity to the cart tracking system data structure smoothly while clearing away the popup window.  

**Status:**  
Pass  

**Post-conditions:**  
- Cart state reflects the added items with persistent price accumulations active.
- Underlying storefront browsing controls return to a fully clickable state.
