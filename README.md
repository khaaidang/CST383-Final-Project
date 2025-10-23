# Predicting Software Engineering Job Trends in the U.S

#### Team Members: Kha Ai Dang, Neng Lao, Enrique Villegas

## Introduction
The Tech industry in the United States is rapidly changing and Software Engineers are some of the key players in driving innovation and economic growth. However, job availability and demand are influenced by factors such as corporate hiring strategies and remote work adoption. With that said, we hope to analyze these patterns in software engineering job listings within the United States to identify current demands, hiring trends, and employer preferences. Using data analysis and predictive modeling, our goal is to forecast future job availability. Ultimately, we are aiming to help job seekers and employers better understand how these factors shape opportunities in the industry and offer data-driven insights into the dynamics of the Software Engineer market.

**Our Goal:**  
In this project, our goal is to predict job availability and demand for software engineering roles in the United States. Using features such as Job Title, Company, Location, Employment Type, and Remote Work Options, we will create predictive models to estimate job openings and identify factors that influence hiring trends. Our analysis will show which skills and positions are in highest demand, how remote work affects opportunities, and how these patterns may shift over time. Our predictions will hopefully help job seekers and employers make data-driven decisions about our evolving software job market.

**Selection of Data:**  
For our Final Project, we used US Software Engineer Jobs from Kaggle:  
https://www.kaggle.com/datasets/mexwell/us-software-engineer-jobs?resource=download.  
  
This dataset contains over 50,000 jobs postings for software engineering positions in the United States and uses data that was collected on July 22, 2021. The postings provide details such as the Job Title, Company, Salary Ranges, Location, Employment Type, Employer Ratings, Urgency of Hiring, and Remote Work Option. This dataset contains information pertaining to employer behavior and demand signals. Both of these will allow us to track trends in the industry, such as Remote versus Onsite listings, Urgency Indicators, and Role Distribution in the United States.  

To supplement this dataset with a salary column, we combined it with another dataset from the U.S Bureau of Labor Statistics (BLS) under the Occupational Employment and Wage Statistics (OEWS) program.  
https://www.bls.gov/oes/oes_research_2024.htm  

All BLS Software and Web Developers, Programmers and Tester roles were considered equivalent to software engineer positions, because there are no separate SWE occupation code in the BLS dataset. We combined the following occupation codes:
- 15-1251 Computer Programmers
- 15-1252 Software Developers
- 15-1253 Software Quality Assurance Analysts and Testers
- 15-1254 Web Developers
- 15-1255 Web and Digital Interface Designers  
  
This dataset also contains geographic and regional information such as which states have the highest employment, what their mean wage is, and what are the highest-paying metro areas.

**Features**  
From Kaggle: title, company, salary, location, hires_needed, urgently_hiring, remote_work_model, is_remote, city_state
From BLS: AREA_TITLE, TOT_EMP, A_MEAN

## Methods
**Tools:**
- NumPy, Pandas, Matplotlib, Seaborn, and Scikit-learn
- GitHub for Version Control
- Google Colab, Spyder, VS CODE, Jupyter Notebook

**Models:**
- KNeighborsClassifier, Linear Regression

## Results

## Discussion

## Summary
