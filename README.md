# EMPLOYEES DATA ANALYSIS 

## Table of Contents
- [Introduction](#Introduction)
- [Problem Statement](#Problem-Statement)
- [Objectives](#Objectives)
- [The Data](#The-Data)
- [Data Cleaning and Preparation](#Data-Cleaning-and-Preparation)
- [Data Exploration](#Data-Exploration)
- [Insights](#Insights)
- [Recommendations](#Recommendation)
  
### Introduction
The exploration of the Employees Data Set offers a profound opportunity to examine the complex details of an organization's workforce dynamics. With a comprehensive attributes ranging from basic demographic information like age, ethnicity, and location to professional specifics such as job title, department, and salary, this dataset provides variety of insights waiting to be unraveled.

This analysis aims to transform simple numbers and labels, by discovering  trends and patterns within the data. We can uncover invaluable information regarding employee demographics, distribution across departments and business units, and also discern potential correlations between various factors such as tenure and performance.

Furthermore, this exploration isn't just about understanding the present state of affairs; it's about understanding actionable intelligence to drive future decision-making. By identifying areas of strength and improvement, organizations can strategically direct their resources to foster a more productive, and successful working environment.
 
In essence, this report serves as a guide to organizational leaders towards a deeper understanding of their workforce composition and dynamics, with the ultimate goal of facilitating informed strategies for growth and improvement through data-driven insights. 

### Problem Statement
Despite the vast amount of data available on employee demographics, performance, and tenure, organizations often struggle to leverage this information effectively to drive strategic decision-making. The lack of comprehensive analysis and actionable insights derived from employee data impedes efforts to optimize workforce dynamics, foster inclusivity, and enhance overall organizational performance.
Key challenges include:
- **Limited Understanding of Workforce Composition:** Organizations often lack a thorough understanding of the diverse demographics, skill sets, and distribution of their workforce across departments and business units. This hampers efforts to promote diversity, equity, and inclusion within the workplace.
- **Ineffective Utilization of Employee Data:** While organizations may collect extensive data on employee attributes such as age, ethnicity, job title, and salary, they often struggle to extract meaningful insights from this data. This results in missed opportunities to identify trends, correlations, and areas for improvement.
- **Suboptimal Workforce Management:** Without a clear understanding of employee demographics and performance metrics, organizations may struggle to allocate resources efficiently, resulting in suboptimal workforce management practices. This can lead to issues such as high turnover rates, low employee morale, and decreased productivity.
  
### Objectives
This project seeks to address these challenges by creating a user friendly Employees Dashboard, leveraging advanced data analytics and visualization tools.
Key objectives of this analysis include:
1. **Identifying High-Risk Groups:** By examining demographic variables such as age, ethnicity, and tenure, we aim to identify segments of the workforce that may be particularly susceptible to turnover. Understanding the unique challenges and motivations of these groups can inform targeted retention strategies.
2. **Analyzing Job Satisfaction and Engagement:** Employee engagement and job satisfaction play a crucial role in retention. By examining variables related to job title, department, and performance metrics, we seek to assess levels of employee satisfaction and identify areas where improvements may be needed to enhance job retention.
3. **Exploring Compensation and Benefits:** Compensation and benefits packages are key factors influencing employee retention. Through analysis of variables such as annual salary, bonus structures, and benefits offerings, we aim to assess the impact of compensation on turnover rates and identify opportunities for adjustment.

### The Data
The data set for this project was provided by Tektrybe Community. It contains 1000 entries, and 15 columns. Key columns include employee ID (EEID), full name, job title, department, business unit, gender, ethnicity, age, hire date, annual salary, bonus percentage, country, city, and exit date. All columns are fully populated except for the Exit Date which has 915 missing values. The employee ID (EEID) column contains 89 duplicate values.

![Screenshot (349)](https://github.com/DanielOladipupo/Employees-Data-Analysis-Project/assets/155446588/ce48342c-5f20-4d85-834d-282ad02a1485)

### Data Cleaning And Preparation
Once we downloaded and imported the data into Excel, we proceeded to clean and prepare it for analysis. Firstly, we created a new version of my data in case we needed to drop some columns or make other changes. In the newly created worksheet, the following steps were taken:
- **Duplicate Check:** We performed data validation to ensure all rows in the data set met the required criteria.
- **Missing Values:** The data cleaning identified 915 missing values in the exit column which represents the active number of employees and 85 resigned/retrenched due to some internal factors.
- **Data types:** All columns were in the general format which is fine for what we need to do.
- **Categorical variables:** We examined the categorical variables for errors in spellings and other unexpected values. Again, everything was fine.
- **Additional Column:** We added another column which is the age range, salary range and the number of active years.

### Data Exploration
With the data now clean and prepared, it was time for exploration and analysis. Now it is time to plot the pivot table to create a visual on various insights derived from the employees data set, the following insights was derived:
- The Total Number of Employee in Each Department was 1000
- Department with the Highest Bonus was Marketing
- We have Gender Distribution in Male as 482, while Female as 518
- The Exit Date Column shows 915 active employees
- The Annual Average Salary was $113,217
- Department with the Highest Number of Employees was the IT Department.

### Insights
1. **Distribution of Employees by Gender:** The total number of Female Employees in the Organization is 518 while the Total number of Male Employees in the Organization is 482, which means that they have more Female Employees than Male Employees in the Organization

![Screenshot (350)](https://github.com/DanielOladipupo/Employees-Data-Analysis-Project/assets/155446588/c67ba75d-f979-4d71-8801-639cf95e745f)

2. **Distribution of Employees by Ethnicity:** The visualization indicates that there are 403 employees of Asian ethnicity, 74 Black Ethnicity, 271 Caucasian Ethnicity, and 251 Latino Ethnicity. This illustrates that the majority of employees belong to the Asian ethnicity group, while Black Ethnicity group recorded the least Employees.

![Screenshot (351)](https://github.com/DanielOladipupo/Employees-Data-Analysis-Project/assets/155446588/db5d2153-2a7d-471e-bec5-2a7f70db0c11)

3. **Distribution of Employees by Salary Range:** The Employees Salary Range indicates 0-50(53), 51-100(488), 101-150(203), 151-200(178), 201-250(63), and above 250(16). 488 employees have the highest salary range, falling between 51 and 100, whereas only 16 employees fall into the lowest salary range, which is above 250.

![Screenshot (352)](https://github.com/DanielOladipupo/Employees-Data-Analysis-Project/assets/155446588/9c73646a-0552-44e8-b35b-d6a47796b2ba)

4. **Distribution Number of Employees in Each Department:** The IT Department emerged as the highest number of employees at 241, while the Accounting Department has the fewest, with only 96 employees. The Marketing and Finance Departments each have an equal number of employees, totaling 120 each.
   
![Screenshot (353)](https://github.com/DanielOladipupo/Employees-Data-Analysis-Project/assets/155446588/c0e4c99d-d651-4683-9739-1990182cd477)

5. **Distribution of Employees by Country:** The United States has the highest number of Employees among all other countries, totaling 643, whereas Brazil, with the lowest count, recorded 139 Employees.

![Screenshot (354)](https://github.com/DanielOladipupo/Employees-Data-Analysis-Project/assets/155446588/936ae523-a93b-4031-a5c9-b6a47ba2f1a5)

6. **Distribution of Employees Bonus by Department:** Among the departments, Accounting, Finance, and Human Resources have the highest bonus rates of 11%, while the IT Department has the lowest of 5%.
   
![Screenshot (355)](https://github.com/DanielOladipupo/Employees-Data-Analysis-Project/assets/155446588/b3a9591b-79ac-440f-8f4a-06f4bb7ef1b2)

### Dashboard



![Screenshot (356)](https://github.com/DanielOladipupo/Employees-Data-Analysis-Project/assets/155446588/3a57693a-e999-4ea4-8f20-99f90595cde6)


### Recommendation
Following a comprehensive analysis of the Employees Data, the following recommendations are proposed to enhance the performance and growth of the Organization Workforce:
- The organization should conduct a regular employee survey to determine satisfaction, collect feedback, and identify areas for improvement. This will help in shaping HR policies and ensuring that they align with Employee expectations and needs.
- There should be a salary adjustment or a review of compensation practices to ensure fairness. This will serve as a mechanism for employees motivation and performance, inspiring greater dedication and productivity in their roles.
- There should be a strategy to enhance gender balancing that will help in fostering an inclusive and equitable workplace culture that can leverage the strengths and perspectives of all employees, regardless of gender to drive success and innovation.
- Employee Turnover should be investigated to determine the root cause of the employee attrition and implementing effective strategies to address them.
















 




