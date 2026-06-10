# SM-013: Store Management Testing – Store Status Indicator

> **Summary:** Verify that the **Active** status indicator correctly reflects the store’s operational state.

**Preconditions:**  
- Vendor is logged in.  
- Store profile section is visible.

### Scenario 1: Verify store status indicator

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Navigate to the **Store Profile** section. | Store status indicator is visible beside the store name. |
| 2 | Observe the indicator color and label. | Green indicator with “Active” label is displayed. |
| 3 | Toggle store status (if applicable). | Indicator updates correctly to reflect new status. |
| 4 | Refresh the page. | Status remains consistent after reload. |

**Actual Result:**  
System correctly displays and maintains the **Active** status indicator.  

**Status:**  
Pass ✅  

**Post‑conditions:**  
- Store status remains accurate and synchronized with operational state.
