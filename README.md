# Algerian Forest Fires Prediction
## This is an end-to-end Machine Learning web application built with Flask. It predicts the occurrence or severity of forest fires based on 9 meteorological and environmental input features using a Ridge Regression model.
# 📁 Project Structure
model/   
 
ridge.pkl: The trained Ridge Regression model.   
 
scaler.pkl: The StandardScaler used to normalize the 9 input features before prediction.   
 
notebooks/   
 
Algerian_forest_fires_dataset_UPDATE.csv: The raw dataset used for the project.   
 
EDA+FE+ModelTraining.ipynb: The Jupyter Notebook detailing the Exploratory Data Analysis, Feature Engineering, and Model Training pipeline.   
 
templates/   
 
home.html: The landing page of the application.   
 
index.html: The prediction form where users can input integer or float values for the 9 features.   
 
application.py: The main Flask application script that serves the web app, processes user input, and returns predictions.   
 
requirement.txt: Contains the list of Python dependencies (Flask, pandas, numpy, scikit-learn, etc.).   
 
## 🚀 Tech Stack
Backend: Python, Flask
Machine Learning: Scikit-learn, Pandas, NumPy
Frontend: HTML, CSS
## ⚙️ Installation & Setup
Clone the repository:
Bash
git clone <your-repository-url>
cd <repository-folder>
Create a virtual environment (recommended):
Bash
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
Install the dependencies:
Bash
pip install -r requirement.txt
## 💻 Usage
Run the Flask application:
Bash
python application.py
Open your web browser and navigate to the local host address provided in the terminal (usually [http://127.0.0.1:5000/](http://127.0.0.1:5000/) or [http://0.0.0.0:5000/](http://0.0.0.0:5000/)).
Navigate to the prediction page, enter the 9 environmental/weather metrics, and submit the form to see the model's prediction.
