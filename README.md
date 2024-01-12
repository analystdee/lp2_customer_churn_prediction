# A Machine Learning Approach to Analyze Customer Churn

## Table of Content 
- [Project Description](#project-description)
- [Data sources](#data-sources)
- [Tools Used](#tools-used)
- [Data Cleaning/Preparation](#data-cleaning)

- [Exporatory Data Analysis](#exporatory-data-analysis)
- [Results/Findings](#results)
- [Recommendation](#recommendation)
- [Reference](#reference)

## Project Description
This repository contains the codebase and resources for a customer churn prediction project tailored specifically for Vodafone Telecommunications. Leveraging machine learning models and advanced analytics, this project aims to forecast customer churn rates within the company's subscriber base.The goal of this project is to develop a supervised machine learning model to analyze customer churn within the telecom company. The model will utilize any provided dataset to generate new observations by accurately determining whether a customer is likely to churn or not. This initiative aims to provide valuable insights into customer behavior, enabling the identification of potential churn and facilitating strategic interventions to retain customers effectively. The outcome of the project will contribute to a more informed and proactive approach to customer relationship management within Vodafone.

Leveraging Predictive Analytics: Understanding and Preventing Customer Churn

In today’s competitive business landscape, customer churn, the loss of customers over a specific period, poses a significant challenge for companies across industries. Not only does it lead to revenue erosion, but it also amplifies customer acquisition costs, impacting the bottom line and hindering growth prospects.

Understanding the intricate patterns and behaviors that lead to customer churn is crucial. Predictive analytics and machine learning have emerged as powerful tools to analyze historical data and forecast potential churners, allowing businesses to take proactive measures to retain customers and enhance customer loyalty.

The goal of this project is to develop a supervised machine learning model to analyze customer attrition within a telecom company. The model will utilize any provided dataset to generate new observations by accurately determining whether a customer is likely to churn or not. This initiative aims to provide valuable insights into customer behavior, enabling the identification of potential churn and facilitating strategic interventions to retain customers effectively. The outcome of the project will contribute to a more informed and proactive approach to customer relationship management within the company.

## Data sources 
Thanks to Azubi Africa for providing me with access to this dataset. The data for this project was divided into three distinct parts.
The initial dataset was stored in a Microsoft SQL Server. I established a remote connection to it using the **pyodbc** library.
The second dataset for this project was sourced from a GitHub repository and was formatted as a CSV file.
The third dataset, intended to serve as the test dataset, was found on OneDrive, also in CSV format.

  ## Tools Used
Tools Used in the Project:
#### Programming Language:
- Python
#### Integrated Development Environment (IDE):
 - VSCode: A general-purpose IDE with robust support for Python development.
#### Libraries and Frameworks:
- scikit-learn 
- Pandas
- NumPy
#### Data Visualization:
- Matplotlib
- Seaborn
#### Version Control:
- Git: Essential for version control, collaboration, and tracking changes in code.
### The data set includes information about:

* Customers who left within the company  — the column is called Churn.
* Services that each customer has signed up for — phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies
* Customer account information — how long they’ve been a customer (Tenure ), contract, payment method, paperless billing, monthly charges, and total charges
* Demographic info about customers — gender, age range, and if they have partners and dependents
Demographics
CustomerID: A unique ID that identifies each customer.
* Senior Citizen: Indicates if the customer is older: Yes, No
* Dependents: Indicates if the customer lives with any dependents: Yes, No. Dependents could be children, parents, grandparents, etc.
* Tenure in Months: Indicates the total amount of months that the customer has been with the company 
* total charges is  equal to each tenue times monthly charges.
* Multiple Lines: Indicates if the customer subscribes to multiple telephone lines with the company: Yes, No

  ## Exploratory Data Analysis (EDA) Overview

The Exploratory Data Analysis (EDA) stage plays a crucial role in unlocking the secrets of the dataset. Here, I dig into the data to uncover patterns, trends, and valuable insights. 

This deep dive isn't just about answering questions but setting the stage for a deeper understanding of the data. It's all about turning raw numbers into meaningful insights that guide the next steps in our analysis. Let's uncover the stories behind the data!




##    *Analytical Questions**

1.  Among customers who have churned, which type of contract is most prevalent

One pivotal aspect in understanding churn involves the examination of contract types prevalent among departed customers. Through meticulous analysis, it was revealed that among customers who churned, a significant majority were associated with short-term contracts. This insight directs attention towards the potential dissatisfaction or lack of commitment associated with shorter contract duration, urging businesses to reevaluate their offerings or engagement strategies.

2. Which gender has the highest rate of churning

Exploring the gender-based churn rates brought forth intriguing revelations. Contrary to conventional assumptions, the data indicated a slightly higher churn rate among male customers. While this disparity might stem from multifaceted reasons, it prompts businesses to reconsider their marketing approaches and tailor retention initiatives to address gender-specific preferences and concerns.

3. Is there a correlation between total charges and the type of contract

Another pivotal inquiry explored the correlation between total charges and the type of contract. The analysis uncovered a strong positive correlation between higher total charges and long-term contracts. This correlation hints at potential opportunities to incentivize long-term commitments by aligning pricing strategies with customer preferences and contract duration.

4. what is the percentage breakdown of customers who have left the company

Delving deeper into the percentage breakdown of customers who have left the company showcased a concerning trend. The analysis unveiled a substantial percentage of departed customers, underscoring the urgency for businesses to fortify their retention strategies and customer engagement initiatives. Understanding this breakdown aids in directing resources towards targeted retention efforts.

5. How does the churn rate vary based on the duration of customer subscription

Analyzing the churn rates concerning the duration of customer subscriptions portrayed an intriguing pattern. It demonstrated a progressive decline in churn rates as subscription duration increased. This observation emphasizes the significance of nurturing long-term relationships with customers and tailoring retention strategies to enhance loyalty over time.

Conclusion

Based on the analysis and the Chi-Square Test for Independence, we reject the null hypothesis, indicating a significant relationship between customer churn and the monthly charges. The bar plot illustrates a higher number of customers leaving the company, particularly among those with a higher monthly charges. To enhance customer retention strategies, the marketing department should consider tailoring promotional efforts or loyalty programs to address the needs and preferences associated with different monthly charges.In conclusion, deciphering customer churn patterns through meticulous data analysis empowers businesses to make informed decisions and implement targeted strategies. Understanding contract preferences, gender-specific trends, correlation insights, and duration-based variations is pivotal in curbing churn rates and fostering enduring customer relationships.


## Reference
I acknowledge the following sources for their contribution to this analysis:
[1]. https://github.com/sj50179/Google-Data-Analytics-Professional-Certificate/wiki/1.3.2.Outlining-the-data-analysis-process.
[2]. 19 Data Analysis Questions Examples For Efficient Analytics (datapine.com)
[3]. A Step-by-Step Guide to the Data Analysis Process [2023] (careerfoundry.com)
[4]. Data Analysis with Python - GeeksforGeeks
[5]. Indian Startup Funding (In-depth analysis) | Kaggle
[6]. Hypothesis Testing Steps & Examples - Data Analytics (vitalflux.com)
[7]. Data Cleaning: Definition, Benefits, And How-To | Tableau
[8]. Guide to Data Cleaning in ’23: Steps to Clean Data & Best Tools (aimultiple.com)
[9]. See 20 Different Types Of Graphs And Charts With Examples (datapine.com)
By presenting this analysis concisely and clearly, I aim to shed light on the funding landscape of the Indian start-up ecosystem, offering valuable insights for entrepreneurs, investors, and policymakers alike.


