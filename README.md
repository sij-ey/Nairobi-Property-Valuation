🏠 Nairobi House Price Prediction (2026 Edition)
An end-to-end Machine Learning solution designed to bring transparency to the Nairobi real estate market. This project uses XGBoost to predict property values based on location, size, and amenities, achieving an R-Squared score of 0.88.

🚀 Overview
Predicting property values in Nairobi is challenging due to "prestige premiums" and rapid infrastructure development. This tool provides instant, data-driven valuations to help buyers and sellers avoid overpricing or undervaluation.

Key Features
Predictive Modeling: Uses Gradient Boosting (XGBoost) with log-transformation for high accuracy across both budget and luxury segments.

Interactive Dashboard: A Streamlit web application for real-time price estimation.

Data Insights: Visualizations highlighting the impact of gated communities and neighborhood location on price.

🛠️ Tech Stack
Language: Python 3.10+

Machine Learning: XGBoost, Scikit-Learn

Data Analysis: Pandas, NumPy

Visualization: Matplotlib, Seaborn, Plotly

Deployment: Streamlit, Joblib

📂 Project Structure
houses.py: Synthetic data generation script (tailored for the 2026 Nairobi market).

train.py: The ML pipeline, including feature engineering and model serialization.

visualizations.py: Scripts for generating exploratory data analysis (EDA) plots.

app.py: The Streamlit web interface code.

house_model.pkl: The trained and saved model weights.

Nairobi_houses.csv: The primary dataset.

🏃‍♂️ How to Run
1. Prerequisites
Ensure you have the following libraries installed:

Bash
pip install pandas numpy scikit-learn xgboost matplotlib seaborn plotly streamlit joblib
2. Training the Model
If you want to re-train the model or update the weights:

Bash
python train.py
3. Launching the Web App
To view the interactive valuer:

Bash
streamlit run app.py
📈 Model Performance
Based on the final evaluation:

R-Squared: 0.88 (The model explains 88% of price variance).

MAE: KSh 1,850,000 (Average error of ~1.8M KSh).

Key Insight: Gated communities in areas like Karen and Runda add a statistically significant premium of ~KSh 3,000,000.
