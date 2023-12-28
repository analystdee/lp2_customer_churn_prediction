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


