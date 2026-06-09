# SL-003: Shop Layout Testing - Report Store

> **Category:** Shop Layout & Menu Interaction  
> **Summary:** Ensure the "Report" button triggers the storefront reporting interface modal.

**Preconditions:**  
- Customer is viewing the target shop's primary page.

### Scenario 1

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Click the **Report** button on the far right. | The system processes the event action. |
| 2 | Monitor the UI overlay behavior. | A store reporting dialog modal appears on top of the screen. |
| 3 | Inspect the reporting choices. | The modal lists structured reporting reasons and a comments box. |

**Actual Result:**  
The report button successfully opens the compliance interaction modal smoothly over the storefront page.  

**Status:**  
Pass  

**Post-conditions:**  
- Storefront navigation elements behind the modal are temporarily locked until closed.
