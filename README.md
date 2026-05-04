#Customer Churn Prediction Analysis
A data analysis and machine learning project that builds and compares classification models to identify high-risk customers likely to cancel their service.


# What it does
  1. **Analyze Data:** (EDA) to find patterns. For example, it identified that churn spikes significantly between the 23rd         and 25th month.
  2. **Preprocessing:** Cleans the data by dropping noisy features like CustomerID and Last Interaction, then converts             categorical data (Gender, Subscription Type) into a format models can understand.
  3. **Model Training:** Builds and compares three specific models: AdaBoost, Random Forest, and Logistic Regression.
  4. **Evaluate:** Determines which algorithm is the most accurate at predicting whether a customer will stay or leave.


# Tools I used
  1. **Pandas & Numpy:** For data manipulation and feature engineering.
  2. **Matplotlib & Seaborn:** To create visual insights like churn distribution and risk heatmaps.
  3. **Scikit-Learn:** To split the data (80/20 train-test split) and train the machine learning classifiers.


#Files in this project
  1. **Churn Prediction.ipynb:** The main Jupyter Notebook containing the code and visualizations.
  2. **customer_churn_dataset-testing-master.csv:** The raw dataset containing customer info.

# How to run it
1. Install the libraries we need by running:
   ```bash
   pip install streamlit pandas scikit-learn requests
