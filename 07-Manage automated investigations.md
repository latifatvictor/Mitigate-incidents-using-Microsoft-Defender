# 🤖 Microsoft Defender XDR – Automated Investigation & Remediation (AIR) (Summary)

## 📌 Overview
Automated Investigation & Remediation (AIR) helps SOC teams:

- Investigate alerts automatically  
- Analyse threats using AI  
- Take remediation actions  

✅ Goal:
Reduce alert fatigue and speed up response  

---

## 🧠 Key Concept

✅ AIR = Automated SOC Analyst  

- Detects threats  
- Investigates root cause  
- Takes (or recommends) action  

---

## 🚀 Why AIR Matters

Without AIR:
- Too many alerts  
- Manual investigation  
- Slow response  

With AIR:
- Faster investigations  
- Reduced alert volume  
- Focus on high-value threats  

---

## ⚙️ How Automated Investigation Starts

Step 1 > Alert is triggered  
Step 2 > Security playbook starts  
Step 3 > Investigation begins automatically  
Step 4 > System checks for spread across devices  

✅ Example:
Malicious file detected → system scans all devices  

---

## 🔍 Investigation Scope Expansion

Step 1 > Detect threat on one device  
Step 2 > Check for same threat on other devices  
Step 3 > Add affected devices to investigation  

✅ Note:
- Large spread (10+ devices) → requires approval  

---

## 📊 Investigation Details

From an investigation you can view:

- Alerts → Triggering alerts  
- Devices → Affected endpoints  
- Evidence → Malicious entities  
- Entities → Files, users, processes  
- Log → Timeline of actions  
- Pending actions → Require approval  

---

## ✅ Verdicts

Each entity is classified as:

- Malicious  
- Suspicious  
- No threats found  

✅ Helps determine next steps  

---

## 🛠 Remediation Actions

AIR can automatically:

- Quarantine files  
- Stop processes  
- Remove scheduled tasks  
- Block malicious activity  

✅ All actions tracked in:
👉 Action Center (https://security.microsoft.com)

---

## 📍 Action Center

Step 1 > View all investigations  
Step 2 > Check:
- Status  
- Completed actions  
- Pending actions  

✅ Can:
- Approve actions  
- Undo actions  

---

## 🔄 Automation Levels

### ✅ Full Automation (Recommended)

- All remediation actions automatic  
- No approval needed  

✅ Best for:
Fast response + reduced workload  

---

### ⚠️ Semi-Automation

- Some actions automatic  
- Some require approval  

Examples:
- Core folders → require approval  
- Non-core folders → auto  

---

### ❌ No Automation

- No automated investigation  
- No automated response  

⚠️ Not recommended  

---

## 🧠 Key Takeaways

- AIR reduces manual SOC effort  
- Automates investigation + response  
- Scales across multiple devices  
- Improves response speed  
- Full automation is recommended  

---

## 🔐 Security Insight

👉 Automation = Force Multiplier  

Without AIR → reactive  
With AIR → proactive & scalable defense  

---

## ✅ Summary Flow

Alert Triggered → Auto Investigation → Analyse Entities → Apply Remediation → Track in Action Center  
