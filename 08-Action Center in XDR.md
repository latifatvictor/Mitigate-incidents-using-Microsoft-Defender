# ⚙️ Microsoft Defender XDR – Action Center (Summary)

## 📌 Overview
The **Action Center** is a central place to manage:

- Pending remediation actions  
- Completed security actions  
- Automated and manual responses  

✅ Purpose:
Provide a **single pane of glass** for response actions across:
- Endpoints  
- Email  
- Identities  

---

## 🧠 Key Concept

✅ Action Center = **Response Control Hub**

- View what actions were taken  
- Approve or reject actions  
- Track investigation outcomes  

---

## 📊 Action Center Tabs

### ⏳ Pending

✅ Shows:
- Actions that require approval  

Step 1 > Open Pending tab  
Step 2 > Select investigation  
Step 3 > Review recommendations  
Step 4 > Approve or reject  

✅ Appears only when actions need approval  

---

### 📜 History

✅ Shows:
- Completed remediation actions  
- Automated responses  
- Manual actions  
- Live response commands  

Step 1 > Open History tab  
Step 2 > Select action  
Step 3 > View details  

✅ Acts as:
Audit log for all actions  

---

## 🔍 Review Pending Actions

Step 1 > Select item  
Step 2 > Review evidence  
Step 3 > Open investigation (optional)  
Step 4 > Approve / Reject  

✅ Tip:
You can approve multiple actions at once  

---

## ✅ Review Completed Actions

Step 1 > Go to History  
Step 2 > Select action  
Step 3 > View:
- Source  
- Details  
- Outcome  

---

## 🔄 Undo Actions

✅ You can reverse actions if needed:

- Isolate device  
- Quarantine file  
- Stop service  
- Remove registry key  
- Remove scheduled task  

Step 1 > Select action in History  
Step 2 > Click Undo  

✅ Use case:
False positive remediation  

---

## 📁 Apply to Multiple Instances

Step 1 > Select quarantined file  
Step 2 > Apply Undo to all instances  

✅ Saves time across multiple devices  

---

## 🧭 Action Sources

Each action shows where it came from:

- Manual device action  
- Manual email action  
- Automated device action (AIR)  
- Automated email action  
- Advanced hunting action  
- Live response action  

✅ Helps track origin of actions  

---

## 📤 Submissions (Threat Analysis)

Admins can submit:

- Emails  
- URLs  
- Attachments  

To Microsoft for analysis  

---

### 🔍 Submit Content

Step 1 > Go to Submissions  
Step 2 > Select type (Email / URL / File)  
Step 3 > Choose reason:
- False positive  
- False negative  
Step 4 > Submit  

---

## 📬 User Reported Messages

Step 1 > View user submissions  
Step 2 > Analyse reported threat  
Step 3 > Mark:
- Phishing  
- Spam  
- Clean  

✅ Can notify users automatically  

---

## 🔄 Convert to Admin Submission

Step 1 > Select user report  
Step 2 > Submit to Microsoft  
Step 3 > Choose category  

✅ Ensures proper analysis  

---

## ✅ Summary Flow

Alert → Investigation → Remediation Action → Review in Action Center → Approve / Undo  

---

## 🧠 Key Takeaways

- Central hub for remediation actions  
- Tracks both manual and automated responses  
- Enables approval workflows  
- Supports undo actions  
- Improves SOC visibility and control  

---

## 🔐 Security Insight

👉 Response visibility = Control  

If you can’t see actions → you can’t trust outcomes  
