# Customer-Churn-Analysis-using-Decision-Tree

This project predicts telecom customer churn by analyzing features like contract renewal, data usage, and service calls. Steps include EDA, preprocessing, decision tree modeling, pruning, and Grid Search optimization. Visualizations and metrics included.

The main goal is to identify factors contributing to customer churn and build a predictive model to improve customer retention strategies.



**Dataset Features**

Churn (Target): Indicates if a customer has churned (1) or not (0).

AccountWeeks: Total weeks the customer has been with the company.

ContractRenewal: Whether the contract was recently renewed (1 = Yes, 0 = No).

DataPlan: Indicates subscription to a data plan (1 = Yes, 0 = No).

DataUsage: Amount of data (GB) used during the billing period.

CustServCalls: Number of customer service calls.

DayMins & DayCalls: Minutes and calls during daytime hours.

MonthlyCharge: Average monthly bill.

OverageFee: Charges for exceeding usage limits.

RoamMins: Minutes spent on roaming calls.





**Steps taken**

Data Preprocessing:

Checked for nulls, duplicates, and outliers.

Applied Winsorization to handle outliers.



Exploratory Data Analysis:

Visualized churn trends and feature distributions.

Identified characteristics of churned customers.



Model Building:

Built and visualized a Decision Tree.

Improved model performance through pruning.



Evaluation:

Assessed model accuracy, sensitivity, and specificity.

Achieved high training and testing accuracy.



Optimization:

Applied Grid Search for hyperparameter tuning.

  
Results:

Training Accuracy: ~79.5% after pruning.

Testing Accuracy: ~86.1%.



Insights: Customers with no data plans, frequent customer service calls, and high overage fees are more likely to churn.





**Install required libraries using:**

pip install -r requirements.txt





**Files Included**

Customer Churn Analysis using Decision Tree.ipynb: Jupyter notebook with the complete analysis.

telecom_churn.csv: Dataset.

requirements.txt: List of required Python libraries.

Decision Tree.pkl: Exported model for predictions.



**Tools & Libraries**

Libraries: Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn, Plotly.

Techniques Used: Data preprocessing, Decision Tree, Grid Search, Winsorization.





Author

Reetika Singh
