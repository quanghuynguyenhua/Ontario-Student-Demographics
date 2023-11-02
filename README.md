# Ontario-Student-Demographics
[ON-GOING] <br />
Description: Analyze the impact of student demographics and school characteristics on academic achievement in Ontario, Canada, in the period of 2017-2022. 

<!-- INTRODUCTION -->
## I. INTRODUCTION
This is a group project including Kylie Snow, Sonia-Deepak Patel, Hemasri Appavu-Krishnaraju, and Huy Nguyen (me).<br />
Date: 2-Nov-2023 <br />
<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- II. DEFINITION OF BUSINESS PROBLEM -->
## II. DEFINITION OF BUSINESS PROBLEM
2.1 Business Problem
Analyze the impact of student demographics and school characteristics on academic achievement. <br />
2.2 Context
The Ontario Ministry of Education delivers early years, childcare, and publicly funded education from Kindergarten to Grade 12 (Government of Ontario, 2023). The goal of the project is to use the provided dataset containing school information, student demographics, and student achievement data to gain insights into the factors that influence academic achievement in publicly funded elementary and secondary schools. This analysis aims to help Ontario’s Ministry of Education make data-driven decisions to improve student outcomes.
2.3 Importance to the Organization
Analyzing academic achievement and identifying student demographics and school characteristics that effect academic achievement will aid in Ontario’s Ministry of Education’s ability to provide early intervention for the schools that consistently underperform on standardized testing. Funding can therefore be better allocated to ensure all children can obtain a high level of education at the elementary and secondary level.
<p align="right">(<a href="#readme-top">back to top</a>)</p>

III. Project Objectives
3.1 Identify Disparities in Academic Achievement: Analyze student achievement data for grade 3 and 6 EQAO reading, writing, and mathematics, grade 9 EQAO academic and applied results, and grade 10 OSSLT scores to identify disparities among different schools and student groups.
3.2 Explore the Impact of School Characteristics: Examine how school characteristics (such as school board, location, size) impact student achievement. Are there patterns in achievement based on school attributes?
3.3 Investigate the Effect of Student Demographics: Investigate the relationship between student demographics (parental background, special education services, first language spoken, and new students to Canada) and academic performance. Are there specific demographic factors that correlate with higher or lower achievement?
3.4 Provide Recommendations for Interventions and Resource Allocation: Based on the insights gained, recommend interventions and resource allocation strategies to address achievement disparities. For example, should specific schools receive additional resources or support programs based on their unique challenges?
3.5 Predictive Analytics: Build predictive models to forecast student achievement based on various factors, allowing schools to identify at-risk students early and implement targeted interventions.
3.6 Trends Analysis: Analyze trends over multiple years to identify any improvements or deterioration in academic achievement, enabling schools to adapt their strategies accordingly.

IV. Description of Data
4.1 Data Sources
The data source is School Information and Student Demographics and is obtained from the Government of Ontario Data Catalogue: https://data.ontario.ca/dataset/school-information-and-student-demographics. The data is reported by individual schools, school boards, EQAO and Statistics Canada and processed by the Government of Ontario (Government of Ontario, 2023). 
4.2 Data Description
There is 5 school years of data available from 2017-2018 to 2021-2022 for public, Roman Catholic, publicly funded hospitals, and provincial schools (Government of Ontario, 2023). 
The Data includes: 
•	School board information
•	School information 
•	Grade 3 and Grade 6 EQAO student achievements for reading, writing and mathematics. 
•	Grade 9 EQAO academic and applied stream student achievements 
•	Grade 10 Literacy Test (OSSLT) student achievements 
•	Student demographic percentages for student parents, special education, first language spoken and new students to Canada.  (Government of Ontario, 2023)
The data excludes private schools, Education and Community Partnership Programs (ECPP), summer and night schools (Government of Ontario, 2023). 

V. Data Analysis
It's essential to preprocess the data, perform cross-validation, and evaluate the models using appropriate metrics (e.g., RMSE, R-squared) to determine which machine learning technique works best. Additionally, may need to combine and fine-tune these techniques to achieve the best results.
Below are some machine learning techniques that are well-suited for this problem:
1.	Linear Regression
2.	Decision Trees
3.	Random Forest
4.	Gradient Boosting
