# Employees-Presence-Analysis(Power BI Dashboard)

This Power BI dashboard analyzes employee attendance data for the year 2022, offering critical insights into presence trends, work-from-home (WFH) patterns, and sick leave (SL) behavior across the organization. 

It was developed to assist HR teams and decision-makers in understanding weekly attendance behavior, optimizing space planning, and identifying absenteeism trends to improve workplace efficiency and employee well-being.


##  1. Problem

Modern organizations, especially those transitioning to hybrid work models, face several challenges:

- Lack of visibility into employee attendance trends, especially **Work From Home (WFH)** and **Sick Leave (SL)** patterns.
- Difficulty identifying which days of the week have **low office presence**, affecting collaboration, space utilization, and productivity.
- **Inefficient infrastructure usage** due to poor space planning in the absence of attendance data.
- Inability to proactively respond to patterns like **spikes in SL**, which may indicate health risks (e.g., COVID outbreaks).

> These insights are crucial to optimize workspace costs, ensure employee well-being, and make data-driven HR decisions.

---

##  2. Goal of the Dashboard

The dashboard aims to deliver an interactive, data-driven solution to track and understand employee attendance trends over time.

###  Key Objectives

- Visualize **Presence %, WFH %, and SL %** across multiple months.
- Identify **day-wise patterns** (e.g., higher WFH on Fridays).
- Spot **outliers** in sick leave behavior for preventive health measures.
- Support **hybrid work planning**, space optimization, and employee well-being initiatives.

---

##  3. Key Visuals

### 1. **Visual 1 : Presence % by Date** *(Area Chart)*
- **Purpose**: Track daily employee presence rate across April to June 2022  
- **Key Insights**: Shows stable attendance with occasional dips  
- **Business Value**: Helps determine high-occupancy days, useful for planning meetings or events  
- **Notable Finding**: Average Presence % is **91.83%**, peaking above **97%** on some days
- ![Visual1](https://github.com/Safwannn89/Employees-Presence-Analysis/blob/main/Visual_1%20Presence%20%25%20by%20Date.png)

### 2. **Visual 2 : WFH % by Date** *(Area Chart)*
- **Purpose**: Analyze daily Work From Home usage patterns  
- **Key Insights**: Friday shows consistently high WFH usage  
- **Business Value**: Supports hybrid work planning and remote policy decisions  
- **Notable Finding**: Highest WFH observed on **06 May 2022** at **23.44%**, average WFH on **Fridays** is **13.01%**
- ![Visual2](https://github.com/Safwannn89/Employees-Presence-Analysis/blob/main/Visual_2%20WFH%20%25%20by%20Date.png)

### 3. **Visual 3 : Sick Leave % by Date** *(Area Chart)*
- **Purpose**: Monitor fluctuations in Sick Leave usage  
- **Key Insights**: Sudden spikes may indicate seasonal illness or health issues  
- **Business Value**: Allows early health-related interventions and policy tweaks  
- **Notable Finding**: Sick Leave % peaked at **5.42%** on **30 May 2022**, with Mondays having the highest average SL at **1.62%**
- ![Visual3](https://github.com/Safwannn89/Employees-Presence-Analysis/blob/main/Visual_3%20SL%20%25%20by%20Date.png)

---

##  4. Business Impact

###  Strategic Insights
- Identify **optimal days** (like Monday or Wednesday) for team meetings and collaboration.
- Optimize **hybrid scheduling** by aligning WFH trends with office needs.
- Analyze **SL patterns** to identify potential health or stress-related issues.
- Take **preventive actions** (e.g., medical camps, sanitization) based on observed spikes in SL.

###  Operational Benefits
- **Space Planning**: Reallocate office space and save on infrastructure costs.
- **Policy Design**: Refine HR and hybrid work policies based on real data.
- **Cost Optimization**: Minimize utility expenses and maximize workspace efficiency.

---

## 🛠 Tools Used

- **Power BI**: Interactive dashboard and data visualization
- **Microsoft Excel**: Source data (employee attendance sheet)
- **DAX**: Custom measures for KPIs and trends

---

##  Files Included

- `Attendance Sheet 2022-2023_Masked.xlsx` – Raw attendance data (anonymized)
- `Employee_Attendance_Insights.pbix` – Power BI dashboard file

---

##  Summary Table

| Metric             | Value      |
|--------------------|------------|
| Presence %         | 91.83%     |
| Work From Home %   | 10.00%     |
| Sick Leave %       | 1.10%      |
| Highest Presence Day| Monday     |
| Highest WFH Day     | Friday     |
| Highest SL Day     |  Monday     |




