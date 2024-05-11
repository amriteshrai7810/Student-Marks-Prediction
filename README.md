# Student Marks Prediction Model
This project implements a web application for predicting student marks using machine learning. The application is built with Flask framework in Python. It utilizes pipelines for data preprocessing and prediction, along with custom exception handling and logging.

<b> Installation </b>
1. Clone the repository: git clone <repository-url>
2. Install the required dependencies: pip install -r requirements.txt
3. Run the Flask application: python app.py

# Usage
Once the application is running, navigate to http://localhost:5000/ in your web browser. You will see the home page where you can enter student details and predict their marks.

# Project Structure
1. app.py: Main Flask application file containing routes for handling requests.
2. index.html: HTML template for the home page.
3. home.html: HTML template for displaying prediction results.
4. src/pipeline/predict_pipeline.py: Module implementing the prediction pipeline.
5. src/pipeline/custom_data.py: Module defining the CustomData class for handling input data.
6. README.md: This file.

# Components
* Flask: Web framework for building the application.
* Pandas: Library for data manipulation and analysis.
* NumPy: Library for numerical computing.
* Scikit-learn: Library for machine learning tasks.
* pickle: Module for serializing and deserializing Python objects.
* StandardScaler: Preprocessing class for scaling features.

# Contributing
Feel free to contribute to this project by opening issues or pull requests.

# License
This project is licensed under the MIT License - see the LICENSE file for details.
