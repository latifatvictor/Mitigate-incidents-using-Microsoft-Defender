# 🔐 Microsoft Defender XDR – Manage Access (RBAC) (Summary)

## 📌 Overview
Role-Based Access Control (RBAC) allows you to:

- Control who can access the Defender portal  
- Define what actions users can perform  
- Limit visibility to specific devices  

✅ Purpose:
Ensure secure and controlled access to security operations  

---

## 🧠 Key Concept

✅ RBAC = **Least Privilege Access**

- Give users only the permissions they need  
- Reduce risk of misuse or over-privilege  

---

## 🧩 RBAC Core Components

### 👤 Roles

- Define what actions users can perform  
- Can create custom roles  

✅ Examples:
- Security Administrator (full access)  
- Security Reader (read-only)  

---

### 👥 User Groups

- Microsoft Entra groups assigned to roles  
- Controls who gets access  

---

### 💻 Device Groups

- Group devices based on:
  - Name  
  - Domain  
  - Tags  

✅ Determines:
What devices users can see/manage  

---

## ⚙️ What RBAC Controls

- Who can view alerts/incidents  
- Who can take response actions  
- Which devices users can access  
- What level of control each role has  

---

## 🧠 How RBAC Works

Step 1 > Create roles (permissions)  
Step 2 > Assign roles to Entra user groups  
Step 3 > Assign device access via device groups  

✅ Result:
Granular control over access + actions  

---

## 🔄 Unified RBAC (URBAC)

✅ From Feb 2025:
- New tenants use **Unified RBAC (URBAC)**  

✅ Benefits:
- Centralised permissions across Defender products  
- Simplified access management  
- Consistent control model  

---

## 🔑 Default Access Levels

- Security Administrator → Full access  
- Global Administrator → Full access (not recommended)  
- Security Reader → Read-only access  

⚠️ Note:
Global Admin = highly privileged → use only in emergencies  

---

## ✅ Best Practices

- Apply least privilege principle  
- Use custom roles when needed  
- Limit Global Admin usage  
- Use device groups for segmentation  
- Regularly review access permissions  

---

## ✅ Summary Flow

Define Roles > Assign Users > Configure Device Groups > Control Access  

---

## 🧠 Key Takeaways

- RBAC controls who can see and do what  
- Device groups restrict visibility  
- URBAC simplifies permissions  
- Least privilege improves security  
- Proper access management reduces risk  

---

## 🔐 Security Insight

👉 Access Control = Security Boundary  

Too much access = high risk  
Controlled access = strong defense  
