🩺 Diabetes Prediction Model (SVM Algorithm)

📌 Project Overview

This project is a machine learning web application that predicts whether a patient is likely to have diabetes based on medical diagnostic measurements.
The model is trained using the Support Vector Machine (SVM) algorithm, which is well-suited for classification problems.

The web application is built with Flask and can be deployed on platforms like Netlify, Heroku, or Render.

⚙️ Features

📊 Predicts diabetes based on input health parameters.

🤖 Uses Support Vector Machine (SVM) for accurate classification.

🖥️ Web-based interface using Flask.

🔄 Model trained on the PIMA Indians Diabetes Dataset.

📦 Easy to deploy and extend with new features.

📊 Dataset

The dataset used is the Kaggle dataset.
It includes medical predictors such as:

--> Pregnancies

--> Glucose

--> Blood Pressure

--> Skin Thickness

--> Insulin

--> BMI

--> Diabetes Pedigree Function

--> Age

👉 The target variable is whether the patient has diabetes (0 = No, 1 = Yes).

🧠 Machine Learning Model

Algorithm: Support Vector Machine (SVM)
Kernel Used: RBF (Radial Basis Function)
Evaluation Metrics: Accuracy, Precision, Recall, F1-Score
The model was trained and evaluated using train-test split and achieved high accuracy in predicting diabetes.

📦 Dependencies

Python 3.10+
Flask 3.0.3
scikit-learn 1.5.1
numpy 1.26.4
pandas 2.2.2
joblib 1.4.2
gunicorn (for deployment)

🤝 Contributing
Contributions are welcome!
Feel free to fork this repo, make improvements, and submit a pull request.
