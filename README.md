# EXPLORING_and_VISUALIZING_a_SIMPLE_IRIS_DATASET
### OBJECTIVE

The objective of this task is to explore and visualize the Iris dataset to understand the relationship and distribution of different flower features across species.

### APPROACH

The Iris dataset was loaded using Seaborn and its structure was examined. Data visualization techniques such as scatter plots, histograms, and boxplots were used to analyze feature relationships and distributions. Species were encoded numerically for better visualization.

### RESULTS_and_INSIGHTS
The visualizations show clear differences between Iris species. Petal length and petal width provide strong separation among species, while sepal features show partial overlap. These insights highlight which features are most useful for distinguishing Iris flower types.


# CREDIT_RISK_PREDICTION
### OBJECTIVE

The objective of this project is to predict whether a loan applicant will repay the loan or default, helping banks reduce financial risk and improve loan approval decisions.

### APPROACH

The dataset was cleaned by removing unnecessary columns and handling missing values. Categorical variables were encoded into numerical form. After data visualization and preprocessing, a Logistic Regression model was trained using a train-test split, and its performance was evaluated.

### RESULTS_and_INSIGHTS

The model achieved an accuracy of 78.8%, showing good predictive capability. Key factors such as credit history, income, and loan amount significantly influence loan repayment decisions. This model can support automated credit risk assessment in banking systems.



# CUSTOMER_CHURN_PREDICTION
### OBJECTIVE:
Predict customer churn in a bank using the Churn Modelling Dataset to help identify at-risk customers and reduce revenue loss.

### APPROACH:

Loaded and explored the dataset.

Dropped irrelevant columns (RowNumber, CustomerId, Surname).

Encoded categorical variables (Gender with Label Encoding, Geography with One-Hot Encoding).

Split data into training (80%) and testing (20%) sets.

Trained a Random Forest Classifier to predict churn.

Evaluated model performance using accuracy and classification metrics.

Analyzed feature importance to understand which factors influence churn the most.

### RESULTS_and_INSIGHTS:

Model achieved 86.6% accuracy.

Customers who left (churned) were harder to predict than those who stayed (recall for churn = 0.46).

Most important features influencing churn: Age, Estimated Salary, Credit Score, Balance, Num of Products.

Insights suggest that age, financial status, and product usage significantly impact customer retention.
