# 🚨 Microsoft Defender XDR – Manage & Investigate Alerts (Summary)

## 📌 Overview
Alerts are **individual detections of suspicious or malicious activity**.

✅ Purpose:
- Provide early warning signals  
- Help identify potential attacks  
- Enable investigation and response  

---

## 🧠 Key Concept

✅ Alert = Single detection  
✅ Incident = Collection of alerts  

👉 Always:
Investigate alerts → understand context → link to incident  

---

## 🛠 Alert Management

Step 1 > Go to Alerts queue or Device page  
Step 2 > Select alert  
Step 3 > Open Alert management pane  

✅ From here you can:
- View details  
- Set metadata  
- Take actions  

---

## 📊 Alert Severity Levels

### 🔴 High
- Advanced attacks (APT, ransomware, credential theft)  
- High organisational risk  

---

### 🟠 Medium
- Suspicious behaviour  
- Possible attack activity  
- Requires investigation  

---

### 🟡 Low
- Common malware or tools  
- Limited organisational impact  

---

### ⚪ Informational
- No direct threat  
- Awareness or logging  

---

✅ Key Insight:
Severity = **organisational risk (not just device impact)**  

---

## 🧩 Alert Categories (MITRE ATT&CK)

Alerts are mapped to attack tactics:

- Initial access  
- Execution  
- Persistence  
- Privilege escalation  
- Defense evasion  
- Credential access  
- Discovery  
- Lateral movement  
- Command & control  
- Exfiltration  
- Impact (e.g. ransomware)  

✅ Helps understand attacker behaviour  

---

## 🔗 Link Alerts to Incidents

Step 1 > Create new incident OR  
Step 2 > Link to existing incident  

✅ Goal:
Build full attack picture  

---

## 👤 Assign Alerts

Step 1 > Select alert  
Step 2 > Click Assign to me  

✅ Ensures ownership + accountability  

---

## 🔕 Suppress Alerts

Step 1 > Create suppression rule  
Step 2 > Choose scope:
- Device only  
- Entire organisation  

✅ Use cases:
- Known safe processes  
- Reduce noise / false positives  

⚠️ Note:
Applies only to future alerts  

---

## 🔄 Alert Status

- New → Not yet reviewed  
- In Progress → Under investigation  
- Resolved → Completed  

✅ Helps manage workflow  

---

## ✅ Alert Classification

Step 1 > Mark as:
- True positive  
- False positive  

Step 2 > (Optional) Add determination  

✅ Improves detection accuracy over time  

---

## 📝 Comments & History

Step 1 > Add notes  
Step 2 > Track changes  

✅ Enables SOC collaboration  

---

## 🔍 Alert Investigation

Step 1 > Open alert  
Step 2 > Review details  
Step 3 > Analyse affected assets  
Step 4 > Explore alert story  

---

## 🌳 Alert Story (Key Feature)

✅ Shows:
- Why alert triggered  
- Related events  
- Attack sequence  

Step 1 > Select entity  
Step 2 > Expand details  
Step 3 > Analyse behaviour  

---

## ⚙️ Investigate Entities

From alert you can investigate:

- Devices  
- Users  
- Files  
- Processes  
- Emails  

✅ Each entity is clickable + expandable  

---

## 🛠 Take Action (From Alert)

Step 1 > Select entity  
Step 2 > Use actions from pane  

Common actions:
- Isolate device  
- Stop process  
- Block file/IP  
- Reset user credentials  

---

## ✅ Close Alert

Step 1 > Complete investigation  
Step 2 > Set status = Resolved  
Step 3 > Classify alert  

✅ Improves future detection quality  

---

## 🔄 Alert Investigation Flow

Open Alert > Review Details > Analyse Story > Investigate Entities > Take Action > Resolve  

---

## 🧠 Key Takeaways

- Alerts are starting point of investigation  
- Severity reflects organisational impact  
- MITRE categories show attacker tactics  
- Suppression reduces noise  
- Proper classification improves security  

---

## 🔐 Security Insight

👉 Alerts = Signal  

Without investigation → noise  
With context → actionable intelligence  
