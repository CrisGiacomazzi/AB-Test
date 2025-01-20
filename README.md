# Hypothesis-Test

# Assessing the Effectiveness of a New Training Program on Employee Performance

Cristiane Mecca Giacomazzi (Data Analyst)
This project was developed with Cross-industry standard process for data mining (CRISP-DM) methodology.
The following topics will be presented:
1. Business Understanding
2. Data Understanding
3. Ethical Statements
4. Hypothesis Formulation
5. Data Preparation
6. Libraries used for this project
7. Project Plan
8. Results
9. Communication and Action
  a.Data visualization
  b.Minthos Pyramides Analysis
10. References

## 1. Business Understanding

Businesses of all sizes invest substantial resources in employee training annually. These programs are designed to enhance employee skills, prepare them for increased responsibilities, and support their professional development. Effective training fosters a culture of continuous learning and can lead to improved productivity. To determine the effectiveness of training initiatives, it is essential to measure key performance indicators (KPIs) and conduct statistical analysis. In this fictional case, the company spends $20,000.00 in training annually. 

This project aims to evaluate the outcomes of a specific training program implemented within a company and demonstrate the results to the stakeholder, CEO of the company.

## 2. Data Understanding

<img width="642" alt="Screen Shot 2024-12-30 at 12 49 03 PM" src="https://github.com/user-attachments/assets/035179e2-7097-4ca8-80c9-1d5aceca0f88" />

Table by author (2024)

## 3. Ethical

For this project, it was used a public dataset from Kaggle called "Employee Performance and Productivity Data" [link](https://www.kaggle.com/datasets/mexwell/employee-performance-and-productivity-data/data)

## 4. Hypothesis Formulation

* Null Hypothesis (H0): The new training program has no effect on employee performance (mean performance after the training is equal to mean performance before the training).
* Alternative Hypothesis (H1): The new training program has a significant effect on employee performance (mean performance after the training is different from mean performance before the training).

## 5. Data preparation
The original dataset was filtered using 2019 and 2020 dates, to align with the project’s goal. The Hire date column was transformed into data time variable type, to be better filtered. There are no duplicates and no missing values to handle. A Feature engineering step was added, to create a new column called “group” to perform the necessary tests. 

## 6.Libraries used for this project

<img width="640" alt="Screen Shot 2024-12-30 at 12 52 39 PM" src="https://github.com/user-attachments/assets/f402a82f-b3ce-4043-b70e-861d32c17395" />


Table by author (2024)

## 7. Project Plan

Following the definition of the research question, a **hypotheses test** was developed. A thorough **data preparation process**, including cleaning, organization, and the creation of analytical variables, ensured data integrity. **Exploratory Data Analysis** (EDA) revealed key insights into the data, informing the subsequent statistical analysis. A **t-test** was employed to evaluate the statistical significance (_p-value_ < 0.05) differences between the means of the two groups (2019 vs 2020), directly addressing the research question. The t-test results provided a clear basis for evaluating the initial hypotheses and guiding further action. V**isualization (graphs) in Python and Power BI** was strategically used to communicate these findings effectively to stakeholders, facilitating understanding and decision-making. Furthermore, a **Mynthos Pyramides Analysis and an SCQA framework** were done to ensure effective, quick, and clear communication of complex issues to business executives.

<img width="633" alt="Screen Shot 2024-12-30 at 12 55 00 PM" src="https://github.com/user-attachments/assets/8c8a202b-63ba-4fc4-b7ca-bce0418881d7" />

Figure 1 made by author (2024)

## 8. Results

* The t-test resulted in a _p_>0.05 (0.54), which means the **new training program has no effect on employee performance**. 
* It is recommended that we conduct a thorough **review of existing training programs** to identify areas for improvement and optimization
* The **performance varied according to the month of year**, further investigation is necessary to understand the reasons.
* The **performance was similar among different educational levels**, and it (the performance) **is not related to the training intensity** of employees, however, further investigation is necessary.

## 9. Communication and Action

### a. Data Visualization
Python

<img width="330" alt="Screen Shot 2024-12-30 at 12 57 11 PM" src="https://github.com/user-attachments/assets/d3ed1938-2c9a-450d-9395-dc6571a73c1b" />

Figure 2. The graphic depicts that training does not change the performance of the employees. 

Power BI

<img width="639" alt="Screen Shot 2024-12-30 at 12 57 53 PM" src="https://github.com/user-attachments/assets/8d846525-241c-4ad2-8c52-b0ba5161d730" />

Figure 3. Dashboard generated from Google Colab connected with Power BI, depicts a summary of the investigation, suggesting a review of the employee training.

### b. Minthos Pyramides Analysis

<img width="595" alt="Screen Shot 2024-12-30 at 12 59 01 PM" src="https://github.com/user-attachments/assets/d35984df-ceca-4890-a1e0-d7cac0a64547" />

## 10. References

Freifeld, L. (November 14, 2023). 2023 Training Industry Report. 

Indeed. (September 6, 2023). Understanding the Importance of Training Employees. 

Skillsoft. 2024. How to Know If Your Learning Program Is Working. 











