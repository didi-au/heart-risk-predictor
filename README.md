🫀 Heart Disease Risk Level Predictor

A simple machine learning + Flask web application that predicts a patient’s heart disease risk level based on basic health details.

🚀 Features

Collects patient details (age, gender, cholesterol, smoking, diabetes, etc.) via a clean web form

Uses a trained regression model (scikit-learn) for prediction

Displays risk score and risk level (Low / Medium / High) in real-time

Built with Flask, HTML templates, Bootstrap

Easy to run locally

📂 Project Structure
heart-risk-predictor/
├─ heart_risk_level_predictor.py     # Main Flask app
├─ heart_risk_prediction_regression_model.sav  # Trained ML model
├─ templates/
│   ├─ patient_details.html           # Input form
│   └─ patient_results.html           # Prediction output
├─ static/                           # Optional CSS/JS/images
├─ cardio_dataset.csv                # Dataset used for training
└─ requirements.txt                   # Python dependencies

⚙️ Installation & Running Locally
1) Clone the repo
git clone https://github.com/didi-au/heart-risk-predictor.git
cd heart-risk-predictor

2) Install dependencies

It’s recommended to use a virtual environment. Then run:

pip install -r requirements.txt

3) Start the Flask app
python heart_risk_level_predictor.py

4) Open in browser

Visit:

http://127.0.0.1:5000/

📊 Example Workflow

Enter details (Age, Gender, Cholesterol, Smoking status, etc.)

Submit the form

The app loads the saved regression model and predicts risk

Results are displayed as a numerical score + categorical level

🛠️ Technologies Used

Python 3

Flask – Web framework

Scikit-learn – Machine learning

Joblib – Model serialization

Bootstrap – Frontend styling

🌟 Future Improvements

Deploy to Heroku / Render / Railway for live demo

Add input validation and charts for results

Try more advanced models (Logistic Regression, Random Forest, XGBoost)

Add unit tests for robustness

👨‍💻 Author

Dilitha Kolonne

GitHub: didi-au

Email: dilithakolonne@gmail.com
