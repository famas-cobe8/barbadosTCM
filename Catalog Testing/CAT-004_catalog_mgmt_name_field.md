# CAT-004: Catalog Management – Product Name Field

> **Summary:** Verify that product name field accepts valid input and rejects blank entries.

**Preconditions:**  
- Vendor is logged in.  
- Add Product modal is open.

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Enter product name. | Field accepts text. |
| 2 | Leave blank and submit. | System shows validation error. |

**Actual Result:**  
Valid input accepted; blank rejected.  

**Status:**  
Pass ✅
