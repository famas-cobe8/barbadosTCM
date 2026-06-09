# SL-009: Shop Layout Testing - Restore Menu List on Clear

> **Category:** Shop Layout & Menu Interaction  
> **Summary:** Verify that clearing the "Search in menu" bar text successfully resets all filters and restores the complete, original food item catalog list.

**Preconditions:**  
- Customer has executed an active search query in the menu search bar.
- The menu catalog is currently displaying a filtered subset of items.

### Scenario 1

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Click the clear inline **X** icon button inside the menu search bar (or manually backspace all characters). | The typed keyword string is instantly removed from the text container field. |
| 2 | Observe the search input container state. | Field immediately returns to its blank "Search in menu" placeholder prompt text. |
| 3 | Monitor the menu catalog listing area below. | System triggers a view update or cache pull to reload the base data array. |
| 4 | Verify the displayed item cards on the screen. | The full, unfiltered menu directory catalog and all food categories restore completely. |

**Actual Result:**  
Wiping the menu search text parameters safely resets the view, cleanly restoring the original, complete storefront catalog listing.  

**Status:**  
Pass  

**Post-conditions:**  
- All menu item cards and category headers are interactive and fully accessible to the customer.
