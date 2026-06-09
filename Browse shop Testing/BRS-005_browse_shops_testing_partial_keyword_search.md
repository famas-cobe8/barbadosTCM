# BRS-005: Browse Shops Testing - partial name keyword in search bar

> **Summary:** Ensure that the discovery search engine can successfully match, resolve, and display relevant shops when a customer inputs only a partial keyword or substring of the shop's name.

**Preconditions:**  
- At least one active shop exists in the platform database containing the partial string in its title (e.g., "cob" for a shop named "Coby's").
- The customer is on the home feed or discovery dashboard.

### Scenario 1

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Tap on the primary search bar container on the home screen. | Search input field gains focus and the keyboard opens. |
| 2 | Enter a valid partial name keyword (e.g., "cob"). | Text field accepts the input; auto-suggestions or matching terms may populate. |
| 3 | Type the partial search query. | System transmits the partial string payload to the search index backend. |
| 4 | Review the displayed results listing on the search results screen. | System surfaces all active shops containing the substring "cob" sorted by relevance or proximity. |
| 5 | | |

**Actual Result:**  
Search engine processes the partial string query accurately, returns the correct matching shop profiles, and allows seamless redirection to the menu view.  

**Status:**  
Pass  

**Post-conditions:**  
- Shop menu items and categories render completely.
- Search filters remain applicable to the active search state.
