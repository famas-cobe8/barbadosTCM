# SM-012: Store Management Testing – Edit Store Information Fields

> **Summary:** Verify that the vendor can successfully edit store name, description, and operating hours.

**Preconditions:**  
- Vendor is logged in.  
- Store profile editing modal is open.

### Scenario 1: Edit store information

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Click inside the **Store Name** field. | Field accepts input correctly. |
| 2 | Modify the **Description** field. | Field accepts text input without errors. |
| 3 | Adjust **Opening time** and **Closing time** using time selectors. | Time fields update correctly and validate input format. |
| 4 | Click the **Check (✓)** icon to confirm edits. | System saves changes and updates the store profile. |

**Actual Result:**  
System successfully updates store name, description, and operating hours.  

**Status:**  
Pass ✅  

**Post‑conditions:**  
- Store profile reflects updated information immediately.
