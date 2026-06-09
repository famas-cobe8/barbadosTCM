# BRS-011: Browse Shop Testing - Clear Search

> **Category:** Search & Discovery  
> **Summary:** Verify that clearing the search bar text fails to refresh the full shop directory feed.

**Preconditions:**  
- Active filtered search results are displayed..

### Scenario 1

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Click backspaces; empty search space. | Text string is removed from the field. |
| 2 | Observe the search bar. | Field returns to empty placeholder state. |
| 3 | Monitor the main shop listing feed. | Feed automatically refreshes to full listing. |
| 4 | |  |

**Actual Result:**  
Text box clears successfully, but the main feed layout fails to refresh or reload the full directory list.  

**Status:**  
Fail  

**Post-conditions:**  
- List remains broken until manual page refresh.
