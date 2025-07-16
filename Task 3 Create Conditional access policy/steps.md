\# Task 3: Create Conditional Access Policy



\##  Objective

Create and apply a Conditional Access (CA) policy that enforces MFA and restricts sign-ins to users only within Canada, using Microsoft Entra ID (formerly Azure AD).



---



\##  Steps Taken



\###  Step 1: Sign in to Microsoft Entra Admin Center

\- Visited: \[https://entra.microsoft.com](https://entra.microsoft.com)

\- Signed in with global admin account



---



\###  Step 2: Navigate to Conditional Access

\- From the left panel:  

&nbsp; Clicked \*\*Microsoft Entra ID\*\* → \*\*Protect \& Secure\*\* → \*\*Conditional Access\*\*

\- Clicked \*\*+ Create new policy\*\*



---



\###  Step 3: Configure Policy Details

\- \*\*Name\*\*: `MFA Canada Only - Standard User`

\- \*\*Users\*\*: Selected the \*\*standard user account\*\* created in Task 1

\- \*\*Cloud apps or actions\*\*: Applied to \*\*All cloud apps\*\*



---



\###  Step 4: Add Location Condition

\- Under \*\*Conditions > Locations\*\*:

&nbsp; - Set \*\*Include\*\* → `All locations`

&nbsp; - Set \*\*Exclude\*\* → `Selected locations` → Chose \*\*Canada\*\*

\- If not already added, created a \*\*Named Location\*\*:

&nbsp; - Location name: `Canada`

&nbsp; - Type: `Countries/Regions` → Selected `Canada`



---



\###  Step 5: Set Access Controls

\- Under \*\*Grant\*\*, chose:

* &nbsp; -  Grant access
* &nbsp; -  Require multi-factor authentication



---



\###  Step 6: Enable \& Save Policy

\- Set policy to: \*\*On\*\*

\- Clicked \*\*Create\*\* to activate the policy



---



\##  Testing Performed

\- Attempted sign-in with standard user account from a browser in Canada

\- Verified that MFA was triggered and login succeeded

\- Confirmed policy blocked sign-ins from other regions (if simulated)



---



\##  Screenshot Evidence

\- Policy setup screen

\- Location condition with “Canada” selected

\- MFA enforcement selected

\- Test login result (if available)



Saved in `/screenshots/` folder



---



\##  Why This Matters

Conditional Access is a critical component in modern identity security. This policy enforces MFA based on geography, helping to prevent unauthorized access from suspicious or foreign locations.



---



\##  Tools Used

\- Microsoft Entra Admin Center  

\- Outlook Web Access (for testing)



