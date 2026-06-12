# 🔎 Microsoft Defender XDR – Advanced Hunting (Summary)

## 📌 Overview
**Advanced Hunting** is a query-based tool that allows you to:

- Search up to 30 days of security data  
- Investigate threats across your environment  
- Proactively hunt for suspicious activity  

✅ Goal:
Find threats BEFORE they become incidents  

---

## 🧠 Key Concept

✅ Advanced Hunting = **Proactive Threat Hunting**

- Not just reacting to alerts  
- Searching for hidden or unknown threats  
- Using queries (KQL) to explore data  

---

## 🔗 Data Sources

Advanced hunting queries data from:

- Defender for Endpoint  
- Defender for Identity  
- Defender for Office 365  
- Defender for Cloud Apps  

✅ Result:
Unified visibility across all domains  

---

## ⚡ Data Types

### 📊 Event Data (Real-Time)

- Alerts  
- Security events  
- System activity  

✅ Updates:
Almost immediately  

---

### 👤 Entity Data

- Users  
- Devices  

✅ Updates:
- Every 15 minutes (partial updates)  
- Fully refreshed every 24 hours  

---

## 🕒 Time Zone

✅ All timestamps = **UTC**

---

## 🗄 Data Schema

✅ Data is organised into tables:

Examples:

- `AlertInfo` → Alert details  
- `DeviceEvents` → Security events  
- `DeviceProcessEvents` → Process activity  
- `DeviceNetworkEvents` → Network connections  
- `IdentityLogonEvents` → Login activity  
- `EmailEvents` → Email activity  

✅ Each table contains:
- Columns (fields)  
- Action types  
- Event data  

---

## 🔍 Build Queries

Step 1 > Open Advanced Hunting  
Step 2 > Select table  
Step 3 > Write KQL query  
Step 4 > Run query  
Step 5 > Analyse results  

✅ Example:
Search for suspicious activity  

---

## ⚙️ Custom Detection Rules

✅ Turn queries into alerts + actions  

Step 1 > Write query  
Step 2 > Ensure required fields:
- Timestamp  
- DeviceId  
- ReportId  
Step 3 > Create detection rule  
Step 4 > Set:
- Severity  
- Category  
- Frequency  
Step 5 > Enable rule  

---

## 🔄 Detection Frequency

- Every 24h  
- Every 12h  
- Every 3h  
- Every 1h  
- Continuous (near real-time)  

✅ Tip:
Use continuous for high-risk threats  

---

## 🎯 Automated Actions

Rules can trigger:

### 💻 Device Actions

- Isolate device  
- Run antivirus scan  
- Collect investigation package  
- Start automated investigation  

---

### 📁 File Actions

- Block file  
- Allow file  
- Quarantine file  

---

## 🎯 Scope

Step 1 > Choose:
- All devices  
- Specific device groups  

✅ Only scoped devices are affected  

---

## 📊 Hunting Graph (Preview)

✅ Visual threat mapping tool  

Shows:
- Entities (users, devices)  
- Relationships (connections, permissions)  
- Attack paths  

---

### 🔍 What You Can Do

- Trace lateral movement  
- Identify high-risk access paths  
- Analyse attack spread  
- Find critical assets at risk  

---

### 🧩 Example Scenarios

- Paths between users/devices  
- Users with access to sensitive data  
- Data exfiltration paths  
- High-risk identity exposure  

---

## 🧠 Investigation Flow

Run Query > Analyse Results > Identify Threat > Create Detection Rule > Take Action  

---

## ✅ Key Takeaways

- Advanced hunting = proactive defense  
- Uses KQL queries to explore data  
- Works across multiple Defender tools  
- Can automate detection + response  
- Graph helps visualise attack paths  

---

## 🔐 Security Insight

👉 Hunting = Advantage  

Attackers hide in noise  
Hunters find them early  

(Not waiting for alerts is key)
