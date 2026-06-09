# ATC-0007: Add to Cart Testing - View All Carts Link
 
> **Summary:** Verify that clicking the "View all carts" link successfully redirects the customer to the main multi-cart page.

**Preconditions:**  
- Customer has the inline subcart open and visible on the storefront.
- The "View all carts" link is fully rendered and clickable at the bottom of the subcart card layout.

### Scenario 1

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Scroll to the bottom of the inline subcart and locate the **View all carts** text link. | The element renders correctly with clean styling beneath the place order button. |
| 2 | Click or tap directly on the **View all carts** link component. | System processes the click event and fetches the global cart collection route data. |
| 3 | Monitor the user interface page transition behavior. | The application transitions smoothly to the main multi-cart dashboard or landing page. |
| 4 | Verify the displayed content on the newly rendered screen view. | The page completely lists all saved or active shopping carts across different platforms or stores. |

**Actual Result:**  
The link handles the route change request immediately, bringing the user directly to the main global cart center overview page.  

**Status:**  
Pass  

**Post-conditions:**  
- Main cart management features and global multi-basket listings are active and fully interactable.
- Historical browser navigation tracks are updated cleanly to register the route switch.
