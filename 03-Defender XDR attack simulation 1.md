# 🚨 Defender XDR Attack Simulation – Suspicious Phishing & Endpoint Compromise

## 📌 Scenario
A user receives a phishing email and unknowingly clicks a malicious link, leading to:

- Credential compromise  
- Suspicious login  
- Malicious process execution on endpoint  

---

## 🎯 Objective
Simulate a real-world SOC investigation using Microsoft Defender XDR:

✅ Detect  
✅ Investigate  
✅ Contain  
✅ Remediate  
✅ Recover  

---

## 🧩 Stage 1 – Initial Attack (Phishing)

### 🦠 What Happens
- User receives phishing email  
- Clicks malicious link  
- Enters credentials  

---

### 🔍 Detection Signals

- Email flagged in Defender for Office 365  
- Suspicious URL click detected  
- Unusual sign-in activity  

---

## 🧩 Stage 2 – Identity Compromise

### 🔍 Detection

Step 1 > Alert: Suspicious sign-in  
Step 2 > Location anomaly (impossible travel)  
Step 3 > Multiple login attempts  

✅ Defender Source:
- Defender for Identity  
- Entra ID sign-in logs  

---

## 🧩 Stage 3 – Endpoint Compromise

### 🦠 What Happens
- Malware downloads  
- Suspicious process launches  

---

### 🔍 Detection

Step 1 > Alert: Malware detected  
Step 2 > Suspicious process execution  
Step 3 > Device flagged at risk  

✅ Defender Source:
- Defender for Endpoint  

---

## 🧩 Stage 4 – Incident Creation

✅ Defender XDR automatically:

- Correlates alerts  
- Groups them into ONE incident  

➡ Incident includes:
- Email alert  
- Identity alert  
- Endpoint alert  

---

## 🔎 SOC Investigation

### Step 1 – Open Incident

Step 1 > Go to Defender portal  
Step 2 > Open incident queue  
Step 3 > Select high severity incident  

---

### Step 2 – Review Alerts

Step 1 > Check all related alerts  
Step 2 > Identify attack timeline  
Step 3 > Confirm phishing origin  

---

### Step 3 – Analyse Timeline

Step 1 > Review device timeline  
Step 2 > Track process execution  
Step 3 > Identify malicious file  

---

### Step 4 – Identify Impact

- Compromised user  
- Affected endpoint  
- Possible lateral movement  

---

## 🛑 Containment Actions

Step 1 > Disable user account  
Step 2 > Revoke active sessions  
Step 3 > Force password reset  

Step 4 > Isolate infected device  
Step 5 > Stop malicious process  

---

## 🛡 Remediation Actions

Step 1 > Run antivirus scan  
Step 2 > Remove malicious files  
Step 3 > Block malicious URL/IP  
Step 4 > Add indicator (block hash/file)  

---

## 🔄 Recovery

Step 1 > Re-enable user account  
Step 2 > Confirm secure sign-in  
Step 3 > Monitor for re-occurrence  

---

## 🧠 Lessons Learned

- Phishing is common entry vector  
- MFA could prevent credential misuse  
- Defender XDR correlates attack signals  
- Fast response limits damage  

---

## ✅ SOC Full Flow

Phishing → Credential Theft → Endpoint Compromise  
→ Incident Created → Investigate → Contain → Remediate → Recover  

---

## 🔐 Key Defender Features Used

- Defender for Office → Email detection  
- Defender for Identity → Suspicious login  
- Defender for Endpoint → Malware detection  
- Defender XDR → Correlated incident  

---

## 🚀 Skills Demonstrated

✅ Threat detection  
✅ Incident investigation  
✅ Endpoint analysis  
✅ Identity protection  
✅ Incident response  

---

## 🔥 Pro SOC Tip

👉 Always follow the attack chain:

Initial Access → Execution → Persistence → Impact  

(Not just individual alerts)
``
