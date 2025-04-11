🧠 Diabetes Prediction Model
🎯 Objective

Build a machine learning model to predict the likelihood of Diabetes based on medical parameters such as glucose level, BMI, blood pressure, and more. The goal is to assist healthcare professionals with early diagnosis and preventive care.
📂 Dataset

    Dataset Used: PIMA Indians Diabetes Dataset

    Upload Method: Upload the CSV file manually via Google Colab using files.upload() prompt.

⚙️ Technologies & Libraries

    Python (Google Colab)

    Pandas, NumPy

    Scikit-learn

    Seaborn & Matplotlib

    Gradient Boosting Classifier

    Support Vector Machine (SVM)

    ROC-AUC, F1 Score

🔍 Workflow
✅ Step 1: Upload Dataset

Manually upload the diabetes.csv file using the file uploader in Google Colab.
✅ Step 2: Data Preprocessing

    Check for missing values

    Separate features (X) and target (y)

    Scale the features using StandardScaler to normalize values

✅ Step 3: Exploratory Data Analysis (EDA)

    Visualize the distribution of diabetic vs. non-diabetic patients

    Analyze correlations between medical features using a heatmap

✅ Step 4: Model Building

Two models are trained to predict diabetes:

    Gradient Boosting Classifier

    Support Vector Machine (SVM)

Both are trained on 80% of the data and evaluated on the remaining 20%.
✅ Step 5: Model Evaluation

    Generate classification reports for both models

    Calculate and plot ROC-AUC curves to visualize performance

    Compare models using metrics like F1 Score and ROC-AUC

✅ Step 6: Feature Importance

    Use the Gradient Boosting model to determine which medical features contribute most to predicting diabetes

    Visualize feature importance in a bar chart for easy interpretation

📊 Visualizations

    📈 Bar plot of diabetes cases vs. non-diabetes cases

    🔥 Correlation heatmap of all features

    🎯 ROC Curve comparison between models

    🧮 Feature importance chart to provide medical insights

📌 Outcome

    A working machine learning pipeline for diabetes prediction

    Multiple trained models with performance comparison

    Actionable insights on which features most influence diabetes detection

🏁 How to Run

    Open the notebook in Google Colab

    Upload the diabetes.csv dataset when prompted

    Run the code step-by-step

    Review charts, evaluation scores, and prediction insights

✅ Ideal For

    Medical practitioners and data scientists aiming for early diabetes detection

    Students working on healthcare machine learning projects

    Anyone interested in building predictive models using real-world health data
