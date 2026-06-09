# CRT-002: Main Cart Test - Checkout Button Activation

> **Category:** Cart Management  
> **Summary:** Verify that the global Checkout button becomes visible and active only after selecting a store checkbox.

**Preconditions:**  
- Customer is on the main Cart dashboard with no store checkbox selected.
- The global "Checkout" button is missing or unclickable.

### Scenario 1

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Click the store-level checkbox icon for a store card. | The store checkbox shifts to an active checked state. |
| 2 | Observe the top right corner of the cart layout view. | The orange **Checkout** button appears and becomes fully clickable. |

**Actual Result:**  
The global Checkout button activates successfully only when a store selection dependency is met.  

**Status:**  
Pass  

**Post-conditions:**  
- The Checkout action button remains active as long as at least one store is checked.

---


