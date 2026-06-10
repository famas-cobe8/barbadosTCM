# ACC-001: Account Access Testing - Login with valid credentials

> **Summary:** Ensure that a user can successfully log in with valid credentials.

**Preconditions:**  
- User has a valid account.  
- Application login page is accessible.

### Scenario 1

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Navigate to the login page. | Login page loads without error. |
| 2 | Enter valid username/email. | Field accepts input correctly. |
| 3 | Enter valid password. | Field accepts input correctly; password is masked. |
| 4 | Click the **Login** button. | System processes login request. |
| 5 | Verify redirection after login. | User is redirected to the main dashboard or landing page. |
| 6 |  |  |

**Actual Result:**  
System authenticates credentials and redirects user to the dashboard successfully.  

**Status:**  
Pass  

**Post-conditions:**  
- User remains logged in.  
- Account-specific features are accessible.

