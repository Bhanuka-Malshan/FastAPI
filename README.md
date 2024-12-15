# Car User Classification API

This project is a simple machine learning-based API that predicts vehicle types based on user attributes such as age and gender. The application is built using **FastAPI** and **Scikit-learn** and hosted on **Heroku**.

---

## Features

- **User Input**: Accepts input attributes (age, gender) through API endpoints.
- **Machine Learning Model**: Utilizes a Decision Tree Classifier to predict the vehicle type.
- **Heroku Hosting**: The application is hosted on Heroku, making it accessible online.
- **Pydantic Validation**: Ensures valid input data with the help of Pydantic's `BaseModel`.

---

## File Structure

```plaintext
├── CarUser.py             # Defines the Pydantic model for user input
├── FastAPI.ipynb          # Main code for data preprocessing, model training, and FastAPI integration
├── cars.csv               # Dataset used to train the Decision Tree Classifier
├── requirements.txt       # Python dependencies for the project
├── Procfile               # Defines the command to run the app on Heroku
├── README.md              # Project documentation
