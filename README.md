🏠 House Price Prediction Model

 I initiated this project to deepen my understanding and practical application of machine learning concepts. It proved to be an enriching and intellectually rewarding experience, and it was a genuine pleasure to work on.
 
This repository contains a simple House Price Prediction model implemented in Python. The project follows a structured process including data cleaning, model training using Ridge Regression, and deployment using a Flask web interface.

🔑 Key Components
📊 Data Cleaning
The model uses the Seattle House Price Prediction dataset from Kaggle. The data is cleaned to handle:

Missing values

Categorical features

Standard preprocessing steps

🤖 Model Development
A machine learning model is developed using Ridge Regression from the scikit-learn library. After training, the model is saved using joblib for later inference.

🌐 Flask Web Application
A user-friendly web interface is built using Flask. Users can input:

Number of bedrooms

Number of bathrooms

House size (sqft)

Zip code

The model will then predict the estimated house price.

🚀 Usage
1. Clone the Repository:
bash
Copy
Edit
git clone https://github.com/yourusername/HousePrice_Prediction.git
cd HousePrice_Prediction
2. Install Dependencies:
bash
Copy
Edit
pip install -r requirements.txt
3. Run the Flask App:
bash
Copy
Edit
python main.py
4. Access the Web App:
Open your browser and navigate to:

cpp
Copy
Edit
http://127.0.0.1:5000/
📁 Dataset Used
Seattle House Price Prediction Dataset – available on Kaggle

