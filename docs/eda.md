# 🔍 Exploratory Data Analysis

## 🛠 Data Cleaning
We standardized:
- **Bus company names** (e.g., `"RELIANT TRANS, INC."` → `"RELIANT TRANSPORTATION, INC."`)
- **Route numbers** (removed invalid entries, unified format)
- **Delay times** (converted hours/minutes/ranges to numeric `Delay_Minutes`)
- **Student counts** (capped at 72 max capacity)
- Removed non-NYC records.

---

## 📊 Insights

**Top Companies by Incident Count**  
![Top Companies](Top_Companies_by_Incident.png)  
Some companies like Pride and Pioneer have much higher incident counts — possibly due to more routes or maintenance issues.

**Distribution of Delay Minutes**  
![Delay Minutes](Delay_Minute_Distribution.png)  
Most delays last **16–30 minutes**, with many long delays (61–90 minutes).

**Key Findings:**
- **Queens** has the highest average delay (49.6 min).
- **Heavy traffic** is the most common reason.
- Incidents peak **5–7 AM** and **1–3 PM**.
