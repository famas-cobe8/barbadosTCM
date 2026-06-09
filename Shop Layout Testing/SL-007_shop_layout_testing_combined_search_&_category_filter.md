# SL-007: Shop Layout Testing - Combined Search and Category Filters

> **Category:** Shop Layout & Menu Interaction (Hidden/Edge Case)  
> **Summary:** Verify that applying a category filter tab simultaneously restricts search keyword filtering to items inside that active category group.

**Preconditions:**  
- Customer has selected the **Beverages** filter chip category.

### Scenario 1

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Click into the "Search in menu" field while "Beverages" is active. | Bar gains focus. |
| 2 | Type a generic item string matching food items (e.g., "Sandwich"). | Field records input characters. |
| 3 | Inspect the menu list catalog output view screen. | Catalog returns an empty-state list because "Sandwich" is not in "Beverages". |

**Actual Result:**  
Intersection of multiple search parameters applies parameters collectively, refining items accurately.  

**Status:**  
Pass  

**Post-conditions:**  
- Clearing the search string restores the broad "Beverages" list view without resetting chips.