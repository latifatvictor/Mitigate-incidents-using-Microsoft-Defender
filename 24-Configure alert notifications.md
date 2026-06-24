# 📧 Microsoft Defender for Endpoint – Configure Alert Notifications (Summary)

## 📌 Overview
Alert notifications send **email alerts** to designated users when threats are detected.

✅ Purpose:
- Ensure immediate awareness of security incidents  
- Enable fast response by SOC teams  

---

## 🧠 Key Concept

✅ Alert Notifications = **Real-Time Security Awareness**

- Notify the right people  
- Based on severity and scope  
- Improve response time  

---

## ⚠️ Permissions Required

✅ Can configure notifications:

- Users with **Manage security settings** permission  
- Security Administrator  
- Global Administrator  

---

## 📊 Notification Features

✅ You can configure:

- Alert severity levels (Low → High)  
- Target devices (all or specific groups)  
- Email recipients  

✅ Emails include:
- Alert summary  
- Severity level  
- Link to Defender portal  

---

## 🔐 RBAC Behaviour

✅ If RBAC is used:

- Notifications are limited to assigned device groups  
- Users only receive alerts within their scope  

⚠️ Note:
- Only Global Admin can manage rules across all device groups  

---

## ⚙️ Create Alert Notification Rule

Step 1 > Go to https://security.microsoft.com  
Step 2 > Settings > Endpoints  
Step 3 > Select Email notifications  
Step 4 > Click + Add item  

---

### 🧩 Step 5 – Configure General Settings

Enter:

- Rule name  
- Include organisation name (optional)  
- Include tenant portal link  
- Include device information  

---

### 💻 Step 6 – Select Scope

Choose:

- All devices (Global Admin only)  
OR  
- Specific device groups  

---

### 🚨 Step 7 – Select Alert Severity

Choose level:

- High  
- Medium  
- Low  

✅ Define when notifications are triggered  

---

### 📧 Step 8 – Add Recipients

Step 1 > Enter email address  
Step 2 > Click Add recipient  
Step 3 > Add multiple recipients (optional)  

---

### ✅ Step 9 – Test Notification

Step 1 > Click Send test email  

✅ Ensures:
Emails are working correctly  

---

### 💾 Step 10 – Save Rule

Step 1 > Click Save  

✅ Alert notification rule created  

---

## ✅ Summary Flow

Define Rule > Set Severity > Select Devices > Add Recipients > Test > Save  

---

## 🧠 Key Takeaways

- Notifications improve response time  
- Can be customised by severity and device group  
- RBAC limits visibility and scope  
- Test emails ensure proper setup  
- Critical for SOC communication  

---

## 🔐 Security Insight

👉 Awareness = Speed  

The faster your team knows →  
the faster they can respond to threats  
