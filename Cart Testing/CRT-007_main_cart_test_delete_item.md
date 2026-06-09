# CRT-007: Main Cart Test - Delete Item via Trash Button

> **Category:** Cart Management  
> **Summary:** Verify that clicking the inline trash icon button removes that specific line-item row entirely from the store's cart block.

**Preconditions:**  
- Customer is viewing a store order block on the main Cart dashboard page.
- A gray trash bin icon button is visible next to the target item's quantity selector controls.

### Scenario 1

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Click the gray **Trash Can** icon button next to the item quantity controls. | The system registers the line-item removal request payload. |
| 2 | Observe the store order card list view. | The specific item row disappears from the cart block layout completely. |
| 3 | Review the store **Subtotal** value string. | The subtotal recalculates or updates to reflect the total removal of that product's cost. |

**Actual Result:**  
The trash button deletes individual item strings cleanly from the interface and updates the layout container.  

**Status:**  
Pass  

**Post-conditions:**  
- The targeted line-item data row is completely purged from the customer session shopping basket.