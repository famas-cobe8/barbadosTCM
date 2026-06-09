# SL-008: Shop Layout Testing - Menu Search Spaces and Typos

> **Category:** Shop Layout & Menu Interaction  
> **Summary:** Verify that the "Search in menu" input handles misplaced spaces and nonsensical typos gracefully by denying false results and displaying a clean empty state.

**Preconditions:**  
- Customer is viewing a specific store catalog page with items populated.

### Scenario 1: Misplaced Spaces

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Click into the "Search in menu" bar. | Field gains focus and text cursor appears. |
| 2 | Enter a valid menu keyword with broken, misplaced padding (e.g., "B r e a k   f a s t"). | Field accepts the spacing pattern characters. |
| 3 | Observe the menu catalog layout below. | System ignores the broken string layout and securely shifts to a zero-results view. |
| 4 | Review the catalog area message. | A clean "No items match your search" indicator displays. |

### Scenario 2: Invalid Typos

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Clear the search field completely. | Field empties and returns to the initial state placeholder text. |
| 2 | Type a completely invalid, nonsensical typo string (e.g., "wvxqzj"). | Field accurately records the typed character keys. |
| 3 | Observe the menu catalog layout below. | System denies matching any active inventory rows instantly. |
| 4 | Review the catalog area message. | A clean "No items match your search" indicator displays. |

**Actual Result:**  
The menu search bar parses broken spacing formats and typo strings cleanly, successfully denying incorrect inventory matches while presenting a secure empty-state message.  

**Status:**  
Pass  

**Post-conditions:**  
- No script termination errors, broken UI frames, or memory leak anomalies occur.
- The user can clear the text entry window to immediately restore view stability over the catalog.
