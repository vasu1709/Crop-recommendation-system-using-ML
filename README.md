# 🌾 Crop Recommendation System using random forest 
# 📌 Overview
This project aims to build a Machine Learning-based Crop Recommendation System that helps farmers or agricultural experts recommend the most suitable crop to grow based on various environmental and soil parameters. The model is trained using the Random Forest algorithm and is deployed using Pickle for real-time inference.

# 🧠 Problem Statement
Choosing the right crop based on soil and climatic conditions is crucial for optimal yield. This system takes inputs like Nitrogen, Phosphorous, Potassium, Temperature, Humidity, pH, and Rainfall and predicts the most suitable crop to grow.

# 📊 Dataset
The dataset contains the following columns:

N: Ratio of Nitrogen content in soil

P: Ratio of Phosphorous content in soil

K: Ratio of Potassium content in soil

Temperature: In degrees Celsius

# ⚙️ Technologies Used
Python

Pandas

NumPy

Scikit-learn

Matplotlib & Seaborn (for visualization)

Pickle (for model serialization)

Humidity: In %

pH: pH value of the soil

# 🧪 Model Training
Algorithm Used: Random Forest Classifier

Evaluation Metrics:

Accuracy Score

# Command to run
streamlit run deployment.py

Rainfall: In mm

Label: Recommended crop
