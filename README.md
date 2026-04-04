# Kevaro Athletics - Roster Systemization & Fiscal Analysis
## 🎯 Objective
To analyze the gender-wise representation and salary distribution across different sports and countries for Kevaro Athletics’ global selection pool. The goal is to identify patterns in participation diversity, pay disparity, and high-salary sports to support equitable athlete management and strategic talent investments.
### **Project Purpose:**
   * To design a centralized roster intelligence dashboard that provides visibility into athlete distribution, demographic segmentation, and financial investment across sports and countries.
   * Evaluate the sport-wise and country-wise candidate participation in the selection pool.
   * Compare total and average salaries between male and female athletes across sports.
   * Identify top-performing (high-salaried) sports and countries contributing maximum value.
   * Support Kevaro Athletics in designing data-driven gender equity and sponsorship strategies.
### **Key KPIs:**
   * Total Active Athletes 
   * Average Age 
   * Age Range 
   * Total Investment
   * Highest Pay 
   * Country-wise & Sport-wise Salary Distribution
### **Deliverables:**
   * Interactive Power BI Dashboard (Roster + Fiscal View)
   * Athlete Segmentation Model (Age Division Logic)
   * Salary Distribution & Financial Gap Analysis
   * Country & Gender Participation Analysis
   * Executive Summary Insights
---

## 📘 Project Overview 
### **Context Highlights:**
   * Kevaro Athletics, a global sports organization, manages a diverse roster of 50 athletes representing 11 countries across multiple sporting disciplines.
   * This project delivers structured visibility into roster composition and financial investment, enabling data-driven decision-making across performance management and resource allocation.
   * The analysis focuses on:
     * Athlete distribution across countries and sports
     * Age segmentation for lifecycle and performance tracking
     * Gender representation & compensation equity
     * Investment patterns across regions and disciplines
---
 
## 🗂️ Data Overview & Schema     
### **Data Source:**  
   * Source: Fictionalized Sports Company Dataset
   * Data Type: Structured Tabular Athlete & Financial Data
   * Time Period: Current Active Roster Snapshot
### **Data Structure & Metrics:** 
   * Key Index Types:
     * Country
     * Gender
     * Age
     * Blood Type
     * Sport Location (Indoor/Outdoor)
     * Salary
   * Total Rows: 50 Athletes
     * Countries: 11
     * Sports Listed: 32
   * **Calculated Metrics:**     
     * Age Division Classification (Young, Veteran, Master, Legend, Experienced)
     * Total Investment
     * Financial Gap (Max - Min Salary) & Mid Pay (Median Salary)
     * Country-Level Salary Contribution
     * Sport-Level Investment Distribution
---
 
## 💻 Tech Stack    
### **Tools:**
   * **Excel**
     * Initial Data Cleaning & Structuring
     * Text Standardization (TRIM / LOWER equivalents)
     * Salary Format Conversion & Validation
     * Data Storage & Preprocessing
   * **Power Query**
     * Data Transformation & Shaping
     * Column Standardization
     * Age-Based Classification Modeling
     * Data Preparation for BI Integration
   * **Power BI**
     * Data Modeling & Relationship Building
     * DAX (Calculated Columns & Measures)
     * Aggregation by Country, Sport & Gender
     * Slicers & Dynamic Filtering
     * Age Segmentation Logic using SWITCH(TRUE())
   * **PowerPoint**
     * Presentation Design, Dashboard Snapshots & Business Insight Documentation
---
        
## 📈 Methodology & Analysis  
### **Prepararation, Process & Analytical Approach:**   
   * **Data Preparation & Cleaning:**
     * Standardized text fields (Country, Sport Location, Gender)
     * Handled missing values
     * Converted salary from K format to numeric
     * Verified age range (27–71)
   * **Data Modeling & Integration:**
     * Built a structured data model
     * Created Age Division logic
     * Established relationships across Country, Gender & Sport
   * **Feature Engineering:**
     * Developed Age Segmentation column
     * Calculated Financial Gap & Gender Ratio
     * Derived Average Salary by Division & Sport
   * **Visualization Design:**
     * Designed interactive dashboard layout
     * Used Bar Charts, Donut Chart, Treemap & KPI Cards
     * Built Fiscal Overview for salary analysis
   * **Validation & Formatting:**
     * Verified 50 athletes & $3.36M total investment
     * Cross-validated salary totals
     * Applied consistent executive theme
---
 
## ❓ Problem Statement     
In a globally competitive sports environment, data-driven roster and financial transparency are essential for sustainable performance and equitable growth. However, without a structured analytical framework, decision-makers lack the clarity needed to optimize talent allocation, compensation fairness, and investment strategy.

### **Key Questions:**
   * What is the overall gender representation in Kevaro’s global selection pool?
   * How are athletes distributed across countries and sports?
   * Which sports generate the highest total and average salaries?
   * Is there evidence of a gender or age-based pay gap?
   * Which countries contribute the highest athlete count and salary volume?
   * What is the investment concentration across sports and regions?
   * Are there signs of over-investment in specific demographics?
   * What is the financial gap across age divisions?
---

## 💡 Key Insights      
### **Top Findings:** 
   * Total Investment: $3.36M
   * Balanced Gender Participation: 25 Male & 25 Female athletes selected globally
   * Gender Salary Split:
   * Male: $1.73M (51.15%)
   * Female: $1.63M (48.49%)
   * Highest Investment Sport: Beach Volleyball (~$0.29M)
   * Top Contributing Country: France (~$0.61M salary allocation)
   * High-Salary Sports: Cycling Road, Volleyball, Alpine Skiing & Triathlon
   * Age Structure: Strong mid-to-late career representation (Avg. Age: 49)
   * Maximum Individual Salary: $117.40K
   * Financial Gap: Noticeable variance across age divisions
### **Supporting Metrics:**
   * 32 Sports across 11 Countries
   * Countries with highest athlete count: France (9), Australia (8), USA (7)
   * Evidence of pay concentration in endurance & cycling-related sports
   * Master Division athletes show higher average earning tier
   * Some sports show gender-dominant salary trends
---
 
## 📍 Conclusion
### **Summary:** 
   * Kevaro Athletics demonstrates strong gender balance in participation, yet salary distribution varies across disciplines.
   * While some sports reflect female earnings leadership, others show a male-dominant pay concentration, indicating opportunities for targeted parity initiatives and performance-linked compensation review.
   * The analysis highlights:
     * Balanced gender investment overall
     * Regional concentration in European markets
     * Financial dominance of endurance & cycling sports
     * Clear age-based salary progression trends
   * The integrated dashboard combines roster intelligence with financial analytics, enabling leadership to make data-driven allocation and equity-focused decisions.
---
 
## 🖥️ Dashboard Overview
![image alt](https://github.com/Cnik1710/Kevaro-Athletics-Roster-Systemization-Fiscal-Analysis/blob/7e4ff7ab52e62e85f1c8ee37041e802d6840ff11/04.%20Kevaro%20Athletics%20-%20Roster%20Systemization%20%26%20Fiscal%20Analysis%20(1)%20Dashboard.png)

![image alt](https://github.com/Cnik1710/Kevaro-Athletics-Roster-Systemization-Fiscal-Analysis/blob/dbdf113f05cbb47ba1d7ed20ab8bf70e96071ea1/05.%20Kevaro%20Athletics%20-%20Roster%20Systemization%20%26%20Fiscal%20Analysis%20(2)%20Dashboard.png)

---

## ✅ Business Impact & Use Cases   
  * Supports Gender Equity Reporting & Pay Gap Monitoring aligned with global sports standards
  * Enables Strategic Salary Budgeting & Sponsorship Alignment by sport and gender
  * Empowers HR to identify underrepresented sports & talent gaps
  * Forms the foundation for a future Diversity & Inclusion Dashboard
  * Strengthens Strategic Budget Allocation & Investment Planning
  * Assists in Talent Lifecycle & Age-Based Performance Planning
  * Supports International Expansion Strategy through country-level insights
  * Identifies High-Investment & High-Return Sports
  * Enhances Executive Decision-Making with Real-Time Interactive Insights
---
 
## 🙏 Acknowledgements & Contact 
### Project Analyst: Anik Chakraborty	
   📧 Email: anikc1710@gmail.com  
### Special Thanks To: 
   * Coding Ninjas – for project framework and guidance  
   
