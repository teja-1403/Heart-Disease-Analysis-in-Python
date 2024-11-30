# Heart-Disease-Analysis-in-Python

**Problem:**

In this project, we delve into a dataset encapsulating various health metrics from heart patients, including age, blood pressure, heart rate, and more. Our goal is to develop a predictive model capable of accurately identifying individuals with heart disease. Given the grave implications of missing a positive diagnosis, our primary emphasis is on ensuring that the model identifies all potential patients, making recall for the positive class a crucial metric.

**Objectives:**

- Explore the Dataset: Uncover patterns, distributions, and relationships within the data.
- Conduct Extensive Exploratory Data Analysis (EDA): Dive deep into bivariate relationships against the target.
- Preprocessing Steps:
  - Remove irrelevant features
  - Address missing values
  - Treat outliers
  - Encode categorical variables
  - Transform skewed features to achieve normal-like distributions
- Model Building:
  - Establish pipelines for models that require scaling
  - Implement and tune classification models including SVM, Decision Trees, and Random Forest, XGBoost
  - Emphasize achieving high recall for class 1, ensuring comprehensive identification of heart patients
- Evaluate and Compare Model Performance: Utilize precision, recall, and F1-score to gauge models' effectiveness.

**Result:**

📍 SVM (Support Vector Machine) Model shows the highest recall (0.97) for detecting heart disease, indicating that it performs well in identifying patients with the disease. Despite the high recall, the model maintains a balanced precision, ensuring that false positives are not excessively high.

📍 Random Forest outperforms Decision Tree in terms of overall accuracy and recall, providing more robust predictions. It’s more effective at detecting heart disease with less sensitivity to overfitting, making it a more reliable model for this problem.

📍 XGBoost also performs well, showing a strong recall similar to Random Forest, but its slight improvement in precision and recall makes it a more competitive model for predicting heart disease.

📍 Decision Tree has lower performance compared to the other models, with both accuracy and recall lagging behind Random Forest and SVM. It seems more prone to overfitting, especially when hyperparameters aren't finely tuned.

📍 Box-Cox Transformation significantly improved the distribution of skewed features, such as oldpeak, chol, and trestbps, enhancing the model's ability to detect meaningful patterns in the data.


# 
Languages used : 

![python-logo-only](https://github.com/user-attachments/assets/a78aa447-fe92-4892-aaed-4dd6ea761795)

# 
📣 Feel free to have a look at all the files in this repository !🤗

❎ In case you find issues in any of my Repositories, you can Hit Me Up [here](https://github.com/issues)! 👈
