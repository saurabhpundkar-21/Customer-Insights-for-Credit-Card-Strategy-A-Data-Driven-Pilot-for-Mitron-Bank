# Customer-Insights-for-Credit-Card-Strategy-A-Data-Driven-Pilot-for-Mitron-Bank
* Domain - Banking
* Function - Strategy
## Mitron Bank Credit Card Analysis Project

## Project Overview
This project was conducted for Mitron Bank, a legacy financial institution headquartered in Hyderabad, which plans to introduce a new line of credit cards to expand its product offerings. AtliQ Data Services proposed a data-driven solution for this initiative. As part of a pilot project, Mitron Bank provided a sample dataset of 4000 customers across five cities, focusing on their online spending and demographic details. The insights generated from this data will guide the creation of tailored credit card products.

## Problem Statement and Background
Mitron Bank is exploring ways to introduce a new line of credit cards. Peter Pandey, a data analyst at AtliQ Data Services, was tasked with analyzing the customer data provided by the bank and delivering key insights to the strategy team. Imagine yourself as Peter Pandey, diving deep into customer demographics, spending patterns, and credit scores to uncover trends and preferences that could shape the product’s success. His analysis is crucial for securing the project by providing actionable, data-driven recommendations that demonstrate a deep understanding of the target customers needs.

## Key Objectives
The key objectives of this project were:
1.Analyze the spending patterns and demographic information of Mitron Bank's customers sample data and generate insights to be presented to the strategy team of Mitron Bank.
2.Provide actionable insights to help Mitron Bank tailor credit card offerings to specific customer segments.
3.Identify key customer groups that are most likely to be high-value users of the new credit cards.
4.Present the findings in a clear, visual, and impactful Tableau dashboard.

## Data Description
The project uses two primary data sources provided by Mitron Bank:

 dim_customers.csv: Contains demographic information about customers, such as:

* customer_id: Unique ID assigned to each customer.
* gender: Gender of the customer (Male, Female).
* age_group: Age groups of customers (e.g., 21-24, 25-34).
* marital_status: Marital status (Single, Married).
* city: Customer's city of residence (e.g., Mumbai, Delhi-NCR).
* occupation: Profession (e.g., Salaried IT Employees, Business Owners).
* average_income: Monthly average income of the customer (in INR).

fact_spends.csv: Contains information about customers' online spending across various categories, including:

* customer_id: Unique ID linked to the dim_customers table.
* month: Month in which the spending was recorded.
* category: Spending category (e.g., Entertainment, Electronics).
* payment_type: Type of payment method used (e.g., Debit Card, Credit Card).
* spends: Total amount spent in the specified category and month.
  

 ## Dashboard Description
 
 The Tableau dashboard provides multiple views that help decision-makers at Mitron Bank understand customer behavior and preferences. The dashboard includes the following pages:
* Home Page : A view that directs users to specific analysis sections.
* Demographics: A breakdown of customers by gender, age, occupation, and city, helping to understand customer diversity.
* Spend Analysis - 1: A detailed analysis of average customer spending across various factors such as age, category, and occupation
* Spend Analysis - 2: A more nuanced analysis considering two factors at once, such as category and gender, occupation and age group.
* Income Analysis: Assesses average income utilization across different demographic segments, providing insights into how income influences spending behavior and credit card usage potential.

https://github.com/user-attachments/assets/b0b6adff-48db-4824-b4db-22f242ad3f7c

## Approach and Methodology
* Data Importation: Loaded data from CSV files into Tableau, consisting of 4000 customers and 860,000 records.
* Data Exploration and Validation: Performed using MySQL to ensure consistency and integrity.
* Table Relationships: Established relationships between customer and spending tables, using Excel-direct method to implement sheet-swapping functionality.
* Calculated Fields: Created calculated fields for total spending, average income, and income utilization.
* Parameter Creation: Developed parameters to enable filtering and button functionality.
* Spending Insights: Derived key insights into customer spending behavior, considering demographics such as occupation, gender, city, and age.
* Customer Segmentation: Identified high-value customer segments for targeted credit card features.
* Recommendations: Proposed key features for the new credit card based on customer behavior insights.

## Insights Generated
* Spending Patterns: Identified where customers are spending the most (e.g., Electronics, Apparel) and analyzed the effect of demographics (age, occupation, etc.) on spending behavior.
* Income Utilization: Analyzed how customers’ average income utilization affects their likelihood of using credit cards.
* High-Value Segments: Segmented customers likely to be the most valuable for the new credit card offering, such as IT professionals and business owners in certain age groups.

## Recommendations
* Targeted Credit Card Benefits:
  * Design credit card offerings that cater to middle-class customers, particularly male salaried IT professionals in the 25-44 age range.
  * Introduce perks aligned with essential spending categories (e.g., bills, electronics, and groceries) and popular modes of payment like credit cards and UPI.
    
* Customized Rewards Program:
  * Consider segment-specific reward points for categories based on demographic insights: higher rewards for bills, electronics, and groceries for salaried IT employees.
  * Implement a bonus rewards program in September to capitalize on peak spending trends.
    
* Enhanced Marketing in Mumbai:
* Allocate more marketing resources to Mumbai, where spending and income utilization are highest, and tailor campaigns to the specific spending habits of salaried IT employees.
  
* Differentiated Card Products:
  * Offer card products with features tailored for young (21-24) customers focused on lifestyle categories (e.g., entertainment, apparel).
  * Introduce products catering to older demographics (45+) with more modest spending but focused on essential categories like health & wellness.
    
* Flexible Payment Options:
  * Encourage the use of credit cards for high-value categories (apparel, electronics, and bills) by offering cashback or discounts.
  * Highlight the ease and benefits of UPI for groceries and food-related spending, which may appeal to married customers.

 ## Key Learnings
1. Data Modeling and Cleaning: Gained experience in cleaning and preparing data using Tableau.
2. Creation of Calculated Fields & Parameters: Developed advanced calculations and parameter- 
   driven analysis to customize dashboard functionality.
3. Excel-Direct Method: Applied this method to create a seamless sheet-switching experience 
   with buttons.
4. Dashboard Design: Designed professional dashboards with containers, navigation buttons, and 
   show/hide features for a polished look.
5. Custom Icons and Color Palettes: Learned how to incorporate personalized icons and color 
   schemes using tools like Figma and Flaticon.
6. Button Activation: Leveraged Tableau’s action functionality to implement interactive buttons.
7. Chart Customization: Created advanced charts (area plots, pie charts, tree maps, maps) with 
   conditional formatting.
8. Tooltips: Customized tooltips to display contextual insights, enhancing user interactivity 
   and understanding of the data.
9. Income Utilization Concept: Understood the concept of average income utilization and its 
   relation to credit card usage likelihood.

## Technologies Used
• Tableau

## Conclusion
This project provided actionable insights for Mitron Bank to introduce a new line of credit cards tailored to specific customer needs. By analyzing customer demographics, spending behaviors, and income utilization, the project helped identify key customer segments, offering significant value to the bank’s strategy team.

## Future Enhancements
* Incorporating more data from other regions or customer segments to further refine the credit 
  card offering.
* Integrating real-time data analysis for continuous updates and improvements.
