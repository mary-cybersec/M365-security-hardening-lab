# Task 8: Create Safe Attachments Policy

## 📎 Objective
Create a Safe Attachments policy in Microsoft Defender for Office 365 to automatically detect and block potentially malicious email attachments by scanning them in a sandbox environment before delivery.

---

## 🛠️ Steps Taken

### ✅ Step 1: Sign in to Microsoft 365 Defender
- URL: [https://security.microsoft.com](https://security.microsoft.com)
- Logged in using the global admin account

---

### ✅ Step 2: Navigate to Safe Attachments
- In the left-hand panel:
  - Clicked **Email & collaboration**
  - Selected **Policies & rules**
  - Clicked **Threat policies > Safe Attachments**

---

### ✅ Step 3: Create a New Policy
- Clicked **+ Create**
- Policy name: `Safe Attachments Policy - Standard User`
- Applied to: Regular/standard user account

---

### ✅ Step 4: Configure Policy Settings
- ✅ Selected **Dynamic Delivery**:
  - Email is delivered without the attachment until scanning is complete
- ✅ Enabled:
  - Monitor, block, and replace malicious attachments
  - Redirect detected files to admin/quarantine
  - Applied policy to internal and external messages

---

### ✅ Step 5: Save & Submit Policy
- Clicked **Submit**
- Policy saved and began applying immediately

---

## 🧪 Testing Performed
- Sent an email with a test attachment (e.g., `.docx` or `.zip`) from a personal account
- Verified that attachment was scanned and email was either delayed or flagged

---

## 📸 Screenshot Evidence
Stored in `/screenshots/`:
- Safe Attachments policy configuration
- Selected “Dynamic Delivery” option
- Test results in OWA inbox

---

## 🔐 Why This Matters
Malicious attachments are a major entry point for ransomware, spyware, and keyloggers. Safe Attachments scans file content in real-time before it reaches the user, reducing risk of infection and lateral movement.

---

## 🔗 Tools Used
- Microsoft 365 Defender Portal  
- Microsoft Defender for Office 365  
- Outlook Web Access (for verification)
