# BRS-0002: Browse Shops testing - View list of all available shops

> **Summary:** Ensure that customer users are redirected to the home page after login and can view the complete list of all available shops.

**Preconditions:**  
- User has a valid customer account.  
- User is logged in successfully.  
- Shops are already registered in the system database.

### Scenario 1: Automatic redirection after login

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | User logs in with valid credentials. | System authenticates and redirects to the home page. |
| 2 | Home page loads automatically. | List of all available shops is displayed with name, logo, and brief description. |
| 3 | User scrolls through the list. | Shops are displayed in a paginated or infinite scroll format without errors. |
| 4 | User clicks on a shop entry. | System redirects to the shop’s detail page. |

**Actual Result:**  
System redirects to the home page after login and displays the list of shops correctly. Navigation and detail view work as expected.  

**Status:**  
Pass  

**Post-conditions:**  
- User remains logged in.  
- Shop details can be accessed individually.  

---