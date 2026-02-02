# 🎓 University Performance Dashboard (2018–2025) — Power BI

### 📌 Executive Summary
This Power BI dashboard provides an institution-level view of **student demand, student outcomes, organisational structure, and financial sustainability** across the period **2018–2025**. It is designed to support **strategy and planning**, enabling stakeholders to monitor performance, identify emerging risks (e.g., capacity pressure), and drill into detail without cluttering the main pages.

---

### 🎯 Project Objectives
- Translate complex institutional data into **clear, decision-ready insights**
- Track performance across **enrolments, student outcomes, staffing capacity, and finance**
- Provide **governance-style reporting** (Targets vs Actuals, trends, and drill-through detail)
- Create a user-friendly experience using **tooltips, bookmarks, and drill-through pages**

---

### 🗂️ Dataset Overview
- **Source:** Structured CSV-based dataset (2018–2025) containing academic, organisational, and financial indicators  
- **Core entities:** Year, Campus, College, School, Department  

**Measures included (examples):**
- Enrolments (new and continuing)
- Student outcomes (graduation, completion, retention)
- Capacity indicators (student–staff ratio)
- Financial indicators (revenue, cost, operating profit/surplus, margin, research income)

---

### 🧱 Data Model & Preparation
**Data cleaned and shaped in Power Query:**
- Standardised data types and year fields
- Created analysis-ready tables (e.g., revenue and expense breakdowns)
- Ensured consistent naming and category labels

**Data modelling approach:**
- Structured tables suitable for reporting with clear relationships
- Measures written in DAX for KPI calculations and time-based comparisons

---

### 📊 Key Metrics & Definitions
- **Operating Surplus ($M)** = Total Operating Revenue − Total Operating Expenses  
- **Operating Margin (%)** = (Operating Surplus ÷ Total Operating Revenue) × 100  
- **Revenue per Student ($)** = Total Revenue ÷ Total Enrolment  
- **Student–Staff Ratio** = Total Students ÷ Total Staff  
- **Retention Rate** = % of students progressing from 1st → 2nd year  
- **Completion Rate** = % of students completing within the defined timeframe  

---

### 🧭 Dashboard Pages

### 1) Executive Overview
A high-level snapshot combining **enrolment trends, revenue and expense composition, and capacity indicators**, supported by KPI cards and executive storytelling via bookmarks.

**What this page answers:**
- Is demand stable or changing?
- Is financial performance on track against targets?
- Are there capacity pressures emerging?

---

### 2) Student Outcomes & Capacity Indicators
Focuses on **graduation trends**, **completion vs retention performance by college**, and **student–staff ratio trends** to surface student success signals and sustainability risk.

**What this page answers:**
- Are outcomes improving or declining?
- Which colleges show stronger retention vs completion?
- Is staffing keeping pace with student numbers?

---

### 3) Organisational Hierarchy View
Interactive hierarchy exploration: **Campus → College → School → Department**, helping users understand where student volume is concentrated and where programmes are more specialised.

**What this page answers:**
- Where is institutional scale concentrated?
- Which areas are high-volume vs specialist?
- What does distribution imply for resource planning?

---

### 4) Student Enrolment & Demographic Overview
Combines enrolment trends (domestic/international) with demographic composition (age, ethnicity, gender) to support inclusion and planning discussions.

**What this page answers:**
- How is the student mix evolving?
- Is international demand recovering/growing?
- How diverse is the student population?

---

### 5) Financial Performance Overview
A governance-style view of **Targets vs Actuals**, revenue composition, expense composition, and operational performance across years.

**What this page answers:**
- Are we tracking to targets?
- What is driving revenue and cost structure?
- Is operating surplus/margin sustainable over time?

---

### 6) Drill-through Detail Pages
Used to reduce clutter while preserving transparency. Drill-through is configured to filter by **Year** while still showing category breakdowns.

**What this page answers:**
- What is the detailed breakdown behind a high-level number?
- How do revenue/expense categories change across years?

---

### 🧠 Key Insights & Takeaways

### Executive Overview
- Enrolment demand remains resilient across the reporting period, with recovery visible after disruption years.
- Revenue remains strong and diversified, with tuition and stable funding as key drivers.
- Capacity pressures emerge as student–staff ratio trends upward, suggesting workforce planning is critical.

### Student Outcomes & Capacity
- Retention remains strong across colleges, supporting long-term completion stability.
- Completion outcomes vary across colleges, indicating targeted interventions may be more effective than system-wide changes.
- Increasing student–staff ratio signals a sustainability risk to student experience if growth outpaces resourcing.

### Organisational Hierarchy
- Student distribution is concentrated across major campuses and high-volume colleges, supported by specialist schools and departments.
- The hierarchy view supports resource allocation discussions by separating scale-based areas from niche programme clusters.

### Enrolment & Demographics
- Domestic enrolments remain the foundation, while international enrolments show signs of recovery/growth.
- The student population reflects multi-age participation, supporting lifelong learning and flexible pathways.
- Diversity insights support equity monitoring and Te Tiriti-aligned institutional planning discussions.

### Financial Performance
- Operating results remain positive across most periods, showing sustainable performance despite cost pressures.
- Expense structure is mission-aligned, with significant investment in academic delivery and research support.
- Margin trends highlight the importance of balancing growth with cost discipline and capacity planning.

---

### 🔍 Features Implemented
- **Custom Tooltips:** Clear breakdowns without cluttering the main visuals  
- **Bookmarks:** Toggle “Insights” text boxes on/off for executive storytelling  
- **Drill-through Pages:** Detailed views filtered by Year (not by category) for clean exploration  
- **Consistent Theme:** Uniform colour palette and formatting for a professional institutional reporting look  

---

### 🛠️ Tools & Technologies
- **Power BI** (DAX, Power Query, drill-through, tooltips, bookmarks)
- **Excel / CSV** (data source)

**Optional workflow support:**
- Data profiling logic in Power Query
- Validation and reconciliation mindset used for trusted reporting

---

### ▶️ How to Use the Dashboard
1. Use slicers (Year / Campus / College etc.) to refine the view.
2. Hover over charts to view tooltip breakdowns.
3. Use drill-through from key visuals to view detailed category tables.
4. Toggle executive insights using bookmark buttons (where enabled).

---

### ⚠️ Assumptions & Limitations
- The dashboard is based on the provided dataset structure and available fields.
- Some institutional definitions (e.g., staffing composition or completion timeframe) depend on the dataset assumptions.
- Figures are designed for analysis and storytelling; official reporting should confirm source-of-truth definitions.

---

### 🚀 Future Improvements
- Add benchmark/reference lines for key metrics (e.g., student–staff ratio target)
- Expand forecasting for enrolment and revenue projections
- Add automated refresh pipeline using a database or data lake source
- Create a glossary page for KPI definitions and governance reporting standards

---

### 🖼️ Screenshots
*(Add images here once uploaded to GitHub — recommended for portfolio impact)*
- Executive Overview
  <img width="1493" height="808" alt="image" src="https://github.com/user-attachments/assets/bfc35bfc-c34b-4ce6-8304-15822e472689" />
- Student Outcomes & Capacity
   <img width="1476" height="834" alt="image" src="https://github.com/user-attachments/assets/62c9a84b-e4d8-44d1-8810-68ff29ada21f" />
- Organisational Hierarchy
  <img width="1436" height="805" alt="image" src="https://github.com/user-attachments/assets/05f51cf2-955d-432d-9473-c71916341ac3" />
- Enrolment & Demographics
<img width="1470" height="802" alt="image" src="https://github.com/user-attachments/assets/710bfd63-89ff-4a29-b195-1e20dd32b9c1" />
- Financial Performance
<img width="1471" height="824" alt="image" src="https://github.com/user-attachments/assets/04baf28a-dbf1-4f87-b13d-1a24236ed26b" />
- Drill-through Detail
<img width="643" height="673" alt="image" src="https://github.com/user-attachments/assets/704c9532-ae61-4093-b95f-04a481a84225" />

---

### 👤 Author
**Ambili Arangath Narayanan**  
Portfolio: https://ambilian.github.io  
PowerBI Project link : https://app.powerbi.com/groups/me/reports/c60cabb2-3d1e-4cc7-9118-0240c6a1502a/6622a618775e4e45ca4c?experience=power-bi&bookmarkGuid=84d13087435ecd9796fd
LinkedIn: https://www.linkedin.com/in/ambilian/
