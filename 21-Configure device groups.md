# 💻 Microsoft Defender XDR – Configure Device Groups (Summary)

## 📌 Overview
Device groups allow you to:

- Organise endpoints based on attributes  
- Control access to devices and alerts  
- Apply different security policies  

✅ Purpose:
Segment devices for **security, visibility, and control**  

---

## 🧠 Key Concept

✅ Device Groups = **Access + Control Boundaries**

- Limit what users can see  
- Control remediation behaviour  
- Improve investigation efficiency  

---

## ⚙️ What Device Groups Are Used For

- Restrict access using RBAC roles  
- Configure automated remediation levels  
- Apply different investigation settings  
- Filter devices during investigations  

✅ Example:
Finance devices vs IT devices  

---

## 🧩 Grouping Criteria

Devices can be grouped by:

- Device name  
- Domain  
- Tags  
- Operating system  

✅ Matching rules determine group membership  

---

## ⚠️ Group Priority (Ranking)

- Devices can match multiple groups  
- Only assigned to **highest-ranked group**  

✅ Importance:
Controls which policies apply  

---

## ⚙️ Create Device Group

Step 1 > Go to https://security.microsoft.com  
Step 2 > Settings > Endpoints  
Step 3 > Permissions > Device groups  
Step 4 > Click + Add device group  

---

### Step 5 – Configure Group

- Enter group name  
- Set remediation level  
- Define matching rules  

---

### Step 6 – Preview Devices

Step 1 > Review matched devices  
Step 2 > Validate grouping logic  

✅ Ensures correct targeting  

---

### Step 7 – Assign Access

Step 1 > Go to User access tab  
Step 2 > Assign Microsoft Entra user group  

✅ Note:
Only groups with RBAC roles can be assigned  

---

### Step 8 – Save

Step 1 > Click Close  
Step 2 > Apply configuration  

✅ Device group created  

---

## 🔄 Automated Remediation Levels

Device groups allow you to:

- Set automation level (Full / Semi / Manual)  
- Control how threats are handled  

✅ Example:
Critical systems → require approval  
Standard devices → auto remediation  

---

## 🔍 Use in Investigations

Step 1 > Open incident or device list  
Step 2 > Apply Group filter  

✅ Helps:
Focus investigations on specific environments  

---

## ✅ Summary Flow

Define Criteria > Create Group > Assign Users > Apply Policies > Manage Devices  

---

## 🧠 Key Takeaways

- Device groups segment endpoints  
- Control access + visibility  
- Enable targeted security policies  
- Ranking determines policy priority  
- Essential for large enterprise environments  

---

## 🔐 Security Insight

👉 Segmentation = Security  

Not all devices should be treated the same  
Critical systems need stricter control  
