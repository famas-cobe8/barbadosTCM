# BRS-008: Browse Shop Testing - Verify shop average rating displays correctly on storefront

> **Summary:** Validate that the shop's average user rating aggregate matches and displays correctly on the store catalog header interface.

**Preconditions:**  
- Customer has successfully navigated to the specific shop's store catalog page.
- The shop has existing user reviews and a calculated average score on the backend database.

### Scenario 1

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Locate the rating component near the shop title header. | Rating block element renders completely without overlapping text. |
| 2 | Check the numerical rating text value (e.g., "4.7"). | The numeric score displays accurately to one decimal place. |
| 3 | Inspect the accompanying star iconography or visual indicator. | Star graphics or colors load correctly adjacent to the text. |
| 4 | Compare the UI rating value against the store value in the database. | The displayed value matches the active database system record exactly. |

**Actual Result:**  
The average rating value and star iconography render cleanly in the header and reflect the correct system calculated score.  

**Status:**  
Pass  

**Post-conditions:**  
- The accurate customer satisfaction metric remains visible to the user browsing the menu.
