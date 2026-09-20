# Renovation-Project-Performance-Analysis-Python
## Overview
This project analyses renovation project data to identify patterns in project duration, delays, costs, revenue and profitability. The analysis was designed from the perspective of a small renovation company looking to improve project planning, cost control and operational performance.

---

## Business Objective
The objective of this project is to analyse renovation project performance and identify opportunities to:
- Improve project scheduling
- Reduce project delays
- Monitor cost overruns
- Understand profitability by renovation type
- Identify operational areas requiring investigation

---

## Business Questions
The analysis aims to answer the following questions:

1. How often renovation projects finish later than planned?
2. Which renovation types experience the highest delays?
3. Which crews have the highest late-project rates?
4. How often do projects exceed their budgets?
5. Which renovation types have the highest cost variance?
6. Which renovation types are the most profitable?
7. Are project delays associated with higher cost overruns?
8. Which individual projects require further investigation?

---

## Tools & Technologies
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook
- Excel/CSV

---

## Dataset
The dataset contains 60 renovation projects and 12 variables covering:
- Project identification
- Renovation type
- Planned and actual duration
- Budgeted and actual costs
- Revenue
- Crew
- Subcontractor
- Project month
- Quarter
**This dataset was created for analytical and portfolio purposes.**

---

## Methodology
The analysis followed these stages:
1. Loaded the renovation dataset using Pandas
2. Inspected the structure and data types
3. Checked for missing values
4. Examined descriptive statistics
5. Created calculated columns for project performance
6. Analysed crew and subcontractor performance
7. Compared performance across renovation types
8. Analysed crew and subcontractor performance
9. Calculated cost variance
10. Analysed project profitability
11. Investigated outliers and high-risk projects
12. Created visualisations to communicate findings
13. Developed business recommendations based on the analysis

--- 

## Key Performance Indicators
| KPI | Result |
|---|---:|
| Total Projects | 60 |
| Late Project Rate | 31.7% |
| Projects Completed On Time | 68.3% |
| Over-Budget Projects | 20 |
| Over-Budget Rate | 33.3% |
| Average Project Delay | 1.3 days |
| Maximum Project Delay | 7 days |

---

## Key Findings:
### Project Scheduling
31.7% of projects finished later than planned, with an average delay of 1.3 days.
Roofing projects experienced the highest average delay at 2.0 days and had a 50% late-project rate.

### Crew Performance
Crew C had a substantially higher late-project rate than Crew A and B.
Crew C completed 17 of 31 projects late, resulting in a late-project rate of approximately 55%.
Further investigation is required before determining the reasons for this difference, as project mix and complexity may influence the results.

### Cost Performance
20 of the 60 projects exceeded their budgets, representing 33.3% of all projects.
Roofing projects had the highest average cost variance at approximately 23 311.

### Profitability
Roofing generated the highest average profit at approximately 49 033 per projects, followed by Kitchen projects at approximately 39 888.
Flooring had a slightly negative average profit, largely influenced by an extreme loss-making project.

### Outlier Investigation
Project J050 was identified as a significant cost and profitability outlier.
The project exceeded its budget by approximately 211 046 and generated a loss of approximately 196 974.
This project should be investigated further rather than assuming it represents normal Flooring project performance.

### Relationship Between Delays and Cost
The correlation between project delays and cost variance was approximately 0.50, indicating a moderate positive relationship.
This suggests that projects with greater delays tended to also experience higher cost variances.
However, correlation does not establish that delays caused the additional costs.

---

## Recommendations
Based on the analysis, the following areas should be investigated:

1. **Review Roofing projects scheduling**

Investigate whether duration estimates, resource allocation or project complexity are contributing to higher delays.

3. **Investigate Crew C performance**

Review Crew C's project mix, workload and resource requirements to understand why its late-project rate is substantially higher.

4. **Strengthen cost monitoring**
 
Introduce earlier monitoring of actual costs against budget to identify potential overruns before project completion.

6. **Investigate Project J050**

Review the project for possible scope changes, unexpected requirements, unusual material costs or potential data-quality issues.

8. **Analyse profitable project characteristics**

Further investigate Roofing and Kitchen projects to understand the operational factors associated with stronger profitability.

---

## Conclusion
The analysis identified opportunities to improve renovation project scheduling, cost control and profitability.

Roofing projects demonstrated strong profitability but also showed the highest average delays and cost variance, making them an important area for further investigation.

Crew C also showed a substantially higher late-project rate than the other crews.

The analysis further demonstrated the importance of investigating outliers, particularly Project J050, before drawing conclusions about overall project-type performance.

Overall, the findings suggest that improved scheduling, early cost monitoring and targeted investigation of high-risk projects could help improve operational efficiency while protecting profitability.

