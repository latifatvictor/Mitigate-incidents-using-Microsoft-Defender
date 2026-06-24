# 🎯 Microsoft Defender XDR – Manage Indicators (IoCs) (Summary)

## 📌 Overview
Indicators of Compromise (IoCs) allow you to:

- Detect threats  
- Block malicious activity  
- Allow trusted entities  

✅ Purpose:
Enable **proactive detection and prevention** of threats  

---

## 🧠 Key Concept

✅ IoCs = **Custom Detection & Prevention Rules**

- Define what to:
  - Allow ✅  
  - Monitor (Audit) ⚠️  
  - Block ❌  

---

## 🔗 Engines Using Indicators

Indicators are used by:

- Cloud detection engine  
- Endpoint prevention (Defender AV)  
- Automated Investigation & Remediation (AIR)  

✅ Result:
Consistent enforcement across detection + response  

---

## 🧩 Supported Indicator Types

### 📁 Files
- Based on file hash (SHA1/SHA256)

---

### 🌐 Network Indicators

- IP addresses  
- URLs  
- Domains  

---

### 🔐 Certificates

- Signed application certificates  

---

## ⚙️ Supported Actions

### 📁 Files

- Allow  
- Audit (alert only)  
- Warn (user can bypass)  
- Block execution  
- Block and remediate  

---

### 🌐 IPs / URLs / Domains

- Allow  
- Audit  
- Warn  
- Block  

---

### 🔐 Certificates

- Allow  
- Block  

---

## ⚙️ Manage Indicators

Step 1 > Go to https://security.microsoft.com  
Step 2 > Settings > Endpoints  
Step 3 > Rules > Indicators  
Step 4 > Select indicator type  
Step 5 > Create / Edit / Delete  

---

## 📁 Create File Indicator

Step 1 > Add file hash (SHA1/SHA256)  
Step 2 > Choose action (Block, Allow, etc.)  
Step 3 > Define scope (device group)  
Step 4 > Set expiration  
Step 5 > Save  

✅ Use case:
Block known malware  

---

## 🌐 Create IP / URL Indicator

Step 1 > Add IP / URL / Domain  
Step 2 > Select action (Block recommended)  
Step 3 > Set scope  
Step 4 > Save  

✅ Requirements:
- Network protection enabled  
- Custom indicators enabled  

---

## 🔐 Create Certificate Indicator

Step 1 > Upload certificate (.CER / .PEM)  
Step 2 > Choose Allow or Block  
Step 3 > Set scope  
Step 4 > Save  

✅ Use case:
Allow trusted apps OR block malicious signed software  

---

## 📥 Import Indicators (Bulk)

Step 1 > Upload CSV file  
Step 2 > Define:
- Indicator type  
- Action  
- Severity  
- Scope  
Step 3 > Import  

✅ Useful for:
Threat intelligence feeds  

---

## ⏱ Key Limitations

- Max 15,000 indicators per tenant  
- File support mainly for .exe / .dll  
- IP ranges (CIDR) not supported  
- Blocking may take a few minutes  

---

## ✅ Summary Flow

Identify Threat → Create Indicator → Apply Action → Monitor Enforcement  

---

## 🧠 Key Takeaways

- IoCs enable proactive threat defense  
- Work across detection, prevention, and response  
- Can block files, domains, and certificates  
- Support automation and threat intelligence  
- Critical tool for SOC analysts  

---

## 🔐 Security Insight

👉 Indicators = Control Over Threats  

Instead of waiting for detections →  
You define what is malicious  
