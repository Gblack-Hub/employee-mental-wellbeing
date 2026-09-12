# Employee Mental Well-being & Work Arrangement Analysis

## Project Overview
The modern work environment has rapidly evolved, with remote and hybrid models becoming standard. This analysis investigates how work arrangements influence employee mental well-being, stress levels, and social isolation. 

This project leverages Power BI to conduct Exploratory Data Analysis (EDA) on a dataset of 5,000 global employees. The goal is to provide data-driven insights into the key factors driving mental health challenges and offer strategic recommendations for HR professionals to improve workplace policies.

## Dataset
* **Population:** 5,000 employees globally.
* **Key Variables:** Work Location (Remote, Hybrid, Onsite), Mental Health Condition (Burnout, Anxiety, Depression, None), Stress Level, Social Isolation Rating (1-5), Work-Life Balance Rating (1-5), and Demographics.

## Analysis Process
1. **Data Cleaning & Preparation:** Confirmed that there were no missing values, checked for standardized categorical variables (e.g., Work Location, Reported Conditions) to ensure accurate aggregation.
2. **Metric Definition (DAX):** Created KPIs to establish a baseline: *Mental Health Condition Rate*, *High Stress Rate*, *Average Social Isolation Score*, and *Remote Work Satisfaction Rate*.
3. **Exploratory Data Analysis (EDA):** Analyzed the correlation between independent variables (Work Location, Isolation, Work-Life Balance) and the dependent variable (Mental Health Condition Rate).
4. **Dashboard Architecture:** Designed a single-page dashboard utilizing a Z-pattern reading flow and applied data visualization best practices.

## Key Findings
The data revealed highly counterintuitive insights regarding the modern workplace:

* **High Universal Baseline:** A staggering **76.1%** of the workforce reports a mental health condition, with roughly even distribution across Burnout, Anxiety, and Depression (approx. 25% each). Furthermore, **33.7%** of employees report High Stress.
* **Work Location is a Non-Factor:** The mental health condition rate remains nearly identical regardless of where employees work: Onsite (77.0%), Hybrid (75.7%), and Remote (75.5%). 
* **Stress is more Systemic than Locational:** The proportion of employees experiencing "High Stress" hovers tightly between 32% and 34% across all three work locations. 
* **Isolation Does Not Solely Dictate Well-being:** While social isolation peaks at a moderate 3.0/5 average, variations in social isolation ratings (1 through 5) result in a negligible shift (less than 3%) in overall mental health condition rates. 

## Strategic Recommendations
Based on the lack of statistical variance across work arrangements, HR leadership must pivot their approach. The data clearly indicates that enforcing Return-to-Office mandates or pushing fully Remote work will **not** solve the mental health crisis. 

* **Shift Focus from Location to Workload:** Since stress and mental health conditions are uniform across remote and onsite employees, organizations must investigate systemic issues such as overall workload, meeting density, and managerial expectations rather than debating physical work locations.
* **Deploy Universal Mental Health Resources:** Because burnout, anxiety, and depression are evenly distributed across the entire 5,000-employee population, HR should invest in universally accessible well-being programs (e.g., telehealth counseling, flexible mental health days) rather than location-specific interventions.
* **Investigate Role-Specific Drivers:** With the high stress baseline established at 33.7%, future data collection should focus on specific job roles, departments, and tenure to identify micro-cultures where burnout is originating.

## Repository Contents
* `Mental_Health_Dashboard.pbix`: The complete Power BI project file containing the data model, DAX measures, and visualizations.
* `README.md`: Project documentation and analysis summary.

## Author
[Olawale Oladiran](https://www.linkedin.com/in/olawale-oladiran/)
