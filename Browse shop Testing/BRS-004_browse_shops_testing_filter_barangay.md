# BRS-004: Browse Shops Testing - Filter by Barangay

> **Summary:** Ensure that users can filter the list of shops by barangay and view only those located in the selected area.

**Preconditions:**  
- User has a valid account (optional if browsing is allowed without login).  
- Shops are already registered in the system database with barangay information.  
- User has access to the Browse Shops section.

### Scenario 1: Apply barangay filter

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | User navigates to the **Browse Shops** page. | System loads the page with all shops displayed in grid layout. |
| 2 | User opens the filter options. | Barangay filter dropdown or selection list is visible. |
| 3 | User selects a specific barangay (e.g., Barangay A). | System filters and displays only shops located in Barangay A. |
| 4 | User scrolls through the filtered grid. | Shops are displayed correctly without errors. |
| 5 |  |  |

**Actual Result:**  
System filters shops correctly by barangay.  

**Status:**  
Pass  

**Post-conditions:**  
- User remains in browsing mode.  
- Shop details can be accessed individually.  
