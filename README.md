# AB Testing using Python
## 1. Introduction
**Welcome to my AB Testing portfolio!**

A/B testing is a fundamental methodology in data science and digital marketing allowing organizations to make data-driven decisions regarding changes in their products or services. 

![Ultimate Guide to A_B Testing with WordPress - Quertime](https://github.com/taufikhidyt/AB_Testing/assets/165252685/7e6c68ea-9659-43b5-b09b-20ea92327c9f)

Image source: https://id.pinterest.com/pin/366058275948776596/

### Scenario

**Company**: E-Commerce

**Experiment/Treatment Setup**
- The company has two versions of their landing page: the old version (current page) and the new version (proposed redesign).
- Visitors to the website are randomly assigned to either the old page or the new page.
- The goal is to see if the new page increases the rate at which visitors convert into paying customers.

**Project Objectives**:

- **Determine the Effectiveness of the New Landing Page**: To determine if a new landing page design leads to a higher conversion rate compared to the current (old) landing page.
- **Business Recommendations**: Providing recommendations based on analysis results for informed decision-making.

### Data Scope
In this project, Data of costumer behavior (whether they converted or not) between the current website design (control group) and the new design (treatment group) was used. 
Data obtained from Kaggle which can be accessed from : https://www.kaggle.com/datasets/zhangluyuan/ab-testing/data

The dataset contains 5 columns , 294480 records:
- user_id: Unique id of the user who came to the website
- timestamp: Timestamp when the user visited the page.
- group: Indicates whether the user was in the control group (saw the old page) or the treatment group (saw the new page).
- landing_page: Indicates whether the user saw the old page or the new page.
- converted: Indicates whether the user converted to a paid customer (1 for converted, 0 for not converted).

## 2. Data Cleaning and Visualization
**Clean the data by**:
- Remove the mismatched data: Remove the records that control group visit new_page and treatment group visit old_page
- Remove duplicate user_id

**Visualize the clean data**: Examine the distribution of users across the control and treatment groups.
![download](https://github.com/taufikhidyt/AB_Testing/assets/165252685/d7e38fc7-a71e-4607-936d-27dc46339cc2)

## 3. AB Testing

To conduct a structured and objective analysis, we define the following hypotheses:
### Formulate Hypotheses:
- **Null Hypothesis (H0)**: The new website design does not impact user engagement, meaning there is no significant difference in the average time spent on the site between the control group and the treatment group.
- **Alternative Hypothesis (H1)**: The new website design increases user engagement, resulting in a significant difference in the average time spent on the site between the control group and the treatment group.




