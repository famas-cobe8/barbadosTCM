# CAT-009: Catalog Management – Search Bar Functionality

> **Summary:** Verify that the search bar correctly filters products based on user input.

**Preconditions:**  
- Vendor is logged in.  
- Catalog page is accessible.  
- Products exist in multiple categories.

### Scenario 1: Search by exact product name
| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Enter full product name in search bar. | Matching product appears immediately. |

### Scenario 2: Search by partial product name
| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Enter partial product name. | System displays all products containing the entered text. |

### Scenario 3: Search by category keyword
| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Enter category name (e.g., “Breakfast”). | System lists products under that category. |

### Scenario 4: Search with no matching results
| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Enter a non-existent keyword. | System displays “No results found.” message. |

### Scenario 5: Clear search input
| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Clear the search bar. | Full product list is restored. |

**Actual Result:**  
Search bar filters and restores product list accurately.  

**Status:**  
Pass ✅
