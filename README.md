# 🚗 Car User Classification API 🚙

This project is a simple machine learning-based API that predicts vehicle types based on user attributes such as age and gender. The application is built using **FastAPI** and **Scikit-learn** and hosted on **Heroku**. 🚀

---

## 🔧 Features

- **User Input**: Accepts input attributes (age, gender) through API endpoints. 🧑‍💻
- **Machine Learning Model**: Utilizes a **Decision Tree Classifier** to predict the vehicle type. 🔍
- **Heroku Hosting**: The application is hosted on **Heroku**, making it accessible online. 🌐
- **Pydantic Validation**: Ensures valid input data with the help of Pydantic's `BaseModel`. ✅

---

## 📁 File Structure

```plaintext
├── CarUser.py             # Defines the Pydantic model for user input 🧑‍💻
├── FastAPI.ipynb          # Main code for data preprocessing, model training, and FastAPI integration 📓
├── cars.csv               # Dataset used to train the Decision Tree Classifier 🗃️
├── requirements.txt       # Python dependencies for the project 📦
├── Procfile               # Defines the command to run the app on Heroku 📄
├── README.md              # Project documentation 📜

```

## ⚙️ Setup and Installation
1 Clone the repository:

git clone <repository-url>
cd <repository-folder>

2 Install dependencies: Ensure you have Python installed (3.8 or later) and run:
pip install -r requirements.txt

3 Run Locally: Start the FastAPI server locally:
uvicorn FastAPI:app --reload

4 Access API Documentation: Open the browser and go to:
http://127.0.0.1:8000/docs 📚

## 📊 Dataset
The cars.csv file is used to train the Decision Tree Classifier. The dataset includes user attributes like age and gender and maps them to a vehicle_type output. 🚗

## 🚀 Deploying to Heroku
1 Install Heroku CLI: Follow the installation guide here. 🛠️
2 Login to Heroku:
heroku login

2 Create a Heroku App:
heroku create <app-name>

3 Add a Git Remote:
heroku git:remote -a <app-name>

4 Add a Git Remote:
5 Deploy to Heroku: Ensure Procfile is configured correctly:

## 📡 API Endpoints
POST /predict
Description: Predict the vehicle type based on user input. 🚗
Request Body

## 📋 Dependencies
FastAPI: Web framework for building APIs. 🌐
Scikit-learn: Machine learning library for model training. 📚
Pandas: For data manipulation and analysis. 📊
Uvicorn: ASGI server for serving FastAPI applications. ⚡
Pydantic: For input validation. ✅

## 🔮 Future Improvements
Add more features (e.g., income, location) to enhance prediction accuracy. 📈
Use a more advanced machine learning model like Random Forest or Gradient Boosting. 🌳
Implement a database to store user queries and model predictions. 🗄️



