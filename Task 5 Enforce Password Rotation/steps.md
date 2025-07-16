# Task 5: Enforce Password Rotation

## 🔁 Objective
Set up a tenant-wide password expiration policy to ensure users are required to reset their passwords every 60 days, promoting account hygiene and reducing the risk of long-term credential exposure.

---

## 🛠️ Steps Taken

### ✅ Step 1: Access the Microsoft 365 Admin Center
- URL: [https://admin.microsoft.com](https://admin.microsoft.com)
- Signed in with the global admin account

---

### ✅ Step 2: Navigate to Password Expiration Settings
- Went to:  
  **Settings > Org settings > Security & privacy**
- Located and clicked on **Password expiration policy**

*(If not visible, used this direct link: [https://admin.microsoft.com/AdminPortal/Home#/Settings/PasswordPolicy](https://admin.microsoft.com/AdminPortal/Home#/Settings/PasswordPolicy))*

---

### ✅ Step 3: Configure the Expiration Settings
- Unchecked: ✅ **Set passwords to never expire**
- Set:
  - **Days before passwords expire**: `60`
  - (Optional) **Days before users are notified**: `14`
- Clicked **Save**

---

## 🧪 Testing Performed
- Reviewed user settings to confirm the policy was applied
- Noted expected expiration warning period of 14 days before 60-day deadline

---

## 📸 Screenshot Evidence
Stored in `/screenshots/`:
- Password expiration policy screen before and after configuration
- Save confirmation message

---

## 🔐 Why This Matters
Regular password rotation reduces the window of opportunity for compromised credentials to be exploited. It’s particularly important in organizations without passwordless or MFA-only environments.

---

## 🔗 Tools Used
- Microsoft 365 Admin Center
