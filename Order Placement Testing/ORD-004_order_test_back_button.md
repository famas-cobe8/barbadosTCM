# ORD-004: Go back during order process

> **Category:** Ordering  
> **Summary:** Verify that the user can navigate back to the previous step in the order process without losing progress or data.

**Preconditions:**  
- User is logged in.  
- Items are already added to the cart.  
- User is in the checkout flow (any stage between item confirmation, method selection, or payment).

### Scenario 1: Go back from payment method selection

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | User is on the **Mode of Payment** screen. | Payment options and order summary are displayed. |
| 2 | User clicks the **Back** button. | System redirects to the previous step (Choose Method of Order). |
| 3 | Verify that previously selected method (Pickup or Delivery) remains selected. | System retains the user’s previous selection. |
| 4 | Click **Back** again. | System redirects to the item confirmation screen with all details intact. |
| 5 | Verify that item quantity, subtotal, and notes remain unchanged. | System retains all previously entered data. |
| 6 |  |  |

**Actual Result:**  
System successfully navigates back through previous steps while retaining all user selections and data.  

**Status:**  
Pass  

**Post‑conditions:**  
- User can resume the order process from any previous step without re‑entering information.  
- No data loss or reset occurs during navigation.
