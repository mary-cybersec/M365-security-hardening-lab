# Task 12: Audit User Activity Logs

## 🔎 Objective
Search user activity logs in Microsoft Purview Compliance Portal to track sign-ins, mailbox activity, and policy-related events. This supports compliance, security investigations, and anomaly detection.

---

## 🛠️ Steps Taken

### ✅ Step 1: Sign in to Microsoft Purview Compliance Portal
- URL: [https://compliance.microsoft.com](https://compliance.microsoft.com)
- Signed in using the global admin account

---

### ✅ Step 2: Navigate to the Audit Page
- In the left panel, clicked **Audit**
- Selected **Audit Search**

---

### ✅ Step 3: Run an Audit Log Search
- Set the search filters to:
  - **Activities**: User signed in, Mailbox login, Send message, etc.
  - **Users**: Selected the standard user account created in Task 1
  - **Start/End date**: Set to include recent activity (e.g., past 7 days)
- Clicked **Search**

---

### ✅ Step 4: Review and Export Results
- Waited for results to populate
- Reviewed columns like:
  - **Activity**
  - **User**
  - **Date/Time**
  - **IP address**
  - **Details**
- Clicked **Export** to download results as a CSV (optional)

---

## 🧪 Testing Performed
- Simulated standard user activity (e.g., logged in, opened mailbox, sent test email)
- Ran audit log search afterward to confirm events were captured

---

## 📸 Screenshot Evidence
Stored in `/screenshots/`:
- Audit Search filter screen
- Search results with user activity
- Optional: CSV export view

---

## 🔐 Why This Matters
Audit logs provide visibility into user and admin activity across Microsoft 365. They support threat hunting, insider risk detection, and forensic investigation after suspicious events.

---

## 🔗 Tools Used
- Microsoft Purview Compliance Portal  
- Microsoft 365 Admin Center (for simulating activity)
- Outlook Web Access (user test actions)
