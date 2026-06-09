# ATC-005: Add to Cart Testing - Subcart Direct Checkout

> **Category:** Cart Management  
> **Summary:** Verify that clicking the "Place Order" button from the inline subcart triggers the direct purchase routing flow without forcing an exit to the main cart page.

**Preconditions:**  
- The subcart is populated with items, displaying correct delivery fee and total calculations.

### Scenario 1

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Click the large orange **Place Order - ₱197.00** button component. | System processes transaction routing rules instantly. |
| 2 | Monitor application screen state navigation. | View transitions directly to the payment selection screen or confirmation flow. |

**Actual Result:**  
The place order action bypasses redundant checkout steps, successfully pushing the session parameters straight into payment verification.  

**Status:**  
Pass  

**Post-conditions:**  
- Final order details lock into structural database logs pending customer financial authorization.
