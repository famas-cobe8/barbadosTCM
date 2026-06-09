# SL-004: Shop Layout Testing - Filter Menu via Search Bar

> **Category:** Shop Layout & Menu Interaction  
> **Summary:** Verify that a customer can successfully filter items inside a shop's menu using keywords in the "Search in menu" input field.

**Preconditions:**  
- Customer is on a specific store catalog page with items populated.

### Scenario 1

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Click into the "Search in menu" input field. | Search bar gains focus and showing text cursor. |
| 2 | Enter a valid menu item name (e.g., "Coffee"). | Field accepts the input text. |
| 3 | Observe the menu catalog below real-time. | Catalog filters instantly to match items with the string "Coffee". |

**Actual Result:**  
Menu item feed filters instantly and dynamically according to the user input string.  

**Status:**  
Pass  

**Post-conditions:**  
- Only matching menu item cards remain visible in the shop listing.

---


