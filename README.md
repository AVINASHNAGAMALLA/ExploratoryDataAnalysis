This project focuses on analyzing telecom customer data to understand factors that drive customer churn and to build predictive models for classification.


Data Preprocessing:

Removed irrelevant identifiers (year, customer_id, phone_no).

Handled missing values (mode for categorical, mean for numerical).

Encoded categorical features using LabelEncoder.

Scaled numerical variables using StandardScaler.

Exploratory Data Analysis (EDA):

Univariate & bivariate analysis with bar charts, histograms, and boxplots.

Correlation analysis to identify influential features.

Outlier detection (kept as <3% of data).

Insights: churn influenced by customer support calls, watch time, and mail subscription status.

Model Development:

Implemented Logistic Regression, Decision Tree, and Random Forest.

Split data into train (80%) and test (20%).

Model Evaluation:

Compared using Accuracy, Precision, Recall, and Confusion Matrices.

Random Forest performed best with:

Accuracy: 90%

Precision: 0.60

Recall: 0.45

🔹 Tech Stack

Python: pandas, numpy, matplotlib, seaborn, scikit-learn

Machine Learning Models: Logistic Regression, Decision Tree, Random Forest

I'm writing this line here to experiment git commands


