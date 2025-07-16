# Task 9: Create and Configure Anti-Phishing Policy

## 🎣 Objective
Create an anti-phishing policy in Microsoft Defender for Office 365 to detect and respond to impersonation attempts, suspicious sender behavior, and spoofing risks.

---

## 🛠️ Steps Taken

### ✅ Step 1: Sign in to Microsoft 365 Defender Portal
- URL: [https://security.microsoft.com](https://security.microsoft.com)
- Logged in with global admin credentials

---

### ✅ Step 2: Navigate to Anti-Phishing Policies
- Went to:
  - **Email & collaboration**
  - **Policies & rules**
  - **Threat policies > Anti-phishing**

---

### ✅ Step 3: Create New Anti-Phishing Policy
- Clicked **+ Create**
- Selected **Inbound policy (anti-phishing)**
- Named policy: `Anti-Phishing Policy - Standard User`
- Assigned to: The standard user created in Task 1

---

### ✅ Step 4: Configure Policy Settings
- Enabled protection against:
  - ✅ Display name impersonation
  - ✅ Domain impersonation
  - ✅ User impersonation
- Added admin user under **"Protected Users"** to defend against impersonation
- Enabled:
  - Spoof intelligence
  - Quarantine actions for high-confidence phishing
  - Safety tips in email banner

---

### ✅ Step 5: Review and Submit
- Reviewed all configuration options
- Clicked **Submit**
- Confirmed the policy appeared in the list under custom anti-phishing policies

---

## 🧪 Testing Performed
- Sent a test email with fake display name mimicking the admin
- Verified warning banner appeared in recipient inbox
- Confirmed detection in Microsoft 365 Defender Threat Explorer

---

## 📸 Screenshot Evidence
Stored in `/screenshots/`:
- Policy setup and user assignment
- Impersonation settings
- Test result showing banner or quarantine

---

## 🔐 Why This Matters
Phishing remains one of the top entry points for attackers. Anti-phishing policies provide behavioral detection, impersonation protection, and early warnings to end users — critical for defending identities.

---

## 🔗 Tools Used
- Microsoft 365 Defender Portal  
- Microsoft Defender for Office 365  
- Outlook Web Access (for email delivery testing)
