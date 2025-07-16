# Task 13: Create Alert Policies in Microsoft Defender

## 🚨 Objective
Create custom alert policies in Microsoft Defender for Office 365 to detect and notify admins about suspicious or high-risk activities across M365 services (e.g., malware detection, unusual file sharing, login anomalies).

---

## 🛠️ Steps Taken

### ✅ Step 1: Sign in to Microsoft 365 Defender Portal
- URL: [https://security.microsoft.com](https://security.microsoft.com)
- Signed in using the global admin account

---

### ✅ Step 2: Navigate to Alert Policies
- From the left-hand menu:
  - Clicked **Email & collaboration**
  - Selected **Policies & rules**
  - Clicked **Alert policies**

---

### ✅ Step 3: Create New Alert Policy
- Clicked **+ New alert policy**
- Filled out policy details:
  - **Name**: `Malware Detection Alert`
  - **Severity**: Medium or High
  - **Category**: Threat Management

---

### ✅ Step 4: Set Alert Conditions
- Selected alert trigger:
  - **Activity**: Malware detected in email or file
- Scope: Applied to **all users**
- Set:
  - **Send alerts to**: Admin email address
  - **Daily alert limit**: (left default or set a reasonable threshold)

---

### ✅ Step 5: Review & Submit
- Reviewed all settings
- Clicked **Submit**
- Verified the new alert policy appeared in the policy list

---

## 🧪 Testing Performed
- Sent a test email with an EICAR string (safe malware test)
- Verified that alert was generated
- Checked admin email for notification

---

## 📸 Screenshot Evidence
Stored in `/screenshots/`:
- Alert policy creation page
- Trigger settings
- Example alert notification

---

## 🔐 Why This Matters
Alert policies help security teams detect, respond to, and investigate threats quickly. Automating these notifications improves visibility and reduces the chance of delayed responses during critical events.

---

## 🔗 Tools Used
- Microsoft 365 Defender Portal  
- Admin email inbox (for alert testing)
- Optional: Microsoft Purview (for alert correlation)
