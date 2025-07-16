# Task 2: Enable Per-User Multi-Factor Authentication (MFA)

##  Objective
Secure the M365 admin account by enabling multi-factor authentication (MFA) to prevent unauthorized access and enforce stronger identity protection.

---

##  Steps Taken

###  Step 1: Sign in to Microsoft 365 Admin Center
- URL: [https://admin.microsoft.com](https://admin.microsoft.com)
- Signed in using the global admin account

---

###  Step 2: Access MFA Settings
- Navigated to **Users > Active users**
- Clicked the link near the top-right:  
  `Multi-factor authentication`

*(If not visible, searched for “Multi-Factor Authentication” in the search bar and followed the link to the MFA settings page.)*

---

###  Step 3: Enable MFA for Admin Account
- Located the admin account in the user list
- Selected the checkbox beside the username
- Clicked **Enable** on the right-hand side
- Confirmed the prompt to enable MFA

---

###  Step 4: Perform First-Time Sign-In with MFA
- Logged in as the admin account in a new browser or incognito window
- Followed the prompt to set up MFA using:
  - Authenticator app (recommended), or
  - SMS verification

---

##  Screenshot Evidence
Stored in `/screenshots/` folder:
- MFA enablement screen
- Admin user selected with MFA enabled
- Authenticator setup prompt

---

##  Why This Matters
Multi-factor authentication is one of the most critical defenses against password compromise and account takeover. Enabling it for privileged accounts like administrators is a foundational best practice in enterprise security.

---

##  Tools Used
- Microsoft 365 Admin Center  
- Outlook Web Access (for testing login behavior)
