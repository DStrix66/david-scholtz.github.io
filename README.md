<h1><strong>UNDER CONSTRUCTION</strong></h1>

<h1>About Me</h1>

<p>I'm a freelance data analyst with experience using statistics, Python, interactive dashboards, and machine learning algorithms to solve business problems. Technical skills are freely available to learn &ndash; my unique value consists in my ability to critically understand business needs and creatively apply data analytic solutions that are accessible to end users.</p>

<p>I have a background in academic Philosophy research and lecturing, giving me foundational skills in critical thinking, stakeholder communication, and complex problem solving. If you don't want to talk data, I'm always down to chat about rationality and epistemology.</p>

<h2>Education</h2>

<style>
summary {
    margin-bottom: 3px;
}
ul {margin-bottom: 3px;
   }
</style>

<details>
   <summary>
      <strong>Google Advanced Data Analytics Professional Certificate</strong> <br/>Coursera | 13 September 2023
   </summary>

   <ul>
      <li>This is what I did in the course.</li>
      <li>And then I did this.</li>
   </ul>
</details>

<details>
   <summary>
      <strong>PhD, Philosophy</strong><br/>Uni. of Johannesburg | April 2021
   </summary>

   <ul>
      <li>This is what I did in my PhD.</li>
   </ul>
</details>

<details>
  <summary>
    <strong>MA by dissertation, Philosophy <em>cum laude</em></strong><br/>Uni. of Johannesburg | DATE
  </summary>

  <ul>
    <li>This is what I did in my MA.</li>
  </ul>
</details>

<details>
   <summary>
     <strong>BA Honours, Philosophy <em>cum laude</em></strong><br/>Uni. of Johannesburg | DATE
   </summary>

   <ul>
      <li>This is what I did in my Honours.</li>
   </ul>
</details>

<details>
  <summary>
    <strong>BA Politics, Philosophy, and Economics</strong><br/>Uni. of Johannesburg | DATE
  </summary>

  <ul>
    <li>This is what I did in my Bachelors.</li>
  </ul>
</details>

<h2>Experience</h2>

<details>
  <summary>
    <strong>KPMG AU Data Analytics Job Simulation on Forage</strong><br/>KPMB | Sep 2023
  </summary>

   <ul>
      <li>Completed a simulation focused on advising a client on customer targeting with the Data, Analytics & Modelling team</li>
      <li>Assessed data quality and completeness in preparation for analysis</li>
      <li>Analysed data to target high-value customers based on demographics and attributes</li>
      <li>Developed dashboards to communicate findings with visuals</li>
   </ul>
</details>

<details>
  <summary>
    <strong>FTC Lecturer in Philosophy</strong><br/>Various Universities | Jul 2023 to present
   </summary>

  <ul>
    <li>I taught stuff.</li>
  </ul>
</details>

<details>
  <summary>
    <strong>Doctoral Researcher</strong><br/>Uni. of Johannesburg | Feb 2018 to Mar 2021
  </summary>

   <ul>
      <li>I researched stuff.</li>
   </ul>
</details>

<h1>Portfolio</h1>

<h2>Student Performance in Ethics Course</h2>

_24 July 2023 – (Ongoing)_

---

<h2><strong>LAPD</strong>: Service Call Intelligence Dashboard</h2>

_27 September to 6 October 2023_

Policing resources are scarce, and deploying assets without intelligence can put law enforcement officers and the public at risk. Awareness of trends in policing service needs – both where and when they are needed – is crucial for optimising safety, providing the public with policing services, and mitigating against officer burnout.

These interactive dashboards provide critical information across a wide matrix of spatial and time-related properties. Decisionmakers on resource allocation have at their fingertips LAPD service call information from 2019 at the city, area, and reporting district levels. Precise time classes can be used to fine-grain intelligence by considering the year, month, time of day, and season. Service calls are also grouped by certain classes (e.g., violence, child-related, etc.), and the top 10 most common service calls are highlighted.

See the Python code for data preparation [here](https://github.com/DStrix66/lapd-dashboard/blob/main/lapd_eda.ipynb) and the interactive dashboard on Tableau Public [here](https://public.tableau.com/app/profile/david.scholtz/viz/LAPDServiceCalls2019-2023fin/Story1).

![lapd_dashboard1](/portfolio_images/lapd1.png)

![lapd_dashboard2](/portfolio_images/lapd2.png)

---

<h2><strong>Salifort Motors</strong>: Customer Churn</h2>

_2-13 September 2023_

---

<h2><strong>Waze</strong>: User Churn Project</h2>

_9 June to 1 September 2023_

Waze is a community driven navigation app that helps millions of users get to where they’re going through real-time road alerts and an up-to-the-moment map.
Typically, high user retention rates indicate satisfied users who repeatedly use the Waze app over time. This project develops a churn prediction model to help prevent churn, improve user retention, and grow Waze’s business. The questions answered in this project were Who are the users most likely to churn? Why do users churn? and, When do users churn?

This was a three-stage project, in which I was involved after the first stage. See the code for these stages [here](https://github.com/DStrix66/waze-user-churn.git).

<details>
<summary><strong>Project Outline</strong></summary>

<h3><strong>Stage 1: Project proposal</strong> (not involved)</h3>

1. Data was imported and explored for useful user churn information
2. A project proposal was accepted by Waze for an in-depth EDA (stage 2), statistical testing (stage 3), and predictive modelling (stages 4 & 5)

<h3><strong>Stage 2: EDA</strong> (9-12 June 2023)</h3>

1. Churn rate is highest for users who didn’t drive using the app much in the last month
2. Device types had similar churn rates
3. Key conclusion: Statistical tests need to be run on variable classes (e.g., device used) to determine significant relationships with churn

<h3><strong>Stage 3: Two-sample hypothesis test</strong> (24-28 June 2023)</h3>

1. Calculations show that iPhone users have a higher average use of the app compared to Android users
2. However, this difference is not statistically significant
3. Key conclusion: More marketing-relevant data is needed for statistically examining churn by device use and other variables.

<h3><strong>Stage 4:Logistic regression analysis</strong> (17-20 July 2023)</h3>

1. Ran a binomial logistic regression with slightly better than benchmark precision but very low recall
2. Contrary to what was expected from EDA findings, the amount of driving was the second-least-important variable for predicting churn

<h3><strong>Stage 5: Predictive classification models</strong> (28 August to 1 September 2023)</h3>

1. Features of interest were extracted, and a random forest model and a GBM model on predicting user churn were developed and performances compared
2. The GBM outperformed the random forest model, and it had similar levels of precision and accuracy to the logistic regression, with a much better (though still unsatisfactory) recall score
3. The models confirmed the insufficiency of the data and the need for driver-level data collection (e.g., drive times and geographic information) and user interaction with the app (e.g., input a road hazard).

</details>

<details>
<summary><strong>Findings</strong></summary>

It was established that the data is insufficient for reliably predicting user churn and that further granular data is needed on app usage and geography. Given the data, it could be determined that users who are professional drivers and who use the app more in a month are the biggest predictors of whether a user will churn or be retained.

</details>

![waze_confusionmatrix](/portfolio_images/waze_gbm_cm.png)

![waze_featureimportance](/portfolio_images/waze_gbm_feature_importance.png)

---

<h2><strong>Workplace Absenteeism</strong></h2>

_24 April – 3 May 2023_

Employee absenteeism can have a significant impact on a company's productivity, operational efficiency, and overall performance. By conducting a comprehensive analysis and developing a predictive model, this project provides support to Human Resources decision-making. The project provides valuable insights into employee absenteeism patterns and delivers actionable recommendations for businesses to optimise workforce management, enhance productivity, and improve employee satisfaction.

**Key Findings and Recommendations**

- Scheduled medical appointments tend not to result in excessive workplace absenteeism, whereas having unplanned medical needs is a strong predictor
- HR is recommended to consider interventions to improve employee health and early medical need detection, e.g.:
  - scheduling regular medical check-ups at company cost
  - driving improved health culture in the workplace (e.g., a workplace gym, canteen that serves balanced meals)
- Employees staying further from work and with more children may be offered benefits like a tax-deductible company fuel card or a partial work-from-home accommodation

See the code [here](www.link.com).

![absenteeismdashboard](/portfolio_images/absenteeism.png)

---
