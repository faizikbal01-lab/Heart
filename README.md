# Heart
Pulse of Prevention: Cardiovascular Risk Analytics. An end-to-end Python project utilizing clinical data to identify heart disease predictors. Features statistical correlation of 13 variables (cholesterol, ECG, chest pain), predictive modeling via Logistic Regression, and medical data visualization to enhance early diagnosis and patient care.
Patient Demographics: Calculates the distribution of male and female patients in the dataset.
Risk Factor Combinations: Identifies the most common combinations of clinical features (chest pain type, fasting blood sugar, exercise-induced angina, etc.) for patients diagnosed with heart disease.
Descriptive Statistics: Provides a statistical summary (mean, max, heart rate, blood pressure, etc.) comparing patients with heart disease against those without.
Statistical & Correlation Analysis
Feature Correlation: Ranks all clinical features by their correlation with the target (presence of heart disease) to identify the most significant predictors.
Hypothesis Testing: Conducts an Independent Samples T-test to determine if there is a statistically significant difference in resting blood pressure (trestbps) between male and female patients.
Correlation Benchmarks: Specifically measures the correlation between age and cholesterol levels
Trend Analysis: Uses line plots to visualize the relationship between Thalassemia, Age, and the presence of heart disease.
Distribution Plots: * Stacked bar charts showing ST Slope by chest pain type.
Stacked bar charts showing the relationship between Thalassemia, Number of Major Vessels, and Fasting Blood Sugar relative to the target diagnosis.
Relationship Mapping: Uses Pair Plots to visualize interactions between continuous variables like age, cholesterol, and maximum heart rate (thalach).
 Machine Learning & Predictive Modeling
Data Preprocessing:
Splits the data into training and testing sets (80/20 ratio).
Feature Scaling: Applies StandardScaler to numerical features (age, blood pressure, etc.) to normalize the data for the model.
Model Training: Trains a Logistic Regression model (using the liblinear solver) to predict the likelihood of heart disease
Performance Evaluation:
Calculates Model Accuracy.

Generates a Classification Report (Precision, Recall, F1-Score).

Visualizes a Confusion Matrix to see the true positive vs. false positive predictions.
