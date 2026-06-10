# CAT-001: Catalog Management Testing – Add New Category

> **Summary:** Verify that the vendor can successfully add a new category through the **Add Category** button and modal form.

**Preconditions:**  
- Vendor is logged in.  
- Catalog page is accessible.  
- “Add Category” button is visible.

### Scenario 1: Add new category

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Navigate to the **Catalog** page. | Catalog management interface loads successfully. |
| 2 | Click the **Add Category** button. | System opens the **Add New Category** modal. |
| 3 | Enter a category name (e.g., “Illegal”). | Input field accepts text correctly. |
| 4 | Click **Add Category**. | System validates input and triggers a success notification event. |
| 5 | Observe the top of the interface layout view. | A green toast notification text banner reading "✓ Category added" appears cleanly. |
| 6 | Verify category list. | Newly added category appears in the list with correct name and formatting. |

**Actual Result:**  
System successfully adds the new category, renders the green "✓ Category added" toast notification message, and updates the list.  

**Status:**  
Pass ✅  

**Post‑conditions:**  
- New category is stored and visible in the catalog list.
- Success toast notification message auto-dismisses or disappears after its set duration rules.
