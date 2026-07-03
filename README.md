# Air line on-time Performance Reliability Control tower 
 Airline Operation Analysis  project
#  Airline On Time Performance & Reliability Control Tower

##  Project Overview
This project analyzes airline operational performance with a focus on departure delays, turnaround efficiency, and delay propagation. Inspired by real-world airline operations, the goal is to build a control tower dashboard that enables proactive decision-making and improves on-time performance.

---

##  Objective
To identify key drivers of flight delays and develop an interactive analytics solution that helps operations teams:
- Monitor reliability KPIs  
- Detect high-risk flights early  
- Take data-driven actions to improve punctuality  

---

##  Dataset Description
The project uses a synthetic but realistic dataset including:

- Flight operations data (schedule vs actual)
- Airport performance metrics
- Weather conditions

### Key Fields:
- Departure & arrival delays  
- Turnaround duration  
- Inbound delay  
- Airport congestion index  
- Weather indicators (rain, wind, storm, fog)  

---

##  Tools & Technologies
- **Python (Pandas)** – Data cleaning & preprocessing  
- **Power BI** – Dashboard development & visualization  
- **DAX** – KPI calculations and business metrics  

---

##  Data Preparation
- Cleaned missing and inconsistent values  
- Merged multiple datasets (flight, airport, weather)  
- Converted date/time columns  
- Created derived features:
  - `time_of_day`
  - `delay_status`
  - `risk_level`
  - `turnaround_risk`

---

##  Key Performance Indicators (KPIs)
- **D15 Rate** – % of flights delayed more than 15 minutes  
- **Average Departure Delay**  
- **Delay Propagation Rate**  
- **Turnaround Overrun Rate**  
- **Airport Reliability Index**  

---

##  Key Insights
-  **Inbound delay propagation** is the primary driver of departure delays  
-  Delays accumulate throughout the day, peaking in the afternoon  
-  Major airports experience higher congestion and delays  
-  Turnaround pressure increases later in the day  

---

##  Dashboard Structure

### 1. Executive Summary
- KPI overview  
- Delay distribution  
- Performance snapshot
- <img width="1185" height="691" alt="Screenshot 2026-04-16 112633" src="https://github.com/user-attachments/assets/146e7161-d6be-41e8-beaf-ca9b0edc2a95" />



### 2. Root Cause Analysis
- Delay propagation analysis  
- Time-of-day impact  
- Airport performance
-  <img width="1232" height="732" alt="Screenshot 2026-04-15 170832" src="https://github.com/user-attachments/assets/060289ca-653b-4591-89bb-1018ab7d4455" />


### 3. Action & Recommendations
- High-risk flight identification  
- Intervention priorities  
- Operational improvement plan
-  <img width="1099" height="685" alt="Screenshot 2026-04-15 170858" src="https://github.com/user-attachments/assets/939f40ef-5d6f-438e-a910-3b63983aebf9" />


---

##  Business Recommendations
- Improve inbound delay recovery processes  
- Monitor and prioritize high-risk flights  
- Optimize airport ground operations  
- Adjust scheduling during peak disruption periods  

---

##  Business Impact
- Improved on-time performance (D15)  
- Reduced delay propagation  
- Better operational efficiency  
- Enhanced decision-making capability  

---

##  Assumptions & Limitations
- Dataset is synthetic and simplified  
- Real-world constraints (crew, gates) not included  
- Weather impact partially modeled  
- Results are directional (prototype-level insights)  

---

## 📦 Project Structure
