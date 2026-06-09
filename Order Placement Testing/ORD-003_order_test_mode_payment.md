# ORD-0003: Order Test - Select mode of payment and place order

> **Summary:** Verify that the user can select a payment method and successfully place an order.

**Preconditions:**  
- User has selected order method (Pickup or Delivery).  
- Payment options are available.

### Scenario 1

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | System displays **Mode of Payment** screen. | Payment options (Cash on Delivery, Mastercard, GCash) are visible. |
| 2 | User selects **Cash on Delivery**. | Option highlights and system enables **Place Order** button. |
| 3 | Review order summary (items, subtotal, total). | Details match previous selections. |
| 4 | Click **Place Order**. | System confirms order placement and displays success message. |
| 5 |  |  |
| 6 |  |  |

**Actual Result:**  
System processes payment selection and confirms order successfully.  

**Status:**  
Pass  

**Post‑conditions:**  
- Order is recorded in the system.  
- User receives confirmation notification.
