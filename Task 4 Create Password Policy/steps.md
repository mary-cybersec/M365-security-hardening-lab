# Task 4: Enforce Custom Password Policy

## 🔐 Objective
Create a tenant-wide password policy in Microsoft Entra ID that includes account lockout after failed login attempts, a lockout duration, and a custom banned password list.

---

## 🛠️ Steps Taken

### ✅ Step 1: Sign in to Microsoft Entra Admin Center
- URL: [https://entra.microsoft.com](https://entra.microsoft.com)
- Logged in as the admin account

---

### ✅ Step 2: Navigate to Password Protection Settings
- From the left panel:  
  **Entra ID > Authentication Methods > Password Protection**

---

### ✅ Step 3: Configure Lockout Threshold & Duration
- Set **Lockout threshold** to `3`
- Set **Lockout duration (seconds)** to `60`
- Clicked **Save**

---

### ✅ Step 4: Enforce Custom Banned Password List
- Toggled **Enforce custom list** to `Yes`
- Added banned entries:
  - `mary`
  - `kelechi`
  - `cyberqueen`
  - `admin`
  - `123456`
- Clicked **Save**

---

## 🧪 Testing Performed
- Attempted sign-in with a weak password similar to the banned entries (e.g. `mary2025`)
- Verified the policy prevented password selection

---

## 📸 Screenshot Evidence
Stored in `/screenshots/`:
- Password Protection settings page
- Custom banned word list with names
- Save confirmation popup

---

## 🔐 Why This Matters
Weak and predictable passwords are one of the top attack vectors for credential stuffing and brute force attacks. Enforcing a custom banned password list ensures users can't use common names, company words, or leaked phrases.

---

## 🔗 Tools Used
- Microsoft Entra Admin Center
