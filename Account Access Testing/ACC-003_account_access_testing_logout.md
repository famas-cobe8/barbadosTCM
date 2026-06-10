# ACC-003: Logout from active account successfully


> **Summary:** Ensure that a logged-in user can log out of their account without errors.

**Preconditions:**  
- User has a valid account.  
- User is logged in successfully.

### Scenario 1

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Click the logout button/link from the navigation menu under (profile button). | System processes logout request. |
| 2 | Verify redirection after logout. | User is redirected to the login page or homepage. |
| 3 |  |  |

**Actual Result:**  
_Profile details displayed correctly; logout function executed without error._

**Status:**  
_Pass_

**Post-conditions:**  
- User session is terminated.  
- User cannot access account-specific pages without logging in again.
