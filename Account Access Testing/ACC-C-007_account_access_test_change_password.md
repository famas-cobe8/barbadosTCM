# ACC-C-007: Account Access Testing - Customer changes password successfully

> **Summary:** Verify that a customer can successfully change their account password.

**Preconditions:**  
- Customer is logged in.  
- Security settings page is accessible.  

### Scenario 1: Change password

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Customer navigates to the **Security** tab in account settings. | Security page loads showing password options. |
| 2 | Customer enters a new valid password in the **New password** field. | Field accepts input correctly and meets password criteria. |
| 3 | Customer clicks **Change password** button. | System validates and updates the password. |
| 4 | Verify confirmation message. | System displays success message (e.g., “Password changed successfully”). |
| 5 | Customer logs out and logs in using the new password. | Login succeeds with updated password. |
| 6 |  |  |

**Actual Result:**  
System updates the password successfully and allows login with the new credentials.  

**Status:**  
Pass ✅  

**Post‑conditions:**  
- Customer password is updated.  
- Customer can log in using the new password.
