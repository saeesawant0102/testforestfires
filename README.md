#  Iris Classification App

##  Overview
This project is a simple machine learning application that predicts the species of an Iris flower based on input features.
It uses a Random Forest Classifier and provides an interactive UI using Streamlit.

##  Features
- Input sepal & petal measurements
- Predicts Iris species (Setosa, Versicolor, Virginica)
- Simple web interface using Streamlit
- Fast and lightweight ML model

##  Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn
- Streamlit

##  Project Structure
project-folder/
│
├── classification.py    # Streamlit app
├── requirements.txt     # Dependencies
├── README.md            # Project documentation

##  Installation & Setup

1. Clone the repository (optional)
git clone <your-repo-link>
cd <project-folder>

2. Install dependencies
pip install -r requirements.txt

3. Run the application
streamlit run classification.py

##  Dataset
The dataset used is the Iris dataset from sklearn.datasets.
It includes:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

##  Model
- Algorithm: Random Forest Classifier
- Library: scikit-learn

##  Output
The model predicts:
- Setosa
- Versicolor
- Virginica

##  Author
Saee