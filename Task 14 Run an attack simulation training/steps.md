# Task 14: Launch Attack Simulation Training

## 🎯 Objective
Use Microsoft Defender’s Attack Simulation Training to simulate phishing and social engineering attacks for user awareness, behavior tracking, and incident readiness.

---

## 🛠️ Steps Taken

### ✅ Step 1: Sign in to Microsoft 365 Defender Portal
- URL: [https://security.microsoft.com](https://security.microsoft.com)
- Signed in using the global admin account

---

### ✅ Step 2: Navigate to Attack Simulation Training
- From the left-hand menu:
  - Clicked **Email & collaboration**
  - Selected **Attack simulation training**

---

### ✅ Step 3: Launch New Simulation
- Clicked **+ Launch a simulation**
- Simulation type selected: **Credential Harvest (Phishing)**
- Clicked **Next**

---

### ✅ Step 4: Configure Simulation Name & Payload
- Simulation name: `Phishing Awareness Test - Standard User`
- Selected a payload:
  - **Microsoft Account Password Reset** template
- Clicked **Next**

---

### ✅ Step 5: Assign Target Users
- Selected the **Standard User** created in Task 1
- Clicked **Next**

---

### ✅ Step 6: Set Launch Time & Options
- Chose **Launch Now**
- Enabled **Training assignment for compromised users**
- Clicked **Next**

---

### ✅ Step 7: Review & Launch
- Reviewed summary of simulation settings
- Clicked **Launch Simulation**
- Simulation status showed as *"Running"*

---

## 🧪 Testing & Results
- Logged in as the standard user and observed phishing email
- Clicked test link to trigger compromise
- Confirmed:
  - Admin received report
  - User was automatically enrolled in training

---

## 📸 Screenshot Evidence
Stored in `/screenshots/`:
- Simulation wizard steps
- User assignment screen
- Final simulation summary
- Compromised user notification

---

## 🔐 Why This Matters
Attack simulation helps build a security-aware culture. It exposes users to realistic phishing tactics and reinforces protective behavior through immediate training — a crucial skill for security leaders and blue teams.

---

## 🔗 Tools Used
- Microsoft Defender for Office 365  
- Microsoft 365 Defender Portal  
- Outlook Web Access (for phishing test)
