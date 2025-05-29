# Wine-Quality-Prediction
![image](https://github.com/user-attachments/assets/46e5b67e-a801-41b5-bfdb-a0647396d222)

**Description:**
Predicting the quality of wine based on its physicochemical properties offers valuable insights for winemakers, distributors, and quality assurance teams. This notebook applies machine learning techniques to determine wine quality ratings using a dataset containing various chemical metrics. By analyzing the relationships between these features and the quality score, we can build a model that helps in forecasting product standards and guiding production.

This analysis helps identify which properties most strongly influence wine quality—such as alcohol, acidity, and residual sugar—enabling data-driven improvements in wine formulation and assessment.

This data frame contains the following columns:

Input variables (based on physicochemical tests):\
* fixed acidity

* volatile acidity

* citric acid

* residual sugar

* chlorides

* free sulfur dioxide

* total sulfur dioxide

* density

* pH

* sulphates

* alcohol

Output variable (based on sensory data):
* quality (score between 0 and 10)

**Objective**

* Explore relationships between chemical properties and wine quality

* Visualize data trends and distributions

* Build a predictive model using classification algorithms

* Evaluate model performance and interpret results

![image](https://github.com/user-attachments/assets/c11608eb-00ee-4be4-bb91-f1177f4faffe)

**📌 Key Steps & Workflow**

1. Data Preprocessing

* Checked for missing/null values

* Scaled and normalized features if necessary

2. Exploratory Data Analysis (EDA)

* Used boxplots, histograms, and heatmaps to uncover patterns

* Visualized class distribution of wine quality

3. Feature Importance & Correlation

* Analyzed which features are most correlated with wine quality

* Identified alcohol, volatile acidity, and sulphates as key predictors

4. Model Building

* Implemented classification algorithms (e.g., Random Forest, Logistic Regression)

* Split data into training and testing sets

* Evaluated accuracy, confusion matrix, and classification report

5. Insights

* Alcohol and sulphates were positively correlated with higher quality

* Volatile acidity showed a negative impact on wine quality

* Model performed well in distinguishing mid-to-high quality wines

**🚀 How to Run the Notebook**

* Clone the repository or download the notebook

Install required Python packages:

* pip install pandas numpy matplotlib seaborn scikit-learn

* Launch Jupyter Notebook and open wine_quality.ipynb

* Execute each cell sequentially to explore data, train models, and view results
