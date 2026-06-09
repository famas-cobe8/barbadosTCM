# SL-010: Shop Layout Testing - Item Add Button

> **Category:** Shop Layout & Menu Interaction  
> **Summary:** Verify that clicking the add button on a food item card successfully opens the item customization popup window.

**Preconditions:**  
- Customer is on the store catalog page under a specific section (e.g., "Beverages").
- At least one item card (e.g., "Lone Star 12 oz.") with an active orange **+** button is visible.

### Scenario 1

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Locate the target item card and click the orange **+** button element. | System registers the click action and triggers the modal overlay event. |
| 2 | Observe the main viewport transition. | A modal popup window transitions into view smoothly over the shop layout. |
| 3 | Inspect the content components inside the popup window. | The item name, pricing, description, and available choice modifiers render completely. |

**Actual Result:**  
The orange add button responds immediately, triggering the item customization popup window flawlessly.  

**Status:**  
Pass  

**Post-conditions:**  
- Main storefront interaction is temporarily locked behind the active modal overlay layer.
- Selection modifiers inside the popup are active and ready for data inputs.
