# BRS-006: Browse Shop Testing - View Shop

> **Summary:** Verify that a customer can successfully transition to a shop's store catalog page upon clicking or tapping its display card from the feed or search results.

**Preconditions:**  
- Customer is on a page displaying shop listing cards (e.g., Home Feed, Search Results, or Favorites).
- The target shop is currently active, open, and accepting orders.

### Scenario 1

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Locate the target shop card on the current discovery screen. | Shop metadata (name, rating, delivery time, banner image) displays correctly. |
| 2 | Click or tap anywhere on the active shop card element. | System registers the click event and initiates the page transition. |
| 3 | Monitor the loading state of the application. | System fetches the real-time menu catalog and store configurations via API. |
| 4 | Verify the landing page after the transition completes. | UI successfully transitions to the store catalog page without layout breaks. |
| 5 | | S|

**Actual Result:**  
The application smoothly executes the page transition to the store catalog page, displaying the complete menu and layout instantly upon user selection.  

**Status:**  
Pass  

**Post-conditions:**  
- Store catalog categories and items are interactive and ready for cart addition.
- Back-navigation tracking correctly preserves the previous feed state.
