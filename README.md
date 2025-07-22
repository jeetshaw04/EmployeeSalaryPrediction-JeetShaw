# EmployeeSalaryPrediction-JeetShaw

💼 Employee Salary Prediction 

🔍 Project Overview

This project presents an advanced machine learning solution for predicting and classifying employee salaries. By utilizing historical data on various employee features (e.g., education, experience, role, etc.), we aim to build a model that predicts whether an employee’s salary is greater than or less than 50K, and also estimates the actual salary value.

The system uses multiple machine learning models to compare performance and selects the best-performing model (Gradient Boosting Classifier) for deployment in a Streamlit web app.

🔗 Webpage Link: https://38e6ada1707a.ngrok-free.app
📂 GitHub Repo: EmployeeSalaryPrediction-JeetShaw


---

✨ Features

🌐 Interactive Web Application
Built with Streamlit to provide an easy and responsive UI for salary prediction.

🧠 Multiple Machine Learning Models
Includes:

Logistic Regression

k-Nearest Neighbors (KNN)

Support Vector Machine (SVM)

Random Forest

Gradient Boosting (best performance)


📊 Model Evaluation & Comparison
Graphical representation of accuracy scores to identify the best model.

📁 Batch Prediction Support
Upload a CSV file to get bulk predictions at once.

📉 Real-Time Prediction
Input employee details in a form to get instant salary classification and prediction.



---

📊 Dataset

The dataset includes employee-related attributes such as:

Education

Experience

Domain/Job Role

Location

Gender

Salary classification label (<=50K or >50K)


The data was preprocessed by handling missing values, encoding categorical variables, and splitting into training/testing sets.


---

🧰 Technology Stack

Python (core programming language)

Pandas, NumPy, Matplotlib, Seaborn (for data manipulation & visualization)

Scikit-learn, LightGBM (for ML models)

Streamlit (for web app development)

Joblib (for saving/loading trained models)

Jupyter Notebook / Colab (for experimentation)



---

🛠️ Installation & Setup

1. Clone the Repository

git clone https://github.com/jeetshaw04/EmployeeSalaryPrediction-JeetShaw.git
cd EmployeeSalaryPrediction-JeetShaw


2. Install Dependencies

pip install -r requirements.txt


3. Run the Application

streamlit run app.py




---

📈 Model Performance

Model	Accuracy

Logistic Regression	80.0%
KNN (k=5)	82.6%
SVM	81.0%
Random Forest	84.5%
Gradient Boosting	86.78% ✅


Final model: Gradient Boosting Classifier


---

🤝 Contribution

Developed by Jeet Shaw
B. P. Poddar Institute of Management & Technology
🎓 CSE Department | AICTE ID: STU68346e0bbbb6b1748266507


---

📄 License

This project is licensed under the MIT License.


---

                                                            

Requirements to run the colab file :-                             

1).ipynb colab notebook                                
                
2)adult 3.csv file                                    

3)rp.jpg background image file                                      
  
All are attached in this github file                                            

Link for Webpage -                           

https://38e6ada1707a.ngrok-free.app
