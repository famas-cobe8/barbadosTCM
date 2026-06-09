# CRT-003: Main Cart Test - Checkout All Store Items

> **Category:** Cart Management  
> **Summary:** Verify that clicking the Checkout button forces all items under the selected store into the order flow without leaving any behind.

**Preconditions:**  
- Customer has checked a store-level checkbox (e.g., "Coby's").
- The global **Checkout** button is visible and active.

### Scenario 1

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Click the active orange **Checkout** button. | The system registers the click event and packages the active store parameters. |
| 2 | Monitor the transit payload or checkout transition screen. | All items belonging to that store are pushed to checkout simultaneously; no line-items can be excluded. |

**Actual Result:**  
The checkout button enforces an all-or-nothing action, routing every item under the selected store into the transaction sequence together.  

**Status:**  
Pass  

**Post-conditions:**  
- The checkout screen launches with the complete store bundle summary and matching price totals.

---
