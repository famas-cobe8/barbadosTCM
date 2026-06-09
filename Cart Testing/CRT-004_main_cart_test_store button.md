# CRT-004: Main Cart Test - Go to Store Button Redirection

> **Category:** Cart Management  
> **Summary:** Verify that clicking the "Go to store" button redirects the customer back to that specific store's main catalog view page.

**Preconditions:**  
- Customer is viewing a store order block on the main Cart dashboard page.

### Scenario 1

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Click the primary orange **Go to store** button in the bottom-right corner of the store card. | The system processes the router path configuration for that specific merchant. |
| 2 | Observe the application viewport screen state. | The app transitions smoothly back to that store's complete menu catalog page. |

**Actual Result:**  
The routing transition completes instantly, returning the customer directly to the active storefront layout.  

**Status:**  
Pass  

**Post-conditions:**  
- The specific store profile page loads completely and remains fully interactive for menu browsing.

---