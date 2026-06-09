# CRT-001: Mian Cart Test - Store Checkbox Selection

> **Category:** Cart Management  
> **Summary:** Verify that checking the store-level checkbox highlights the entire store block and selects all items under that store.

**Preconditions:**  
- Customer is on the main Cart dashboard page.
- At least one store order card (e.g., "Coby's") containing items is displayed.

### Scenario 1

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Click the empty checkbox icon in the top-right corner of the store header. | The checkbox changes to a filled orange checked state. |
| 2 | Observe the item rows bundled inside the store card. | All items under the store are visually highlighted as selected for checkout. |

**Actual Result:**  
The store checkbox selects the entire store block and bundles all items together instantly.  

**Status:**  
Pass  

**Post-conditions:**  
- The chosen store's entire cart dataset is marked as ready for checkout processing.

---

