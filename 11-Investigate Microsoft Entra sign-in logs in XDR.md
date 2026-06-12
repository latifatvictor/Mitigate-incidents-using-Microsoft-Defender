# 🔐 Microsoft Entra – Investigate Sign-in Logs (Summary)

## 📌 Overview
Microsoft Entra **Sign-in Logs** provide visibility into:

- User login activity  
- Authentication attempts  
- Conditional Access policy evaluation  

✅ Purpose:
Detect suspicious sign-ins and investigate identity threats  

---

## 🧠 Key Concept

✅ Sign-in Logs = **Identity Activity Evidence**

- Who signed in  
- When they signed in  
- From where  
- Whether access was successful or blocked  

---

## 🔍 Where to Query Sign-in Logs

### 📊 Option 1 – Defender XDR (Advanced Hunting)

Table: AADSignInEventsBeta

✅ Used for:
- Threat hunting  
- Correlating identity with endpoint/activity data  

---

### 📊 Option 2 – Microsoft Entra / Log Analytics

Table:

SigninLogs

✅ Used for:
- Monitoring login activity  
- Investigating authentication events  

---

### 🖥 Portal View

Step 1 > Go to Azure Portal  
Step 2 > Microsoft Entra ID  
Step 3 > Monitoring > Sign-in logs  

---

## 📊 Key Data Fields

Sign-in logs provide:

- Date & Time  
- User  
- Application accessed  
- Sign-in status (Success / Failure)  
- Conditional Access result  

✅ Helps track authentication behaviour  

---

## 🔐 Conditional Access Insights

You can see:

- Policies applied  
- Policies successful or failed  
- Access granted or blocked  

✅ Use:
Verify security policy effectiveness  

---

## 🔍 Investigation Use Cases

### 🚨 Suspicious Login

- Unusual location  
- Impossible travel  
- Multiple failed attempts  

---

### 🔑 Account Compromise

- Successful login after failures  
- Login from unknown device  
- Risky sign-in  

---

### 🛡 Policy Troubleshooting

- Check why access was blocked  
- Validate MFA enforcement  
- Confirm CA policy behaviour  

---

## ⚙️ Basic Investigation Flow

Step 1 > Query Sign-in Logs  
Step 2 > Identify suspicious activity  
Step 3 > Check location & device  
Step 4 > Review Conditional Access results  
Step 5 > Correlate with incidents  

---

## 🔄 Integration with Defender XDR

✅ Combine with:

- Alerts  
- Incidents  
- Endpoint data  

➡ Provides full attack visibility  

---

## ✅ Summary Flow

Collect Sign-in Data > Analyse User Activity > Check Policies > Identify Risk > Investigate Further  

---

## 🧠 Key Takeaways

- Sign-in logs are critical for identity security  
- Show authentication + access attempts  
- Help detect compromised accounts  
- Essential for Conditional Access validation  
- Integrates with Defender XDR investigations  

---

## 🔐 Security Insight

👉 Identity = Entry Point  

Most attacks start with compromised credentials  
Sign-in logs help detect this early  
