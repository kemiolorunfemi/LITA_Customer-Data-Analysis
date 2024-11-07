# LITA_Customer-Data-Analysis

### Project Title: Customer Segmentation for a Subscription Service
---

### Project Objective:
The main objective of this project is to analyze the customer segmentation data for subscription service to understand customer behavior, track subscription types, and identify key trends in cancellations and renewals.

### Data Overview
**Customer ID:** Unique identification code for each Customer that subscribed for the Service offered by the company.

**Customer Name:** The name of each subscribing Customer.

**Region:** The location where each subscription was made.

**Subscription Type:** The specific subscription package opted for by each Customer.

**Subscription Start:** The time the subscrition began.

**Subscription End:** The time the subscrition began.

**Canceled:** The subscrition services that were stopped.

**Revenue:** The total amount generated from aech subscription service purchased.

**Subscription Duration:** The period subscription was active.

### Key Metrics
**1. Subscription Duration:** Calculated as the difference between the Subscription End and Subscription Start across all subscription.
**2. Total Revenue:** Calculated as the Sum of all the Revenue from the various subscriptions.
**3. Average Subscription Duration:** Calculated as the average of the difference between the Subscription End and Subscription Start across all subscription.
**4. Average Revenue:** Calculated as Average of the Total Revenue across the subscription Types

### Tools and Method Utilised
**Data Analysis:** The Sales Data was analysed with Microsoft Excel with the by generating Pivot Tables which were used to organise, summarize, and filter the data for easy understanding. 

**Data Visualization**: Bar charts and Pie Charts were created in Excel for visual representation of key insights and report presentation.

### Steps and Methodology

### Data Preparation:
1. Import the Customer Data into Excel,
2. Clean the Customer Data by checking for any missing values or irregularities. 
3. Remove duplicates

### Visual Analysis and Inferences
![image](https://github.com/user-attachments/assets/68404ade-5a5f-426b-b57c-f2d5828c88c1)
![image](https://github.com/user-attachments/assets/f0b950b7-9ba2-4012-b52d-58c2da5012cd)
![image](https://github.com/user-attachments/assets/1cc8a978-e371-4dd8-979d-283706ccb70b)

### SQL Analysis of Customer Subscription Behaviour
Analyzing the customer subscription pattern using SQL to generate insights into subscription type, subscription cancelled or renewed, 
revenue, customer behavior, subscription duration and regional performance. The analysis is aimed at helping stakeholders make 
informed decisions based on customers key trends in cancellations and renewals.

The following were retrieved by SQL Query after :
![image](https://github.com/user-attachments/assets/1bb1d9bc-4c36-4fc8-af81-de1ed659a234)
1.	Retrieve the total number of customers from each region.
![image](https://github.com/user-attachments/assets/3599c544-ef85-4e1b-a117-ed5128b2c1f2)

2.	Find the most popular subscription type by the number of customers.
![image](https://github.com/user-attachments/assets/24c836f4-7ce5-4a7b-a3d8-b3183e8f47e9)

3.	Find customers who canceled their subscription within 6 months. 
![image](https://github.com/user-attachments/assets/78d21742-0ce8-4fc4-86a9-8215f2cc4f2e)
No Customer canceled Subscription within 6 months

4.	Calculate the average subscription duration for all customers. 
![image](https://github.com/user-attachments/assets/d1e0b524-6be4-4dd5-bc8e-569cd5347313)
The Average subscription duration for all Customers is 1year

5.	Find customers with subscriptions longer than 12 months. 
![image](https://github.com/user-attachments/assets/f1d0d963-4db9-4279-b5e8-4aee682a4c0b)
No Customer has subscription duration longer than 12months

6.	Calculate total revenue by subscription type.
![image](https://github.com/user-attachments/assets/fd8df1ae-e544-446a-a377-d425043ff51e)


7.	Find the top 3 regions by subscription cancellations. 
![image](https://github.com/user-attachments/assets/b8fb3717-55bf-4d5f-b4aa-526da0c5f380)


8.	Find the total number of active and canceled subscriptions.
![image](https://github.com/user-attachments/assets/f0c76622-db24-4b31-b72f-67a5c10b0b14)




















