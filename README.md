# Student Exam Performance Predictor

## Overview

The Student Exam Performance Predictor is a Flask-based web application designed to predict students' exam performance based on various input features. It uses a trained machine learning model to make predictions and provides a user-friendly interface for input and results.

## Features

- **User-friendly interface**: Provides a form for users to input student details and receive predictions.
- **Predictive model**: Uses a trained machine learning model for predictions.
- **Responsive design**: Mobile-friendly and visually appealing design.

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/your-repository-name.git
   cd your-repository-name
   ```

2. **Set Up a Virtual Environment**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

## Running the Application

1. **Start the Flask Application**:
   ```bash
   python app.py
   ```
   - The app will be available at `http://127.0.0.1:5000/` by default.

2. **Access the Application**:
   - Open your browser and navigate to `http://127.0.0.1:5000/` to view the home page.
   - Use the form to input student details and get predictions.

## Project Details

- **`/artifacts/`**: Contains serialized objects like trained models and preprocessors.
- **`/catboost_info/`**: Contains information related to hyperparameters for CatBoost models.
- **`/notebook/`**: Includes Jupyter notebooks for data ingestion and exploration.
- **`/src/`**: Contains source code for the application, including prediction pipelines.
- **`/templates/`**: HTML templates for rendering web pages.
- **`app.py`**: Main Flask application script defining routes and handling requests.
- **`requirements.txt`**: Lists the Python dependencies required for the project.
- **`setup.py`**: Setup script for packaging and installing the application.

## Contributing

Feel free to fork the repository and submit pull requests with improvements or fixes. Ensure that your code adheres to the existing style and passes all tests.

## Acknowledgments

- **Flask Documentation**: [Flask Documentation](https://flask.palletsprojects.com/en/2.0.x/)
- **Scikit-learn Documentation**: [Scikit-learn Documentation](https://scikit-learn.org/stable/documentation.html)
- **CatBoost Documentation**: [CatBoost Documentation](https://catboost.ai/docs/)
  
