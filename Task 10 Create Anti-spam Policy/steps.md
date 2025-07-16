# Task 10: Create and Configure Anti-Spam Policy

## 📨 Objective
Create a custom anti-spam policy in Microsoft Defender for Office 365 to better protect users from spam, phishing, and spoofed emails, while customizing how suspicious messages are handled.

---

## 🛠️ Steps Taken

### ✅ Step 1: Sign in to Microsoft 365 Defender Portal
- URL: [https://security.microsoft.com](https://security.microsoft.com)
- Signed in using the global admin account

---

### ✅ Step 2: Navigate to Anti-Spam Policies
- From the left-hand menu:
  - Clicked **Email & collaboration**
  - Selected **Policies & rules**
  - Opened **Threat policies > Anti-spam**

---

### ✅ Step 3: Create a Custom Anti-Spam Policy
- Clicked **+ Create policy**
- Selected **Inbound policy (anti-spam)**
- Policy name: `Anti-Spam Policy - Standard User`
- Assigned to: Specific user (standard user account)

---

### ✅ Step 4: Configure Anti-Spam Settings
- Enabled the following protections:
  - ✅ Bulk email filtering
  - ✅ Spam filtering with aggressive thresholds
  - ✅ Spoof intelligence
  - ✅ Enable spam notifications
- Configured action for high-confidence spam:
  - Move to **Quarantine**
- Enabled automatic forwarding control: **Block**

---

### ✅ Step 5: Save and Submit Policy
- Reviewed all configurations
- Clicked **Submit**
- Verified that the policy was now listed under “Custom policies”

---

## 🧪 Testing Performed
- Sent a spoofed-style email from an external account
- Confirmed that the message was quarantined and alert was sent to user/admin

---

## 📸 Screenshot Evidence
Stored in `/screenshots/`:
- Anti-spam policy configuration page
- User assignment screen
- Sample quarantine message or alert

---

## 🔐 Why This Matters
Anti-spam policies are vital for protecting users from phishing, spoofing, and unsolicited bulk mail. Custom configurations allow security admins to fine-tune how messages are detected and where they’re delivered.

---

## 🔗 Tools Used
- Microsoft 365 Defender Portal  
- Microsoft Defender for Office 365  
- Outlook Web Access (for test spam delivery)
