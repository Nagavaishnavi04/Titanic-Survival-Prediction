**Titanic-Survival-Prediction**

This project is a web application that predicts the survival of passengers on the Titanic using a machine learning model. The application is built with a simple user interface to input passenger details and receive predictions about survival likelihood.

**Features**
- **User Inputs:-**: 
  - Pclass: Passenger class (1, 2, or 3)
  - Sex: 0 for male, 1 for female
  - Age: Passenger's age
  - SibSp: Number of siblings/spouses aboard
  - Parch: Number of parents/children aboard
  - Fare: Ticket fare
  - Embarked: Port of Embarkation (0 for S, 1 for C, 2 for Q)

- **Survival Prediction**: The model predicts survival with a binary output (0 for not survived, 1 for survived).

**Technologies Used:-**
- **Frontend**: HTML/CSS for the user interface
- **Backend**: Flask for handling HTTP requests and responses
- **Machine Learning**: Scikit-learn for building the prediction model

**How to Run**
1. Clone this repository.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the Flask app with `python app.py`.
4. Access the application at `http://localhost:5000`.

**Dataset**
The model is trained on the Titanic dataset, which includes various features about the passengers.

**Future Improvements**
- Enhance the user interface for better user experience.
- Integrate more advanced machine learning models for improved accuracy.
- Add data visualization for better insights.

