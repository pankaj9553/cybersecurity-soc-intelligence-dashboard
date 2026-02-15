# 🚨 Enterprise Cybersecurity SOC Intelligence Dashboard (Power BI)

## 📌 Project Overview

This project showcases an enterprise-level **Cybersecurity Security Operations Center (SOC) Intelligence Dashboard** built using **Power BI**.

The dashboard simulates a real-world SOC monitoring environment and provides:

- Executive cyber risk visibility  
- Live threat intelligence monitoring  
- Threat pattern analysis  
- Incident response performance tracking  
- System & infrastructure risk assessment  

The solution follows a **Star Schema data model**, advanced **DAX measures**, and executive-level dashboard design principles.

---

## 🎯 Project Objectives

- Monitor global cyber attack trends  
- Analyze attack types and MITRE ATT&CK tactics  
- Measure detection and response efficiency (MTTD & MTTR)  
- Identify high-risk systems and infrastructure  
- Provide executive-level cybersecurity decision intelligence  

---

## 🗂 Dashboard Pages

### 1️⃣ Executive Cyber Risk Overview
High-level enterprise cyber posture including:
- Total cyber attacks
- High severity attacks
- Risk severity score
- Attack growth %
- Geographic distribution
- System exposure overview

---

### 2️⃣ Live Attack Intelligence
SOC monitoring view including:
- Daily attack activity
- Critical attack tracking
- Top malicious IP addresses
- Protocol-based analysis
- Geographic threat visualization

---

### 3️⃣ Threat Pattern Analysis
Analytical threat intelligence including:
- Attack type distribution
- DDoS % and Phishing %
- Critical attack percentage
- Traffic volume analysis
- MITRE tactic breakdown
- Threat reputation distribution

---

### 4️⃣ Incident Response Performance
Operational efficiency analysis including:
- MTTD & MTTR trends
- Escalation rate
- Closed vs open incidents
- Root cause analysis
- Critical resolution time

---

### 5️⃣ System & Asset Risk Dashboard
Infrastructure exposure analysis including:
- Total attacks per system
- High severity attacks per system
- Risk score by asset
- Business criticality index
- System attack trends

---

## 📊 Key KPIs

- Total Cyber Attacks  
- High Severity Attacks  
- MTTD (Mean Time To Detect)  
- MTTR (Mean Time To Respond)  
- Risk Severity Score  
- Escalation Rate  
- Business Criticality Index  

---

## 🏗 Data Model Architecture

The dashboard follows a **Star Schema** design.

### Fact Tables
- `Security_Events`
- `Incident_Response`
- `Network_Traffic`

### Dimension Tables
- `Attack_Type`
- `Severity`
- `Country`
- `Affected_System`
- `IP_Address`
- `Date_Table`

Relationships are configured as:
- One-to-Many
- Single direction filtering
- `Security_Events` as the central fact table

---

## 🛠 Tools & Technologies

- Power BI Desktop  
- DAX (Advanced Measures & Time Intelligence)  
- Star Schema Data Modeling  
- MITRE ATT&CK Framework Mapping  

---

## 📈 Key Insights

- DDoS accounts for **35.7%** of total attacks.
- Critical and Severe attacks represent nearly **30%** of incidents.
- Escalation rate is high (**67.45%**), indicating operational pressure.
- Firewall and Cloud infrastructure show the highest exposure.
- Detection time is efficient, but response optimization is needed.

---


---

## 🚀 How to Use

1. Download the `.pbix` file.
2. Open in Power BI Desktop.
3. Use slicers (Year, Severity, Attack Type, System, Country) to explore.
4. Analyze trends and operational performance metrics.

---

## 👨‍💻 Author

**Pankaj Yadav**  
Data Analyst | Business Intelligence & Cyber Analytics Enthusiast  

---

⭐ If you found this project valuable, consider giving the repository a star!


