# Task 6: Create External Email Warning Banner

## ✉️ Objective
Create a mail flow rule in Microsoft Exchange Online to prepend a warning banner on all incoming emails from external senders. This helps users quickly recognize potentially risky messages and avoid phishing attempts.

---

## 🛠️ Steps Taken

### ✅ Step 1: Open Exchange Admin Center (EAC)
- URL: [https://admin.exchange.microsoft.com](https://admin.exchange.microsoft.com)
- Signed in as the global admin account
- Navigated to: **Mail flow > Rules**

---

### ✅ Step 2: Create New Rule
- Clicked **+ Add a rule**
- Chose **Create a new rule**
- Rule name: `External Email Warning Banner`

---

### ✅ Step 3: Set Rule Conditions
- **Apply this rule if**:
  - The sender is located → **Outside the organization**

---

### ✅ Step 4: Add the Disclaimer Action
- **Do the following**:
  - Prepend a disclaimer to the message
- Used the following **HTML banner**:

```html
<div style="border:2px solid red; padding:10px; color:red; font-weight:bold;">
⚠️ This email originated from outside your organization. Do not click links or open attachments unless you trust the sender.
</div>

Fallback action: Wrap message

✅ Step 5: Save & Enable Rule
Reviewed the configuration

Clicked Finish and Enabled the rule

🧪 Testing Performed
Sent an email from external Gmail account to the standard user

Verified that the warning banner appeared at the top of the email message in Outlook Web Access

📸 Screenshot Evidence
Stored in /screenshots/:

Mail flow rule configuration screen

Banner preview in email inbox

External test email results

🔐 Why This Matters
Phishing is one of the most common attack vectors in enterprise environments. Visual cues like warning banners help end users detect external senders and avoid falling for impersonation or malware-laced emails.

🔗 Tools Used
Exchange Admin Center (EAC)

Outlook Web Access (OWA)

Gmail (external testing)