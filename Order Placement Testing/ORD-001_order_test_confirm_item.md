# ORD-0001: Order Test - Confirm item quantity and total before checkout
 
> **Summary:** Verify that the user can adjust item quantity and view the correct total before proceeding to checkout.

**Preconditions:**  
- User is logged in.  
- At least one item is added to the cart.

### Scenario 1

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Open the cart and select an item to review. | Item details (name, price, quantity) are displayed. |
| 2 | Adjust quantity using plus/minus buttons. | Subtotal updates automatically based on quantity. |
| 3 | Add an optional note to the order. | Note field accepts input correctly. |
| 4 | Click **Confirm** to proceed. | System redirects to method of order selection. |
| 5 |  |  |
| 6 |  |  |

**Actual Result:**  
System correctly updates subtotal and proceeds to the next step.  

**Status:**  
Pass  

**Post‑conditions:**  
- Item quantity and total are saved for checkout.
