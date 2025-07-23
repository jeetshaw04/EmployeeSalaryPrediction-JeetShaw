# EmployeeSalaryPrediction-JeetShaw

💼 Employee Salary Prediction 

WEBPAGE URL- https://employeesalaryprediction-jeetshaw04.streamlit.app/


🔍 Project Overview

This project presents an advanced machine learning solution for predicting and classifying employee salaries. By utilizing historical data on various employee features (e.g., education, experience, role, etc.), we aim to build a model that predicts whether an employee’s salary is greater than or less than 50K, and also estimates the actual salary value.

The system uses multiple machine learning models to compare performance and selects the best-performing model (Gradient Boosting Classifier) for deployment in a Streamlit web app.

🔗 Webpage Link: https://employeesalaryprediction-jeetshaw04.streamlit.app/


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

The dataset includes employee-related attributes from the UCI Adult Census Dataset, which contains over 48,000 instances with 14 attributes.
 These attributes include:

age: Age of the individual.

workclass: Type of employer (e.g., Private, Self-emp-not-inc, Federal-gov).

fnlwgt: Final weight (census-specific, represents the number of people the census believes the entry represents).

education: Highest level of education achieved (e.g., Bachelors, HS-grad, Some-college).

educational-num: Numerical representation of education level.

marital-status: Marital status (e.g., Married-civ-spouse, Never-married, Divorced).

occupation: Type of occupation (e.g., Tech-support, Craft-repair, Exec-managerial).

relationship: Relationship within the household (e.g., Husband, Own-child, Not-in-family).

race: Race of the individual (e.g., White, Black, Asian-Pac-Islander).

gender: Gender of the individual (Male, Female).

capital-gain: Capital gains from investments.

capital-loss: Capital losses from investments.

hours-per-week: Number of hours worked per week.

native-country: Country of origin.

income:  Salary classification label (<=50K or >50K)


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


---

📄 License

This project is licensed under the MIT License.


---

                                                            

Requirements to run the colab file :-                             

1).ipynb colab notebook                                
                
2)adult 3.csv file                                    

3)rp.jpg background image file                                      
  
All are attached in this github file                                            
