🐉 Dragon Real Estate Price Prediction

A complete Machine Learning project that predicts house prices using regression algorithms. It includes data preprocessing, exploratory data analysis (EDA), model building, evaluation, and saving the best-performing model.

📁 Project Structure
01_Dragon_Real_Estate_Price_Prediction_Model
│
├── Data/
│   ├── housing.csv
│   └── housing_names.txt
│
├── Dragon_Real_Estate.ipynb
├── Dragon.joblib
├── Output_from_Diffrent_Models.txt
├── requirements.txt
└── README.md

🎯 Objective
The goal of this project is to analyze real estate data and build a machine learning model that predicts house prices accurately.
Multiple models were trained and compared to select the best-performing one.

📊 Model Performance Summary
Model results taken from Output_from_Diffrent_Models.txt:

🧠 Model	📉 Mean Error	📈 Std. Deviation
Decision Tree Regression	3.9559	0.6562
Linear Regression	5.0256	1.0307
Random Forest Regression	3.3376	0.6613

✅ Best Model: Random Forest Regression
🚀 How to Run the Project
1️⃣ Clone the repository
git clone https://github.com/Musharraf-Bubere/Machine-Learning-Projects.git

2️⃣ Install the required libraries
pip install -r requirements.txt

3️⃣ Launch the Jupyter Notebook
jupyter notebook Dragon_Real_Estate.ipynb

4️⃣ (Optional) Load the trained model
import joblib
model = joblib.load("Dragon.joblib")

🧰 Technologies Used
🐍 Python
🔢 NumPy
🧮 Pandas
📊 Matplotlib
🌈 Seaborn
🤖 Scikit-learn
💾 Joblib
📝 Jupyter Notebook

🌟 Features
✔ Data cleaning and preprocessing
✔ Exploratory data analysis
✔ Feature engineering
✔ Training multiple regression models
✔ Model performance comparison
✔ Saving and loading trained model

🔮 Future Enhancements
🔧 Add hyperparameter tuning
🌐 Deploy using Streamlit or Flask
🖥 Add a user-friendly dashboard
🚀 Experiment with advanced ML models like XGBoost

👨‍💻 Author
Musharraf Bubere
Machine Learning Projects Portfolio