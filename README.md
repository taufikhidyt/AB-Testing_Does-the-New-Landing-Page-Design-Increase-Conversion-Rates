# AB Testing using Python
## 1. Introduction
**Welcome to my AB Testing portfolio!**

A/B testing is a fundamental methodology in data science and digital marketing allowing organizations to make data-driven decisions regarding changes in their products or services. In this project, we aim to evaluate the impact of a new website design on user engagement. User engagement is a critical metric for website performance, often measured by the amount of time users spend on the site. By comparing user behavior between the current website design (A: control group) and the new design (B: treatment group), we can determine if the redesign leads to increased engagement.
![Ultimate Guide to A_B Testing with WordPress - Quertime](https://github.com/taufikhidyt/AB_Testing/assets/165252685/7e6c68ea-9659-43b5-b09b-20ea92327c9f)
Image source: https://id.pinterest.com/pin/366058275948776596/

**Project Objectives**:

**Determine the Effectiveness of the New Design**: Assess whether the new website design improves user engagement compared to the old design, 
**Business Recommendations**: Providing recommendations based on analysis results for informed decision-making.

## Data Scope
In this project, Data of ser behavior (whether they converted or not) between the current website design (A: control group) and the new design (B: treatment group) was used. 
Data obtained from Kaggle which can be accessed from : https://www.kaggle.com/datasets/zhangluyuan/ab-testing/data

The dataset contains 5 columns , 294480 records:
- user_id: unique id of the user who came to the website
- timestamp: timestamp that the user came to the page
- group: whether the user in treatment group or control group
- landing_page: whether the user saw the old page or new page
- converted: whether the user converted to a paid user. 1 means converted, 0 means not converted.

# 2. Data Cleaning
