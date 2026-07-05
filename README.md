# HR-Employee-Data-Analysis
This project involved cleaning, transforming, and analyzing a Human Resources (HR) dataset using Microsoft Excel. The objective was to improve data quality, build interactive pivot table analyses, and generate actionable business insights to support workforce planning and decision making.

## Data Cleaning Process

Before conducting the analysis, the dataset was thoroughly cleaned to ensure accuracy and consistency.

The following data cleaning techniques were applied:

* Removed duplicate records to eliminate redundancy.
* Corrected data types by ensuring all Employee IDs were stored in a numeric format (**Home → Number Format**).
* Removed extra spaces and non-printable characters using the **TRIM()** and **CLEAN()** functions, then converted formulas to values.
* Handled missing values by using **Find & Replace (Ctrl + H)** to replace blank entries in the Salary and Performance Score columns with their respective average values.
* Standardized Employment Status values by correcting inconsistencies (e.g., **"Actv"** to **"Active"**) and applied the **PROPER()** function to maintain consistent text formatting.
* Used **XLOOKUP()** to retrieve Department Names and other related fields from the lookup table into the main dataset.
* Standardized the Hire Date column by removing unnecessary time values and converting all entries into a consistent date format using **Data → Text to Columns**, ensuring Excel recognized each value as a valid date.

These cleaning steps improved the reliability of the dataset and prepared it for accurate analysis.

---

# Data Analysis

The cleaned HR dataset was analyzed using **Excel Pivot Tables** to evaluate employee distribution, compensation, performance, attrition, and bonus allocation across departments. The analysis focused on four key Human Resource metrics that provide valuable insights into workforce management and organizational performance.

---

# Data Insights from Pivot Tables

## 1. Salary and Headcount by Department

### Key Findings

* Finance recorded the highest average salary at **₦87,173.59**.
* Information Technology (IT) had the largest workforce with **36 employees**.
* Finance had the smallest department size with **17 employees**.
* The organization has a total workforce of **150 employees** with an overall average salary of **₦83,603.94**.
* Although IT has the highest employee count, it records one of the lowest average salaries (**₦80,512.83**), while Operations has the lowest average salary (**₦80,049.93**).

### Interpretation

The salary distribution suggests potential pay disparities across departments. High staffing levels in IT combined with comparatively lower salaries may impact employee satisfaction and retention.

---

## 2. Employee Attrition by Department

### Key Findings

* Operations recorded the highest employee attrition:

  * **20.70%** Left
  * **17.24%** Resigned
  * Only **62.10%** remain Active.
* Marketing and Finance recorded **0% resignation**, making them the most stable departments.
* Overall workforce status:

  * **77.33% Active**
  * **16.00% Left**
  * **6.67% Resigned**

### Interpretation

Operations experiences significantly higher employee turnover than other departments, indicating possible issues relating to workload, leadership, employee engagement, or workplace satisfaction.

---

## 3. Performance Score by Employment Status

### Key Findings

* Employees who **Resigned** recorded the highest average performance score (**76.40**).
* Active employees recorded an average score of **67.74**.
* Overall company average performance score is **68.07**.

### Interpretation

One of the most notable findings is that some of the organization's highest-performing employees are leaving the company. This may indicate inadequate career progression opportunities, insufficient recognition, or compensation concerns.

---

## 4. Bonus Distribution by Performance Band

### Key Findings

* Employees in the **Achieving** performance band received the highest total bonus payout (**₦165,216.95**).
* **Exceeding** performers received the second-highest payout (**₦144,689.44**).
* Employees in the **Needs Improvement** category received no bonus.
* Total bonuses distributed amounted to **₦486,911.19**.
* Surprisingly, **Outstanding** performers received lower total bonuses (**₦92,411.52**) than employees in the Achieving category.

### Interpretation

The bonus distribution may reflect either a smaller number of Outstanding performers or a reward structure that disproportionately favors employees within the Achieving category.

---

# Key Business Recommendations

Based on the analysis, the following recommendations are proposed:

1. Investigate the Operations department to identify the root causes of its high attrition rate and implement targeted employee retention strategies.

2. Develop retention programs for high-performing employees by strengthening career development opportunities, recognition initiatives, and competitive compensation.

3. Review salary structures across departments, particularly within IT, to ensure compensation remains fair and competitive.

4. Reassess the organization's bonus allocation framework to ensure exceptional performance is adequately rewarded and aligned with business objectives.

5. Continue monitoring workforce metrics regularly using dashboards and pivot tables to support evidence-based HR decision-making.

---

# Project Limitations

* The dataset represents a single reporting period and does not capture historical trends.
* Attrition reasons and employee satisfaction data were unavailable, limiting root-cause analysis.
* External factors such as labor market conditions, economic changes, and industry salary benchmarks were not included in this analysis.

---

# Conclusion

This project demonstrates how Excel's data cleaning tools, Pivot Tables, and analytical techniques can transform raw HR data into meaningful business intelligence. The findings reveal opportunities to improve employee retention, optimize compensation strategies, strengthen workforce planning, and support more informed human resource decision-making.
