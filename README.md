# **UNDER CONSTRUCTION**

# About Me

## Education

<details>
<summary>**Google Advanced Data Analytics Professional Certificate** | Coursera | 13 September 2023</summary>

* This is what I did in the course.

</details>

<details>
<summary>**PhD, Philosophy** | Uni. of Johannesburg | April 2021</summary>

* This is what I did in my PhD.

</details>

<details>
<summary>**MA by dissertation, Philosophy** *cum laude* | Uni. of Johannesburg | DATE</summary>

* This is what I did in my MA.

</details>

<details>
<summary>**BA Honours, Philosophy** *cum laude* | Uni. of Johannesburg | DATE</summary>

* This is what I did in my Honours.

</details>

<details>
<summary>**BA Politics, Philosophy, and Economics** | Uni. of Johannesburg | DATE</summary>

* This is what I did in my Bachelors.

</details>

## Experience

<details>
<summary>**KPMG AU Data Analytics Job Simulation on Forage** | Sep 2023</summary>

* Completed a simulation focused on advising a client on customer targeting with the Data, Analytics & Modelling team
* Assessed data quality and completeness in preparation for analysis
* Analysed data to target high-value customers based on demographics and attributes
* Developed dashboards to communicate findings with visuals

</details>

<details>
<summary>**FTC Lecturer in Philosophy** | Various Universities | Jul 2023 to present</summary>

* I taught stuff.

</details>

<details>
<summary>**Doctoral Researcher** | Uni. of Johannesburg | Feb 2018 to Mar 2021</summary>

* I researched stuff.

</details>

# Portfolio

## Student Performance in Ethics Course

*24 July 2023 – (Ongoing)*

---

## **LAPD**: Service Call Intelligence Dashboard

*27 September to 6 October 2023*

Policing resources are scarce, and deploying assets without intelligence can put law enforcement officers and the public at risk. Awareness of trends in policing service needs – both where and when they are needed – is crucial for optimising safety, providing the public with policing services, and mitigating against officer burnout.

These interactive dashboards provide critical information across a wide matrix of spatial and time-related properties. Decisionmakers on resource allocation have at their fingertips LAPD service call information from 2019 at the city, area, and reporting district levels. Precise time classes can be used to fine-grain intelligence by considering the year, month, time of day, and season. Service calls are also grouped by certain classes (e.g., violence, child-related, etc.), and the top 10 most common service calls are highlighted.

See the Python code for data preparation [here](https://github.com/DStrix66/lapd-dashboard/blob/main/lapd_eda.ipynb) and the interactive dashboard on Tableau Public [here](https://public.tableau.com/app/profile/david.scholtz/viz/LAPDServiceCalls2019-2023fin/Story1).

![lapd_dashboard1](/portfolio_images/lapd1.png)

![lapd_dashboard2](/portfolio_images/lapd2.png)

---

## **Salifort Motors**: Customer Churn

*2-13 September 2023*

---

## **Waze**: User Churn Project

*9 June to 1 September 2023*

Waze is a community driven navigation app that helps millions of users get to where they’re going through real-time road alerts and an up-to-the-moment map.
Typically, high user retention rates indicate satisfied users who repeatedly use the Waze app over time. This project develops a churn prediction model to help prevent churn, improve user retention, and grow Waze’s business. The questions answered in this project were Who are the users most likely to churn? Why do users churn? and, When do users churn?

This was a three-stage project, in which I was involved after the first stage. See the code for these stages [here](https://github.com/DStrix66/waze-user-churn.git).

<details>
<summary>**Project Outline**</summary>

### **Stage 1: Project proposal** (not involved)

1. Data was imported and explored for useful user churn information
2. A project proposal was accepted by Waze for an in-depth EDA (stage 2), statistical testing (stage 3), and predictive modelling (stages 4 & 5)

### **Stage 2: EDA** (9-12 June 2023)

1. Churn rate is highest for users who didn’t drive using the app much in the last month 
2. Device types had similar churn rates
3. Key conclusion: Statistical tests need to be run on variable classes (e.g., device used) to determine significant relationships with churn

### **Stage 3: Two-sample hypothesis test** (24-28 June 2023)

1. Calculations show that iPhone users have a higher average use of the app compared to Android users
2. However, this difference is not statistically significant
3. Key conclusion: More marketing-relevant data is needed for statistically examining churn by device use and other variables.

### **Stage 4:Logistic regression analysis** (17-20 July 2023)
1. Ran a binomial logistic regression with slightly better than benchmark precision but very low recall
2. Contrary to what was expected from EDA findings, the amount of driving was the second-least-important variable for predicting churn

### **Stage 5: Predictive classification models** (28 August to 1 September 2023)

1. Features of interest were extracted, and a random forest model and a GBM model on predicting user churn were developed and performances compared
2. The GBM outperformed the random forest model, and it had similar levels of precision and accuracy to the logistic regression, with a much better (though still unsatisfactory) recall score
3. The models confirmed the insufficiency of the data and the need for driver-level data collection (e.g., drive times and geographic information) and user interaction with the app (e.g., input a road hazard).

</details>

<details>
<summary>**Findings**</summary>

It was established that the data is insufficient for reliably predicting user churn and that further granular data is needed on app usage and geography. Given the data, it could be determined that users who are professional drivers and who use the app more in a month are the biggest predictors of whether a user will churn or be retained.

</details>

![waze_confusionmatrix](/portfolio_images/waze_gbm_cm.png)

![waze_featureimportance](/portfolio_images/waze_gbm_feature_importance.png)

---

## **Workplace Absenteeism**

*24 April – 3 May 2023*

Employee absenteeism can have a significant impact on a company's productivity, operational efficiency, and overall performance. By conducting a comprehensive analysis and developing a predictive model, this project provides support to Human Resources decision-making. The project provides valuable insights into employee absenteeism patterns and delivers actionable recommendations for businesses to optimise workforce management, enhance productivity, and improve employee satisfaction.

**Key Findings and Recommendations**

* Scheduled medical appointments tend not to result in excessive workplace absenteeism, whereas having unplanned medical needs is a strong predictor
* HR is recommended to consider interventions to improve employee health and early medical need detection, e.g.:
    * scheduling regular medical check-ups at company cost
    * driving improved health culture in the workplace (e.g., a workplace gym, canteen that serves balanced meals)
* Employees staying further from work and with more children may be offered benefits like a tax-deductible company fuel card or a partial work-from-home accommodation

See the code [here](www.link.com). 

![absenteeismdashboard](/portfolio_images/absenteeism.png)

---
