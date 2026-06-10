# 🔴 Defender XDR Attack Simulation – Ransomware Attack

## 📌 Scenario
An attacker gains initial access to your environment and deploys ransomware across endpoints, leading to:

- File encryption  
- Possible data exfiltration  
- Business disruption  

---

## 🎯 Objective

Simulate a ransomware attack lifecycle and respond using Microsoft Defender XDR:

✅ Detect  
✅ Investigate  
✅ Contain  
✅ Eradicate  
✅ Recover  

---

## 🧩 Stage 1 – Initial Access (Phishing / Credentials)

### 🦠 What Happens
- User clicks phishing link OR credentials stolen  
- Attacker gains access to account  

---

### 🔍 Detection

- Suspicious login alert  
- Impossible travel  
- Multiple failed login attempts  

✅ Source:
- Defender for Identity  
- Entra ID  

---

## 🧩 Stage 2 – Lateral Movement

### 🦠 What Happens
- Attacker moves across network  
- Attempts to access other systems  
- Uses compromised credentials  

---

### 🔍 Detection

Step 1 > Alert: Unusual authentication activity  
Step 2 > Multiple device access attempts  
Step 3 > Privilege escalation attempts  

✅ Source:
- Defender for Identity  
- Defender for Endpoint  

---

## 🧩 Stage 3 – Ransomware Execution

### 🦠 What Happens
- Malicious executable launched  
- Files encrypted  
- Ransom note created  

---

### 🔍 Detection

Step 1 > Alert: Ransomware behaviour detected  
Step 2 > File modifications spike  
Step 3 > Suspicious process execution  

✅ Source:
- Defender for Endpoint  

---

## 🧩 Stage 4 – Incident Creation

✅ Defender XDR automatically:

- Correlates all alerts  
- Creates a single high-severity incident  

---

## 🚨 SOC Investigation

### Step 1 – Open Incident

Step 1 > Go to Defender portal  
Step 2 > Open incident queue  
Step 3 > Identify high severity incident  

---

### Step 2 – Review Attack Chain

Step 1 > Analyse alerts  
Step 2 > Identify entry point  
Step 3 > Track lateral movement  
Step 4 > Confirm ransomware activity  

---

### Step 3 – Analyse Device Timeline

Step 1 > Open affected device  
Step 2 > Review processes  
Step 3 > Identify malicious executable  

---

### Step 4 – Assess Impact

- Number of devices affected  
- Encrypted files  
- User accounts impacted  
- Potential data exfiltration  

---

## 🛑 Containment Actions (Critical)

Step 1 > Isolate infected devices  
Step 2 > Disable compromised accounts  
Step 3 > Revoke active sessions  

✅ Priority:
Stop spread immediately  

---

## 🧹 Remediation Actions

Step 1 > Remove malware  
Step 2 > Block malicious files (hash)  
Step 3 > Block IP/domains  
Step 4 > Run antivirus scans  

---

## 🔄 Recovery Actions

Step 1 > Restore files from backup  
Step 2 > Rebuild affected systems  
Step 3 > Validate system integrity  
Step 4 > Monitor environment  

---

## 🧠 Lessons Learned

- Ransomware often starts with phishing  
- Early detection reduces impact  
- Endpoint visibility is critical  
- Backups are essential  

---

## ✅ SOC Full Flow

Initial Access → Lateral Movement → Execution → Encryption  
→ Incident Created → Contain → Eradicate → Recover  

---

## 🔐 Key Defender Features Used

- Defender for Identity → Account compromise detection  
- Defender for Endpoint → Ransomware detection  
- Defender XDR → Incident correlation  

---

## 🚨 Indicators of Compromise (IOCs)

- Unusual login locations  
- Rapid file modifications  
- Suspicious executable files  
- Unknown admin activity  

---

## 🚀 Skills Demonstrated

✅ Ransomware detection  
✅ Incident response  
✅ Endpoint investigation  
✅ Threat containment  
✅ Recovery planning  

---

## 🔥 Pro SOC Tip

👉 In ransomware attacks:

Containment > Investigation  

Stop the spread FIRST, then analyse  

---

## 🧠 Advanced Insight

👉 Ransomware = Business Risk  

Not just security issue → impacts operations, revenue, reputation  
