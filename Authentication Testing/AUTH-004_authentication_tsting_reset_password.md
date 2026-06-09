# AUTH-0004: Authentication Testing - Reset forgotten password

> **Summary:** Ensure that a user can successfully reset their password when they have forgotten it.

**Preconditions:**  
- User has a registered account.  
- User clicks the “Forgot Password?” link.

### Scenario 1

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Enter a valid registered email address in the “Forgot Password” form. |  |
| 2 | Click "Reset Password" Button. |System sends a password reset link to the provided email.
| 3 | Open the received email and click the “Reset Password” link. | User is redirected to the password reset page. |
| 4 | Enter a new password and confirm it, then click “Update Password.” | Password is updated successfully, and user can log in with the new credentials. |

**Actual Result:**  
System sends the reset link, redirects correctly, and updates the password successfully. All functions work as expected.

**Status:**  
Pass

**Post-conditions:**  
- User’s password is updated.  
- Old password is invalidated.  
- User can log in using the new password.
