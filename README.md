# Mini-project IV

### [Assignment](assignment.md)

## Project/Goals
The goal of the project was to predict loan eligibilty based on customer details.  

## Hypothesis
Without having much understanding of loan eligibility, I would thinj that income might have an effect on whether or not someone would be able to repay a loan and therefore be approved for a loan. 

## EDA 
7 columns had missing values. Most categorical variables had 2 options execpt dependents and property area. Applicant income has a right skew - which is also seen when you break it into graduates and non-graduates. Loan amount has a bit more of a normal distribution with some outliers. 


## Process
(fill in what you did during EDA, cleaning, feature engineering, modeling, deployment, testing)
    1. In the pipeline numerical features NaN's were replaced with a     mean and scaled using standard scaler. The categorical features NaN's were replaced with the mode, and one-hot-encoded. 
    2. The pipeline included logistic regression and SVC and select K-best with 3-7 features. 
    3. pickle was used to save the model and the the model columns  

## Results/Demo
The final model had a test accuracy of 0.813, which was achieved using Logistic Regression and 3 features. 

## Challanges 
I wasn't able to get the deployment part of the assignment working. 

## Future Goals
In the future I would like to look more into features and if there were other ways to engineer this information. I would also try different types of models. 