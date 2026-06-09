# ATC-004: Add to Cart Testing - Clear and Delete Subcart Items

> **Summary:** Verify that clicking the "Clear" link removes all configured line items from the storefront's active subcart panel layout.

**Preconditions:**  
- The subcart card displays at least one active item entry in its list.

### Scenario 1

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Click the **Clear** text link element in the top-right blue banner header tracking track. | System registers the deletion execution event request. |
| 2 | Observe the active subcart panel space. | The item entries, subtotal breakdown lines, and place order button disappear. |
| 3 | Verify the fallback screen layout state. | The panel displays a clean empty cart placeholder message context. |

**Actual Result:**  
The clear option purges stored session elements instantly, turning the active card back into a clean empty basket layout baseline.  

**Status:**  
Pass  

**Post-conditions:**  
- Active order states for the current shop are reset back to a zeroed baseline balance.

---

