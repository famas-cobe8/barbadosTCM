# SL-002: Shop Layout Testing - Store Chat

> **Category:** Shop Layout & Menu Interaction  
> **Summary:** Verify that selecting the "Chat with Store" button opens a direct messaging session with the merchant.

**Preconditions:**  
- Customer is inside the target shop's storefront.

### Scenario 1

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Click the **Chat with Store** button. | The system registers the click event. |
| 2 | Observe the interface transition. | Redirects to an active message panel. |
| 3 | Verify input field readiness. | The text cursor appears in the input field, ready for typing. |

**Actual Result:**  
The communication channel opens immediately, establishing an active chat session with the merchant.  

**Status:**  
Pass  

**Post-conditions:**  
- Customer can send real-time text messages to the store.

---

