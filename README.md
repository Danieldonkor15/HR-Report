# HR Analysis


### Project Overview

This data analysis projects aims to provide insights into poeple that works in this firm. By analyzing the various aspects of the HR data, we intend to find salaries for diffrent race group or gender, and weather there's a wage gap between the genders, and make data driven recomendations.


### Data Sources 
HR Dataset: I used Kaggle to find this dataset, which contained detailed information about the employees working for this firm.

### Tools

- MySQL-Data Cleaning & Analysis
- PowerBI-Data Visualization

### Data Cleaning /Preparation
For the data Preparation phase, I performed the following task:
1. Data loading and inspection
2. Data Cleaning and formatting
   
   Incude some intresting code
   ```SQL
   UPDATE HR_DATASET SET AGE =timestampdiff(YEAR,DOB,CURDATE());
   ```
## Questions
1. What is the gender breakdown of employees in the company?
2. WHAT IS THE RACE/ETHNICITY breakdown of the employee in company?
3. What is the age distribution of employees in the company?
4. What is the distribution of married poeple and single poeple?
5. What is the aveage leanght of employment for employee who have been terminated?
6. How does the gender distributions vary across deparments and job titles?
7. Which deparment has the highest tuenover raate?
8. What is the distibution of employee across the locations by city and state?
9. What is Average salaries for each department?
10. What is the Average salary?
11. what is the Average salaries between both genders?
12. whta is the Average salaries for each gender in their departments?

    ## Results/Findings
    - There are more female employees but not by huge amount.
    - The average leanght of employment for terminated employees is 3 years.
    - The youngest employee is 31 years old and the oldest is 53 years old.
    - Across the 3 age groups that were created(30-40,41-48,49-53). A large number of employees falls between 30-40.
    - White race is the most dominant race while Hispanic are the least dominant.
    - A large number of employees come from the state of massachusetts.
    - The average salary is 69000.
    - The average salary between genders Men are earning more than women.
  ## Limitations
   - Some records had negative ages and these were excluded.
   - There wasn't anything on hours worked or years of experiences so I wasn't able to determine why men were erning more than women.

## Recommendation 
   I recommed the following actions:
   - Employ more poeple from minorites back ground espercially Hispanic.
   - Employ more men in order to balance both genders
   - Employ more younger poeple as the youngest is 31 years old.
   - Make the salaries between genders in their department more even, depending or hourse worked and level of experience.
