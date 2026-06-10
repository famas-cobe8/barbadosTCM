# AAC-V-007: Account Access Testing - Vendor changes password successfully

> **Summary:** Verify that a vendor can successfully change their account password.

**Preconditions:**  
- Vendor is logged in.  
- Security settings page is accessible.  

### Scenario 1: Change password

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Vendor navigates to the **Security** tab in account settings. | Security page loads showing password options. |
| 2 | Vendor enters a new valid password in the **New password** field. | Field accepts input correctly and meets password criteria. |
| 3 | Vendor clicks **Change password** button. | System validates and updates the password. |
| 4 | Verify confirmation message. | System displays success message (e.g., “Password changed successfully”). |
| 5 | Vendor logs out and logs in using the new password. | Login succeeds with updated password. |
| 6 |  |  |

**Actual Result:**  
System updates the password successfully and allows login with the new credentials.  

**Status:**  
Pass ✅  

**Post‑conditions:**  
- Vendor password is updated.  
- Vendor can log in using the new password.
