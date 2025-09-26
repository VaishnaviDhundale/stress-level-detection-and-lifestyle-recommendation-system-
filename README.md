**Stress Level Detection using Machine Learning
Overview**

This project predicts stress levels (Low, Medium, High) based on lifestyle factors such as sleep hours, screen time, work hours, caffeine intake, exercise hours, and heart rate.
It uses a Random Forest Classifier for prediction and provides an interactive Streamlit dashboard for real-time monitoring.

**Tech Stack**

Programming Language: Python
Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Joblib
GUI Framework: Streamlit
Development Tools: VS Code, Jupyter Notebook
Deployment: Streamlit Community Cloud

**Dataset**

The dataset includes the following features:
Sleep Hours
Screen Time Hours
Work Hours
Caffeine Intake (mg)
Exercise Hours
Heart Rate (BPM)
Stress Category (Low, Medium, High – generated labels)
Dataset is saved as:
stress_dataset.csv

**Installation & Setup**

Clone this repository:
git clone https://github.com/YourUsername/stress-level-detection.git
cd stress-level-detection

Install dependencies:

pip install -r requirements.txt

Run the Streamlit app:

streamlit run app.py

**Flow of the Project**

Input Data (Sleep, Screen Time, Work, Caffeine, Exercise, Heart Rate) →
Data Preprocessing (Cleaning & Splitting) →
Model Training (Random Forest Classifier) →
Prediction (Low / Medium / High Stress) →
Interactive Dashboard with Streamlit

**Deployment**

The project is deployed on Streamlit Community Cloud.
👉 Click here to try the app
 (replace with your actual link)

**Expected Outcome**

Predict stress levels accurately using lifestyle data.
Visualize results with charts and interactive GUI.
Provide insights into lifestyle factors that affect stress.

**Future Enhancements**

Integration with wearable devices (Fitbit, Apple Watch, etc.).
Collecting real-world survey data for better accuracy.
Deploying as a mobile/web health application.

📸 Screenshots

(Add screenshots of your Streamlit app once deployed here)

Author: Vaishnavi Dhundale
