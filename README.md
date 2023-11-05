# Travel_Insurance

Predictive Modeling for Travel Insurance Claims

Objective:

The objective of this assignment was to perform Exploratory Data Analysis (EDA) and feature engineering on the given travel insurance dataset, followed by creating a binary classification model to predict the "Claim" column, which represents whether a claim was made (Yes/No).

1. Exploratory Data Analysis (EDA):

●	Data Loading: The dataset was loaded into a pandas DataFrame for analysis.

●	Data Overview: The dataset contains various columns, including 'Agency', 'Agency Type', 'Distribution Channel', 'Product Name', 'Claim', 'Duration', 'Destination', 'Net Sales', 'Commision (in value)', 'Gender', and 'Age'.

●	Handling Missing Values: The 'Gender' column, having a significant number of missing values, was dropped from the dataset.

●	Data Visualization: Utilized various visualization techniques like bar charts, pie charts, histograms, and heatmaps to understand the distribution and relationships among different features.

Key Observations: Identified popular destinations, analyzed age distribution, and visualized claim requests based on destinations, agencies, and insurance plans.

2. Feature Engineering:

●	Label Encoding: Categorical variables like 'Agency', 'Agency Type', 'Distribution Channel', 'Product Name', 'Claim', and 'Destination' were label encoded for model compatibility.

●	Correlation Analysis: Conducted correlation analysis to identify relationships between variables, helping in understanding feature importance.

3. Predictive Model Building:

●	Handling Imbalanced Classes: Addressed the imbalanced class issue using Synthetic Minority Over-sampling Technique (SMOTE) to create synthetic samples of the minority class, balancing the dataset.

●	Data Preprocessing: Split the dataset into features (X) and target variable (y). Scaled features using Min-Max Scaling.

●	Model Selection: Utilized Random Forest Classifier due to its ability to handle complex relationships and feature importance calculation.

●	Model Training: Trained the Random Forest Classifier on the preprocessed data.

●	Model Evaluation: Evaluated the model's performance using accuracy and recall scores, crucial metrics for imbalanced classification problems.

4. Conclusion:

The predictive model successfully addressed the assignment objectives, including performing EDA, feature engineering, and creating a predictive model using categorical variables. The Random Forest Classifier demonstrated satisfactory performance in predicting travel insurance claims.
