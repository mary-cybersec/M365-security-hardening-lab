# Task 7: Create Safe Links Policy for Email

## 🛡️ Objective
Create and apply a Safe Links policy in Microsoft Defender for Office 365 to protect users from malicious URLs in emails, Teams, and Office apps by scanning links at the time of click.

---

## 🛠️ Steps Taken

### ✅ Step 1: Sign in to Microsoft 365 Defender Portal
- URL: [https://security.microsoft.com](https://security.microsoft.com)
- Signed in using the global admin account

---

### ✅ Step 2: Navigate to Safe Links
- From the left-hand menu:
  - Clicked **Email & collaboration**
  - Clicked **Policies & rules**
  - Opened **Threat policies > Safe Links**

---

### ✅ Step 3: Create a New Safe Links Policy
- Clicked **+ Create**
- Policy name: `Safe Links Policy - Standard User`
- Applied policy to: Standard user account

---

### ✅ Step 4: Configure Safe Link Settings
- ✅ Enabled protection for email messages
- ✅ Enabled scanning of links in Office apps (Word, Excel, PowerPoint, Teams)
- ✅ Enabled real-time scanning of URLs
- ✅ Enabled click tracking
- ✅ Blocked users from clicking through malicious links

---

### ✅ Step 5: Save and Submit the Policy
- Reviewed configuration
- Clicked **Submit**
- Policy saved and began applying to target user

---

## 🧪 Testing Performed
- Sent test email from external account containing a dummy URL (e.g., `http://example.com`)
- Hovered over link to confirm **Safe Links rewriting** was applied (URL shows Microsoft redirect)

---

## 📸 Screenshot Evidence
Stored in `/screenshots/`:
- Safe Links policy creation screen
- Enabled settings view
- Confirmation screen
- Test result showing rewritten URL

---

## 🔐 Why This Matters
Safe Links helps prevent phishing attacks by scanning URLs **at the time of click**, even if the link wasn’t malicious at the time the message was delivered. This provides advanced, real-time protection for users.

---

## 🔗 Tools Used
- Microsoft 365 Defender Portal  
- Outlook Web Access (for testing)
