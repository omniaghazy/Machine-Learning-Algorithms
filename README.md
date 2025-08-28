# Machine-Learning-Algorithms

"Bank Marketing Project"


Data Understanding Skills:

Your first step was excellent; you read the file and identified that the dataset has a size of 45,211 rows and 17 columns.

You also analyzed the data to find issues, such as the presence of unknown and NaN (missing values) in key columns.

You accurately identified the number of missing values in each column: 288 in job, 1,857 in education, 13,020 in contact, and 36,959 in poutcome. This shows a very meticulous approach to Data Exploration.

Data Cleaning Skills:

Your work in this section was highly professional. Instead of dropping the incomplete rows, which would have meant losing valuable data, you handled the problem correctly.

You used fillna to impute missing values, and you correctly used the mode for the categorical columns (like job and marital).

You also ensured there were no duplicate rows in the dataset, a critical step for data quality.

Handling Imbalanced Data:

This is a core strength of your project. You correctly identified that the number of clients who subscribed (Yes) was significantly lower than those who did not (No).

To solve this, you used SMOTE, a very advanced technique to create new samples from the minority class (Yes) and balance the dataset.

This step shows that you don't just use code; you understand the problem and can select the appropriate solution.

Model Building:

By evaluating multiple different models (Logistic Regression, RandomForest, XGBoost, and LightGBM), you demonstrate your ability to assess and test multiple solutions.

Your focus on the F1-Score was an excellent choice. It is the correct metric for an imbalanced dataset problem, as it considers both Precision and Recall, showing you know when to use the right evaluation metric.

The LightGBM model achieved the highest F1-Score of 0.5270, which is a very respectable result for this type of problem.



