📊 Carbon Emissions Prediction
Domain: Machine Learning | Environmental Analytics | Automobile Industry

🔍 Project Description:
Carbon Emissions Prediction involves forecasting CO₂ emissions using machine learning models to support sustainability efforts and reduce climate change impacts.
This project specifically focuses on predicting the amount of CO₂ emitted by cars based on various engine and technical features.

🎯 Business Objective:
To develop a predictive model that estimates vehicle CO₂ emissions using various automobile specifications, assisting manufacturers and regulators in making data-driven, eco-conscious decisions.

🧰 Tools & Technologies Used:
Programming Language: Python

Libraries: NumPy, Pandas, Matplotlib, Seaborn, SciPy, scikit-learn

Framework: Streamlit (for deploying the model as a web application)

ML Models Implemented:

Linear Regression

Random Forest

K-Nearest Neighbors (KNN)

Support Vector Regression (SVR)

Environment: Jupyter Notebook, Streamlit

Deployment: Cloud-hosted app via Streamlit

⚙️ Installation Instructions:
Install Python from python.org

Install project dependencies by running:

bash
Copy
Edit
pip install -r requirements.txt
▶️ Running the Project Locally:
To launch the application, use the following Streamlit command:

bash
Copy
Edit
streamlit run app.py
✅ Milestones Achieved:
Week 1 – Data Cleaning & Preparation
Loaded the original multi-sheet Excel dataset using pandas.read_excel() (without converting to CSV)

Cleaned and prepared the dataset for model training

Tools used: Pandas, Jupyter Notebook

Week 2 – Data Exploration & Visualization
Imported cleaned dataset (data_clean.csv)

Performed feature engineering and pattern recognition

Created various visualizations:

Correlation matrix heatmap

Scatterplots for feature relationships

Histograms to explore distributions

Visual outlier detection

Identified dependencies and emission trends from the data

Week 3 – Model Building & Evaluation
Summarized the project goals and clarified dataset source

Imported necessary libraries and ensured reproducibility

Provided a clear overview of data columns and feature abbreviations

Formulated a hypothesis and selected relevant variables

Split data into training and test sets

Applied Recursive Feature Elimination (RFE) with cross-validation for optimal feature selection

Conducted hyperparameter tuning on Random Forest using Grid Search

Trained and evaluated models using cross-validation

Validated the model’s performance on unseen test data

Documented conclusions and prepared the model for deployment


🛠 Tools Summary:
Data Handling: Pandas, NumPy

Visualization: Matplotlib, Seaborn

Modeling: scikit-learn

Notebook & UI: Jupyter Notebook, Streamlit
