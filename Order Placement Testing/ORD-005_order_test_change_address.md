# ORD-005: Order Test Change delivery address at final checkout stage

> **Summary:** Verify that the user can change their delivery address during the last stage of the checkout flow.

**Preconditions:**  
- User is logged in.  
- Items are already added to the cart.  
- User has proceeded through item confirmation and method of order selection.  
- User is on the payment/checkout confirmation screen.

### Scenario 1: Change address before placing order

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | User is on the **Checkout Confirmation** screen with delivery details visible. | Current delivery address is displayed along with order summary. |
| 2 | User clicks **Edit Address** option. | System should open address input form or selection list. |
| 3 | User enters a new valid delivery address. | Field should accept input correctly; validation checks applied. |
| 4 | User saves the new address. | System should update the delivery details in the order summary. |
| 5 | User clicks **Place Order**. | System should confirm order placement with updated delivery address. |
| 6 |  |  |

**Actual Result:**  
No process has been run; system did not allow address change or proceed with order placement.  

**Status:**  
Fail  

**Post‑conditions:**  
- Order not placed.  
- Address change not executed.  
