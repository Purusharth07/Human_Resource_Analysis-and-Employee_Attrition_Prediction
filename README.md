# Human Resource Analysis and Employee Attrition Prediction using Python

#### Attrition Rate: A common attrition rate definition refers to employee or staff turnover, but in a broader sense, attrition rate is a calculation of the number of individuals or items that vacate or move out of a larger, collective group over a specified time frame. Attrition rate is also commonly referred to as churn rate. 

#### Attrition in business can mean the reduction in staff and employees in a company through normal means, such as retirement and resignation, the loss of customers or clients to old age or growing out of the company's target demographic.

## Step 1 -Define the Goal

#### The following questions are among the ones every Company suffering with high Employee Attrition Rate would like to be answered:

   #####       1. What proportion of our staff are leaving?
   #####       2. Where is it occurring?
   #####       3. How does Age and Length of Service affect termination?
   #####       4. What, if anything, else contributes to it?
   #####       5. Can we predict future terminations?
   #####       6. If so, how well can we predict?
  
  
## Step 2 – Collect and Manage the Data

#### The information contained in the readily available dataset is as follows: 
#### There are 35 different Attributes, and 1470 instances.
| Attributes | Attributes |
| ---------- | ---------- |
| 1. Age     | 19. Monthly Income |  
| 2.	Attrition | 20. Monthly Rate | 
| 3.	Business Travel | 21. Number of Companies Worked |
| 4.	Daily Rate      | 22. Over18   
| 5.	Department      | 23. Over Time    
| 6.	Distance from Home |  24. Percent Salary Hike 
| 7.	Education          |  25. Performance Rating    
| 8.	Education Field    |  26. Relationship Satisfaction   
| 9.	Employee Count     |  27. Standard Hours 
| 10. Employee Number    |  28. Stock Option Level  
| 11. Environment Satisfaction |  29. Total Working Years  
| 12. Gender             |  30. Training Times Last Year
| 13. Hourly Rate        |  31. Work Life Balance  
| 14. Job Involvement    |  32. Years at Company  
| 15. Job Level          |  33. Years in Current Role  
| 16. Job Role           |  34. Years since Last Promotion
| 17. Job Satisfaction   |  35. Years with Current Manager 
| 18. Marital Status     |          
 


### Step 3 – Data Exploration 

#### Stop and Think about the Data:
#### •	What features affect our target variable the most (Attrition)?
#### •	What features have strong correlations with each other?
#### •	Can we do a more in depth examination of these features?

### Correlation Matrix and Heat Map
#### Moderate/Highly Positively Correlated Features


#### Moderate/Highly Negatively Correlated Features


#### Summary:
From the heatmap, there is strong positive(+) correlation between Total working Years, Job Level, Monthly Income, Years with Current Manager, and Years in Current Role. Which could mean that the employees who have worked for more number of Total Years and are at higher Job Level are having high Monthly Income.

For the negative(-) relationships, Attrition and job level + total working years are correlated. I'm assuming that people tend to leave a company more when they are not been promoted and hence are working in current role for longer period of time.Moreover, people at higher job level and with more number of total working years are expected to leave the company.

