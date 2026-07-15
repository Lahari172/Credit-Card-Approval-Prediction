# Flask Web Application

## Overview

The Flask Web Application provides a simple and interactive interface for predicting whether a credit card application is likely to be approved or rejected. It serves as the front-end of the Credit Card Approval Prediction System by connecting user inputs with the trained machine learning model.

---

## Features

- User-friendly interface
- Accepts applicant information through a web form
- Uses the trained Machine Learning model for prediction
- Displays instant approval or rejection results
- Lightweight and easy to deploy

---

## Technologies Used

- Python
- Flask
- HTML
- CSS
- Scikit-learn
- Pandas
- NumPy

---

## Project Structure

```
Flask_App/
│
├── app.py
├── requirements.txt
├── templates/
│   └── index.html
└── static/
    └── style.css
```

---

## Workflow

1. User enters applicant details.
2. Flask receives the input.
3. Input data is preprocessed.
4. The trained machine learning model predicts the result.
5. The prediction is displayed on the web page.

---

## Future Improvements

- Deploy the application on IBM Cloud.
- Add user authentication.
- Store prediction history in a database.
- Improve UI using Bootstrap.
- Support batch prediction through CSV upload.

---

## Conclusion

The Flask application demonstrates how machine learning models can be integrated into a web interface to provide real-time credit card approval predictions, making the system practical and easy to use.
