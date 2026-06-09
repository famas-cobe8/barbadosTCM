# BRS-003: Browse Shops Testing - Search by Name

> **Summary:** Ensure that customer users are redirected to the home page after login and can view the complete list of all available shops.

**Preconditions:**  
- User has a valid customer account.  
- User is logged in successfully.  
- Shops are already registered in the system database.

### Scenario 1: Search by name on home page

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | User enters a keyword (e.g., shop name) in the search bar on the home page. | System filters and displays matching shops. |
| 2 | User clears the search input. | Full list of shops is restored. |

**Actual Result:**  
Search filtering work correctly; full list not restored when cleared.  

**Status:**  
failed  

**Post-conditions:**  
- User can refine browsing using search.  
- No data loss occurs when clearing search.  
