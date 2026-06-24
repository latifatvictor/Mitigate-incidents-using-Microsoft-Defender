# ⚙️ Microsoft Defender for Endpoint – Advanced Features (Summary)

## 📌 Overview
The **Advanced Features** section allows you to enable or disable key security capabilities in Defender for Endpoint.

✅ Purpose:
- Enhance protection  
- Improve investigation capabilities  
- Enable integrations with other security tools  

---

## 🧠 Key Concept

✅ Advanced Features = **Security Enhancements & Integrations**

- Extend detection and response capabilities  
- Automate protection  
- Improve visibility across environments  

---

## 🖥 Where to Access

Step 1 > Go to https://security.microsoft.com  
Step 2 > Settings > Endpoints  
Step 3 > Advanced features  
Step 4 > Toggle features On/Off  
Step 5 > Click Save  

---

## 🤖 Core Security Features

---

### 🔄 Automated Investigation (AIR)

- Enables automated investigation and remediation  
- Uses AI to analyse alerts  

✅ Recommendation:
Enable ✅  

---

### 💻 Live Response

- Remote investigation on devices  
- Requires AIR enabled  

✅ Includes:
- Basic commands (read-only)  
- Advanced commands (scripts, file actions)  

---

### 🧠 Live Response (Servers & Scripts)

- Enable for servers  
- Allow unsigned script execution  

✅ Use carefully (higher risk)  

---

### 🛡 Always Remediate PUA

- Automatically remove unwanted applications  

✅ Protects users from unsafe software  

---

## 🔐 Protection Features

---

### 🧱 EDR in Block Mode

- Blocks threats even if AV is passive  

✅ Strong post-breach protection  

---

### 🧬 Tamper Protection

- Prevents disabling security settings  

✅ Critical feature → KEEP ON  

---

### 📁 Allow / Block File

- Block malicious files across organisation  

✅ Uses indicators (IOCs)  

---

### 🌐 Custom Network Indicators

- Block/allow:
  - IP addresses  
  - URLs  
  - Domains  

✅ Requires network protection enabled  

---

## ⚙️ Incident & Alert Behaviour

---

### 🔄 Auto-Resolve Alerts

- Closes alerts that are remediated  

✅ Reduces alert noise  

---

### 🔒 Restrict Alert Correlation

- Limits correlations to device groups  

⚠️ Not recommended in most cases  
(lose full attack visibility)  

---

## 🔗 Integrations

---

### 🧠 Defender for Identity

- Adds identity-based insights  
- Improves investigation scope  

---

### ☁️ Defender for Cloud Apps

- Shares endpoint signals with cloud apps  

---

### 📧 Office 365 Threat Intelligence

- Correlates email + endpoint threats  

---

### 📱 Microsoft Intune

- Enables device risk-based Conditional Access  

✅ Important:
Must enable in both Intune & Defender  

---

### 🔍 Microsoft Purview

- Share alerts for insider risk management  

---

## 📡 Visibility & User Insights

---

### 👤 Show User Details

- Displays user info (name, role, department)  

✅ Helps investigations  

---

### 💬 Skype / Communication Integration

- Contact users during incidents  

---

## 🌐 Web & Network Protection

---

### 🌍 Web Content Filtering

- Block harmful websites  
- Monitor web activity  

---

### 🔍 Device Discovery

- Identify unmanaged devices  

✅ Improves visibility  

---

## 🧪 Other Features

---

### 🚀 Preview Features

- Access early features  

---

### 📥 Download Quarantined Files

- Retrieve files for analysis  

---

## ✅ Summary Flow

Enable Features → Improve Protection → Enhance Visibility → Integrate Tools  

---

## 🧠 Key Takeaways

- Advanced features enhance Defender capabilities  
- Critical features: AIR, EDR block mode, Tamper protection  
- Integrations improve investigation depth  
- Alerts can be automated and optimised  
- Device discovery adds visibility  

---

## 🔐 Security Insight

👉 Security = Layers  

Detection + Prevention + Automation + Integration  

All must work together for strong defense  
