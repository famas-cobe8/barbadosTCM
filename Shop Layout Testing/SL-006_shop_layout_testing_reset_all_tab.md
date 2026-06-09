# SL-006: Shop Layout Testing - Reset Filters with All Tab

> **Category:** Shop Layout & Menu Interaction  
> **Summary:** Verify that selecting the "All" category chip clears individual category restrictions to re-display the entire menu catalog.

**Preconditions:**  
- Customer has an active specific category filter applied (e.g., "Breakfast" is currently active).

### Scenario 1

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Click on the highlighted **All** category button chip. | The "All" chip changes to its highlighted active orange state. |
| 2 | Observe the previously selected category chip status. | The "Breakfast" chip returns to its default unselected white layout. |
| 3 | Review the vertical menu feed items layout. | The complete store menu listing scales back to show all item types. |

**Actual Result:**  
Selecting the baseline option resets item filtering parameters to instantly refresh the full category array.  

**Status:**  
Pass  

**Post-conditions:**  
- Complete store inventory categories list displays down the screen container block.

---
