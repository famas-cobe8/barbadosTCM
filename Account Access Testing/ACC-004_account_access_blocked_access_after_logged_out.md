# ACC-004: Blocked access to pages after logged out

> **Summary:** Ensure that users cannot access protected pages after logging out.

**Preconditions:**  
- User has a valid account.  
- User is logged in successfully.

### Scenario 1

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Log out from the active account. | User session is terminated. |
| 2 | Attempt to access a protected page (e.g., profile, dashboard) via direct URL or browser history. | System detects invalid session and blocks access. |
| 3 | Verify displayed message or redirection. | “Invalid Link” message appears, and user is prompted to return to the login page. |

**Actual Result:**  
System correctly blocks access to protected pages after logout and displays the “Invalid Link” message. Functionality works as expected.

**Status:**  
Pass

**Post-conditions:**  
- User remains logged out.  
- No protected content is accessible without re-authentication.
