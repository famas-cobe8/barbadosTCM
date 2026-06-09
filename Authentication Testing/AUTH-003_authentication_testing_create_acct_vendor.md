# AUTH-003: Authentication Testing Create account as Vendor

> **Summary:** Verify that a user can successfully create a Vendor account and complete email verification.

**Preconditions:**  
- Application registration page is accessible.  
- User has a valid email address.

### Scenario 1

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Navigate to the **Create Account** page. | Registration form loads correctly. |
| 2 | Fill in valid details (Full Name, Email, Password, Confirm Password). | Fields accept input; password is masked. |
| 3 | Agree to Terms & Conditions and Privacy Policy. | Checkbox is selected successfully. |
| 4 | Click the **Create Account** button. | System sends a verification email and displays confirmation message. |
| 5 | Open email and click the verification link. | System verifies email and displays success message. |
| 6 | Click **Log In** and enter credentials. | User is redirected to role selection page. |
| 7 | Select **Vendor** role and click **Continue**. | System creates Vendor account and displays success message. |

**Actual Result:**  
System sends verification email, validates user, and creates Vendor account successfully.  

**Status:**  
Pass  

**Post‑conditions:**  
- Vendor account is created and verified.  
- User can log in and access vendor‑specific features.
