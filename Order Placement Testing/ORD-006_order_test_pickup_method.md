# ORD-006: Orde Test - Pick-up Method

> **Summary:** Verify that the user can select a preferred method of order before payment.

**Preconditions:**  
- User has confirmed items in the cart.  
- Checkout page is accessible.

### Scenario 1

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | System displays **Choose Method of Order** screen. | Options for **Pickup Point** and **Delivery** are visible. |
| 2 | User selects **Pickup Point**. | Option highlights and system enables **Confirm** button. |
| 3 | Click **Confirm** to proceed. | System redirects to payment method selection. |
| 4 |  |  |
| 5 |  |  |
| 6 |  |  |

**Actual Result:**  
System allows selection of order method and proceeds correctly to payment.  

**Status:**  
Pass  

**Post‑conditions:**  
- Selected method is stored for the current order.
