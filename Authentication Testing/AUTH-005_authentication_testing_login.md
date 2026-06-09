# AUTH-005: Authentication Testing - Login

> **Summary:** Verify that a user can successfully log in using valid username and password credentials.

**Preconditions:**  
- User has a registered account with valid username and password.  
- Application login page is accessible.

### Scenario 1

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Navigate to the login page. | Login form loads correctly with username and password fields visible. |
| 2 | Enter valid username in the username field. | Field accepts input correctly. |
| 3 | Enter valid password in the password field. | Field accepts input correctly; password is masked. |
| 4 | Click the **Login** button. | System validates credentials and processes login request. |
| 5 | Verify redirection after successful login. | User is redirected to the main dashboard or landing page. |
| 6 |  |  |

**Actual Result:**  
System authenticates credentials and redirects user to the dashboard successfully.  

**Status:**  
Pass  

**Post-conditions:**  
- User session is active.  
- Account-specific features are accessible.
