# Bank-Customer-Churn-Prediction

I have completed a project on predicting bank customer churn using a dataset obtained from Kaggle [https://www.kaggle.com/datasets/radheshyamkollipara/bank-customer-churn]. 
The dataset comprises information from 10,000 bank customers, with 7,964 customers classified as unchurned and 2,038 as churned. It encompasses 12 features, providing a 
comprehensive understanding of customer behavior and attributes. This project aimed to analyze factors contributing to customer churn and develop predictive models to assist banks in identifying and retaining potentially at-risk customers. The findings and insights derived from this project contribute to the ongoing efforts in enhancing customer retention strategies within the banking sector.

FEATURES :

RowNumber—corresponds to the record (row) number and has no effect on the output.

CustomerId—contains random values and has no effect on customer leaving the bank.

Surname—the surname of a customer has no impact on their decision to leave the bank.

CreditScore—can have an effect on customer churn, since a customer with a higher credit score is less likely to leave the bank.

Geography—a customer’s location can affect their decision to leave the bank.

Gender—it’s interesting to explore whether gender plays a role in a customer leaving the bank.

Age—this is certainly relevant, since older customers are less likely to leave their bank than younger ones.

Tenure—refers to the number of years that the customer has been a client of the bank. Normally, older clients are more loyal and less likely to leave a bank.

Balance—also a very good indicator of customer churn, as people with a higher balance in their accounts are less likely to leave the bank compared to those with lower balances.

NumOfProducts—refers to the number of products that a customer has purchased through the bank.

HasCrCard—denotes whether or not a customer has a credit card. This column is also relevant, since people with a credit card are less likely to leave the bank.

IsActiveMember—active customers are less likely to leave the bank.

EstimatedSalary—as with balance, people with lower salaries are more likely to leave the bank compared to those with higher salaries.

Exited—whether or not the customer left the bank.

In this dataset, I addressed various preprocessing tasks to ensure its integrity and suitability for analysis. Firstly, I managed duplicate entries, ensuring the dataset's consistency and reliability. Secondly, I employed encoding techniques using pandas' 'get_dummies' function to convert categorical variables into numerical representations, facilitating subsequent analysis. Additionally, I handled missing data, ensuring minimal impact on the overall dataset quality. Furthermore, I conducted thorough data visualizations to gain insights into the dataset's characteristics, distribution, and potential relationships among variables. These preprocessing steps were instrumental in preparing the dataset for subsequent modeling and analysis, laying a solid foundation for robust and accurate predictive modeling of bank customer churn.

In the data modeling phase, I employed four distinct machine learning algorithms: Decision Tree, Logistic Regression, Support Vector Machine (SVM), and Random Forest. After rigorous evaluation and comparison, Random Forest emerged as the most effective model, achieving an impressive accuracy rate of 85%. Consequently, I selected Random Forest as the primary machine learning model for predicting bank customer churn. This decision was based on its superior performance in accurately classifying customer churn, highlighting its potential as a reliable predictive tool in real-world banking applications.

