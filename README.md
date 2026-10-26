# 👥 HR EMPLOYEE ATTRITION ANALYTICS

> Why are 237 employees leaving? Analysis of 1,470 employees with 16.12% attrition rate to identify at-risk departments, roles, salary bands and satisfaction drivers.

### 🔍 Dashboard Preview
<img width="813" height="365" alt="Employee Attrition Dashboard" src="https://github.com/user-attachments/assets/6f13acbb-9faf-4e4d-862f-8c272d35016c" />

*KPIs + 6 visuals: Department, Job Role, Salary Band, Age, Overtime, Job Satisfaction*

---

### 📌 Business Problem
HR reported 16.12% attrition (237 of 1470) - above industry healthy benchmark of 10-12%. CHRO needs to know:
1. Who is leaving? (Dept, Role, Age, Salary)
2. What are the key drivers? (Overtime, Satisfaction, Income)
3. How to reduce attrition to save hiring costs?

**Cost of attrition:** If avg hiring cost = $5K, 237 exits = **~$1.18M annual cost**.

### 📂 Dataset
- **Source:** IBM HR Analytics Employee Attrition Dataset
- **Total Employees:** 1,470
- **Attrition:** 237 Yes (16.12%), 1,233 No (83.88%)
- **Avg Monthly Income:** $6,502.93
- **Avg Years at Company:** 11.3 yrs
- **Fields:** Department, Job Role, Monthly Income, Age, Overtime, Job Satisfaction, Attrition

### 🛠️ Tools & Techniques
- **BI Tool:** Advanced Excel
- **Analysis:** Attrition Rate Calculation, Cohort Analysis (Age, Salary Band), Driver Analysis (Overtime, Satisfaction), Pareto (Top Roles), Departmental Benchmarking
- **Visuals:** Stacked Bars, Clustered Bars, KPI Cards with conditional formatting

### 📈 Key Insights & Results

**Overall KPIs:**
- Total Employees: 1,470
- Attrition Rate: 16.12% (237 employees)
- Avg Monthly Income: $6,502.93
- Avg Tenure: 11.3 years

**1. Departmental Attrition Level - Sales is Highest Risk:**
| Department | Attrition % | Stay % | Verdict |
| :--- | :--- | :--- | :--- |
| Sales | **20.63%** | 79.37% | **Highest Risk** |
| Human Resources | 19.05% | 80.95% | High Risk |
| Research & Development | 13.84% | 86.16% | Lowest - Best retention |

> Sales team attrition is 50% higher than R&D - sales pressure / targets issue.

**2. Job Roles of Exited Employees - Lab Technicians Lead:**
- Laboratory Technician: **62 exits (26% of all attrition)**
- Sales Executive: 57 exits
- Research Scientist: 47 exits
- Sales Representative: 33 exits
- HR: 12, Manufacturing Director: 10, Healthcare Rep: 9, Manager: 5, Research Director: 2
- **Insight:** 3 roles (Lab Tech, Sales Exec, Research Scientist) = 166 exits = **70% of all attrition** - Pareto principle.

**3. Monthly Salary Band by Attrition - Low Salary = High Exit:**
- 1000-4008: **117 Yes** / 407 No = **22.3% attrition rate** - Highest
- 4009-7008: ~59 Yes / 439 No = ~11.8%
- 7009-10008: ~29 Yes / 131 No = ~18%
- 10009-13008: 15 Yes / 80 No
- 16009-19008: 7 Yes / 75 No
- 13009-18008 & 19009-22008: <5 exits - almost zero attrition
- **Insight:** Employees earning < $4K are 3x more likely to leave. Salary is a retention lever.

**4. Age Range by Attrition - Young Employees Leave Most:**
- 18-27: **28.10% attrition** - Highest, early career churn
- 28-37: 17.71%
- 38-47: **9.36%** - Lowest, most stable cohort
- 48-57: 11.76%
- 58-67: 17.24% - Pre-retirement / second career
- **Insight:** Focus retention on 18-27 group - onboarding & career path issue.

**5. Working Overtime by Attrition - SMOKING GUN:**
- **No Overtime:** 10.44% attrition
- **Yes Overtime:** **30.53% attrition**
- **Employees working overtime are 3x more likely to leave.**
- This is the strongest driver found.

**6. Job Satisfaction Rating of Exited Employees - Surprising:**
- Rating 3 (Medium): **73 exits (highest)** - Not lowest satisfaction!
- Rating 1 (Low): 66 exits
- Rating 4 (High): 52 exits - Even highly satisfied are leaving
- Rating 2: 46 exits
- **Insight:** Attrition is not just about low satisfaction - Rating 3 & 4 employees leaving suggests better external opportunities / salary issues not just misery.

### 💡 Strategic Recommendations for CHRO

**Immediate (0-30 days):**
1.  **Overtime Policy:** Cap overtime, introduce compensatory time-off - can reduce attrition by up to 20%
2.  **Sales Dept Audit:** 20.63% attrition - review targets, commission structure, manager quality
3.  **Salary Review for < $4K band:** 22.3% attrition in lowest salary band - market correction needed

**Mid-term (30-90 days):**
4.  **Retention Program for 18-27:** Mentorship + clear 2-year career path - 28% attrition is too high
5.  **Focus on 3 Critical Roles:** Lab Tech (62), Sales Exec (57), Research Scientist (47) - create role-specific retention (stay interviews, skill growth)
6.  **Stay Interviews for Rating 3 & 4:** They are satisfied but still leaving - likely salary/external pull

**Estimated Impact:** Reducing attrition from 16.12% to 12% saves 60 employees = **$300K annual hiring cost savings**.

