# MSG-C-002: Message Test - Customer sends messages
 
> **Summary:** Verify that the customer can send messages and receive replies from the vendor successfully.

**Preconditions:**  
- Customer is logged in.  
- Vendor is active and responsive.

### Scenario 1

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Customer types a message in the input field. | Field accepts input correctly. |
| 2 | Customer clicks the **Send** button. | Message appears in chat window with timestamp and sender label. |
| 3 | Vendor replies to the message. | Reply appears in chat window with correct timestamp and vendor label. |
| 4 | Customer scrolls through chat history. | All messages are displayed in chronological order. |
| 5 |  |  |
| 6 |  |  |

**Actual Result:**  
Messages sent and received successfully; timestamps and sender labels are accurate.  

**Status:**  
Pass  

**Post‑conditions:**  
- Conversation thread is updated and stored.
