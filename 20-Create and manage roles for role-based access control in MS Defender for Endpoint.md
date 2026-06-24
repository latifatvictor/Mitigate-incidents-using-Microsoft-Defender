# 🔐 Microsoft Defender XDR – Create & Manage RBAC Roles (Summary)

## 📌 Overview
Role-Based Access Control (RBAC) in Microsoft Defender enables you to:

- Create custom roles  
- Assign permissions  
- Control access to devices and actions  

✅ Purpose:
Enforce **least privilege access** across security operations  

---

## 🧠 Key Concept

✅ RBAC Roles = **Granular Permission Control**

- Define what users can see  
- Define what users can do  
- Restrict access to specific devices  

---

## ⚠️ Requirements

- Role: Security Administrator  
- Existing Microsoft Entra user groups  

✅ Best Practice:
Use least privilege  
Avoid Global Administrator unless necessary  

---

## ⚙️ Create a Role

Step 1 > Go to https://security.microsoft.com  
Step 2 > Settings > Endpoints  
Step 3 > Permissions > Roles  
Step 4 > Click Turn on roles  
Step 5 > Select + Add item  
Step 6 > Enter:
- Role name  
- Description  
Step 7 > Select required permissions  
Step 8 > Click Next  
Step 9 > Assign to Microsoft Entra group  
Step 10 > Click Save  

✅ Result:
Custom role created and assigned  

---

## 🔗 Assign Device Access

Step 1 > Create device groups  
Step 2 > Assign role to device group  

✅ Purpose:
Control which devices users can access  

---

## 🔑 Permission Categories

---

### 👁 View Data

- Security operations data  
- Vulnerability management data  

✅ Read-only access  

---

### ⚙️ Active Remediation Actions

- Take response actions  
- Approve/dismiss automated remediation  
- Manage allow/block indicators  

✅ Used by SOC responders  

---

### 🛠 Threat & Vulnerability Management

- Exception handling  
- Remediation tracking  
- Application blocking/unblocking  
- Security baseline assessments  

✅ Manage risk and vulnerabilities  

---

### 🚨 Alerts Investigation

- Investigate alerts  
- Start automated investigations  
- Run scans  
- Collect forensic data  
- Manage device tags  

✅ Core SOC responsibilities  

---

### ⚙️ Security Settings Management

- Configure alert suppression  
- Manage onboarding/offboarding  
- Control notifications  

✅ Administrative controls  

---

### 📱 Endpoint Security (Intune)

- Configure endpoint protection  
- Manage compliance settings  
- Access Intune Endpoint Security  

✅ Integration with Intune  

---

### 💻 Live Response Capabilities

#### ✅ Basic
- Start live response session  
- Run read-only commands  

---

#### ✅ Advanced
- Upload/download files  
- Execute scripts remotely  
- Perform deep investigations  

---

## ✅ Summary Flow

Create Role → Assign Permissions → Link Entra Group → Assign Device Group  

---

## 🧠 Key Takeaways

- RBAC enables precise access control  
- Roles define actions users can perform  
- Device groups limit visibility  
- Least privilege reduces security risk  
- Proper role design is critical for SOC operations  

---

## 🔐 Security Insight

👉 Access Control = Security Control  

Too much access = risk  
Right access = secure operations  
