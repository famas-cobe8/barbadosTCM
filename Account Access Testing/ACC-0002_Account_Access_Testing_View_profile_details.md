# ACC-0002: Account Access Testing - View profile details

> **Summary:** Ensure that a logged-in user can view their own profile details correctly.

**Preconditions:**  
- User has a valid account.  
- User is logged in successfully.

### Scenario 1

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | Navigate to the profile section after login. | Profile page loads without error. |
| 2 | Verify displayed details (name, email, contact info). | All details match the user’s account records. |
| 3 | Check for edit/update options. | Edit/update buttons are visible and functional. |

**Actual Result:**  
_System displays the user’s profile details correctly as expected._

**Status:**  
_Pass_

**Post-conditions:**  
- User remains logged in.  
- Profile data is unchanged unless explicitly updated.