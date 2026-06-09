# AUTH-002: Authentication Testing - Logging in using Google


> **Summary:** Verify that users can successfully log in using their Google account through OAuth 2.0 and OpenID Connect.

**Preconditions:**  
- Application is registered with Google Cloud Platform and configured with valid Client ID, Client Secret, and Redirect URI.  
- Internet connection is active.

---

### Scenario 1: No Google accounts logged in on browser

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | User clicks the **“Sign in with Google”** button on the application login page. | Application redirects to Google’s Authorization Endpoint with required parameters. |
| 2 | Google login screen appears; user enters valid email and password. | Google validates credentials and proceeds to consent screen. |
| 3 | User reviews and clicks **Allow** on the consent screen. | Google issues an Authorization Code and redirects back to the application’s Redirect URI. |
| 4 | Application exchanges the Authorization Code for tokens via Google’s Token Endpoint. | Access Token and ID Token are returned and validated. |
| 5 | Application retrieves user profile data from Google’s UserInfo Endpoint. | User information is fetched securely and stored in the session. |
| 6 | User is redirected to the application dashboard. | Login completes successfully; user session is active. |

**Actual Result:**  
System prompts for credentials, processes consent, and logs in successfully.  

**Status:**  
Pass  

**Post-conditions:**  
- User session is created with Google OAuth tokens.  
- User can access protected pages.  

---

### Scenario 2: Existing Google accounts already logged in on browser

| # | Step | Expected Behavior |
|---|------|-------------------|
| 1 | User clicks the **“Sign in with Google”** button on the application login page. | Application redirects to Google’s Authorization Endpoint. |
| 2 | Google account chooser screen appears showing already logged-in accounts. | User selects one of the available accounts. |
| 3 | If consent was not previously granted, user clicks **Allow** on the consent screen. | Google issues an Authorization Code and redirects back to the application’s Redirect URI. |
| 4 | Application exchanges the Authorization Code for tokens via Google’s Token Endpoint. | Access Token and ID Token are returned and validated. |
| 5 | Application retrieves user profile data from Google’s UserInfo Endpoint. | User information is fetched securely and stored in the session. |
| 6 | User is redirected to the application dashboard. | Login completes successfully; user session is active. |

**Actual Result:**  
System allows quick account selection, processes consent if needed, and logs in successfully.  

**Status:**  
Pass  

**Post-conditions:**  
- User session is created with Google OAuth tokens.  
- User can access protected pages.  
- Previously logged-in Google accounts remain unaffected in the browser.  

