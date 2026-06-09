# SL-005: Shop Layout Testing - Select Menu Category Tab

> **Category:** Shop Layout & Menu Interaction  
> **Summary:** Verify that clicking an unselected menu category chip updates the view to jump or filter to that specific category section.

**Preconditions:**  
- Customer is viewing the storefront menu layout.
- Category pills (e.g., "Beverages", "Breakfast") are visible.

### Scenario 1

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Locate and click on the **Beverages** category pill. | Pill changes color state from white to active orange theme. |
| 2 | Observe the active category state change. | The default **All** category chip turns white (inactive state). |
| 3 | Check the vertical catalog list contents. | Screen auto-scrolls or filters to exclusively reveal the "Beverages" catalog. |

**Actual Result:**  
Active states switch smoothly upon selecting a category tab, accurately adjusting catalog layouts.  

**Status:**  
Pass  

**Post-conditions:**  
- Selected category tab stays highlighted until another selection event fires.

---

