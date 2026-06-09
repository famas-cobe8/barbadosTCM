# BRS-012: Browse Shop Testing - Spaces and Typos

> **Category:** Search & Discovery  
> **Summary:** Verify search handles blank spaces and invalid typos by showing an empty state without errors.

**Preconditions:**  
- Customer is on the search screen.

### Scenario 1: Spaces Only

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Click into the search bar. | Field gains focus. |
| 2 | Enter spaces only ("   ") and submit. | Input is cleaned or blocked. |
| 3 | Observe the results screen. | View prompts for a valid term. |

### Scenario 2: Invalid Typos

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Enter a nonsensical typo ("xyzqwbv"). | Field displays the input. |
| 2 | Submit the search query. | System returns an empty data set. |
| 3 | Review the results screen. | "No shops found" message displays. |

**Actual Result:**  
System rejects invalid space and typo queries gracefully by showing a clean zero-results empty state.  

**Status:**  
Pass  

**Post-conditions:**  
- Search bar remains interactive for clean inputs.
