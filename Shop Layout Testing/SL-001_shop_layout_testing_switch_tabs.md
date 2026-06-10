# SL-001: Shop Layout Testing - Switch Tabs

> **Category:** Shop Layout & Menu Interaction  
> **Summary:** Verify that a customer can toggle between the menu catalog and the customer feedback views using the "Shop" and "Reviews" buttons.

**Preconditions:**  
- Customer has opened a specific shop's page.
- The navigation buttons are visible.

### Scenario 1: Switch to Reviews Tab

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Click the **Reviews** button. | The button becomes highlighted; reviews load. |
| 2 | Observe the main content area. | The menu catalog hides, and customer reviews display. |

### Scenario 2: Switch to Shop Tab

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Click the **Shop** button. | The button highlights in orange; reviews hide. |
| 2 | Observe the main content area. | The menu categories and food item cards re-display. |

**Actual Result:**  
The application shifts view contexts cleanly between the menu catalog and the review panels without page refreshes.  

**Status:**  
Pass  

**Post-conditions:**  
- Selected tab remains active until another button is clicked.

---

