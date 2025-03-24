# Car Theft Analysis Dashboard - Tableau

### An interactive Tableau Dashboard analyzing car theft trends, recovery rates, and high-risk areas.

## Overview

Car theft continues to be a growing concern in urban areas. This interactive **Tableau dashboard** analyzes over **4,000 reported cases of ottawa (2019–2023)** to uncover:

- Theft trends over time
- High-risk neighborhoods
- Most targeted car brands, models, and colors
- Recovery patterns and peak theft hours


![Thefts Dashboard](https://github.com/user-attachments/assets/10f47952-aa07-4cd6-ab9c-b80a7103ab10)

<p align="center"> Checkout the Dashboard  <a href="https://public.tableau.com/app/profile/shubham.naik5258/viz/CarTheftAnalysis/Dashboard ">HERE</a>
</p>

This dashboard helps *law enforcement, policymakers, and car owners* make *informed decisions* to reduce vehicle theft.

---

##  Core Research Questions
1. How have car theft trends evolved over time?
2. Which neighborhoods experience the highest theft rates?
3. Which car makes, models, and colors are most frequently stolen?
4. What percentage of stolen vehicles are recovered?
5. Are there specific times of the day and week when thefts peak?

---

##  Dataset Details
**Total Reports:** *4,106 thefts*  
**Timeframe:** *2019 - 2023*  
**Data Source:** *Government police records / Auto theft database*

### **Dataset Attributes**
| **Variable**        | **Data Type**  |
|--------------------|---------------|
| OBJECTID           | Integer       |
| Vehicle Year       | Integer       |
| Vehicle Make       | String        |
| Vehicle Model      | String        |
| Vehicle Type       | String        |
| Vehicle Colour     | String        |
| Weekday            | String        |
| Recovered          | String        |
| Neighbourhood      | String        |
| Reported Date      | Date          |
| Year               | Integer       |
| Time of Day        | String        |
| Longitude          | Float         |
| Latitude           | Float         |

---

##  Key Metrics Overview
 **Total Thefts:** *4,106 cases reported*  
 **Recovery Rate:** *61.91%* recovered  
 **Most Stolen Car Brands:** *Toyota, Honda, Ford*  
 **High-Risk Neighborhoods:** *New Barrhaven, Orléans Avalon, Centretown*  
 **Peak Theft Time:** *Evening (5 PM - 9 PM)*  

---

##  Key Insights
###  **Car Theft Trends:**
- Theft rates *peaked in 2021 and 2022* before a slight decline in 2023.
  
![Theft Trend ](https://github.com/user-attachments/assets/7ded1eb2-3c63-44c4-bfa3-510994f24cbc)

### 📌 **High-Risk Locations:**
- **Top neighborhoods for theft:**
  - *New Barrhaven - 257 cases*
  - *Orléans Avalon - 238 cases*
  - *Centretown - 138 cases*
- *Emerging theft zones:* Riverside South, Overbrook.
  
![Theft Map](https://github.com/user-attachments/assets/60b84e6b-559c-485b-94a3-8ebd3b1d6094)

###  **Most Stolen Vehicles:**

- **Top 3 Car Brands:**
  
  1️. *Toyota* – *1,327 thefts*  
  2️. *Honda* – *474 thefts*  
  3️. *Ford* – *344 thefts*
   
- **Top 3 Stolen Models:**
  
  1️. *Toyota Highlander* – *665 thefts*  
  2️. *Toyota RAV4* – *282 thefts*  
  3️. *Honda CR-V* – *217 thefts*
  
![Screenshot 2025-02-18 185227](https://github.com/user-attachments/assets/db76cac8-bac6-404f-bef4-8d70806a9675)

###  **Theft Timing & Recovery:**
- **Peak Theft Hours:** *Evening (5 PM - 9 PM)* 
- **Recovery Rate:** *61.91% of stolen vehicles were recovered.*
- *Newer vehicles (post-2020) have lower recovery rates.*
  
![Theft Weekday Heatchart](https://github.com/user-attachments/assets/b66ec942-32bb-428c-800e-ffcd38199b78)
![Theft Recovery Linechart](https://github.com/user-attachments/assets/80ac4c49-243a-4a4e-bb86-0dae4a54676c)

---

##  Recommendations
###  **For Law Enforcement:**
- Increase *patrols in high-risk areas*  
- Improve *CCTV & surveillance in theft hotspots*   
- Focus *night patrols (5 PM - 9 PM)* for maximum impact 

###  **For Car Owners:**
- *Avoid parking in high-theft areas*   
- *Install GPS trackers & smart alarms*   
- *Use steering wheel locks & secure garages*  

###  **For Policymakers & Insurers:**
- Implement *public awareness programs*   
- Require *mandatory security features for high-risk vehicles*   
- Offer *insurance discounts for anti-theft measures*   

---

