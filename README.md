# Titanic Survival Prediction

📌 Project Overview

This project predicts Titanic passenger survival using three machine learning models:

- Logistic Regression
- Random Forest
- Neural Network (TensorFlow/Keras)


The dataset is processed, trained, and evaluated using accuracy, precision, recall, and F1-score.

📊 Dataset Information

The Titanic dataset is taken from kaggle and contains the following features:
- Survival: Whether a passenger survived or not (0 or 1)
- Pclass: The socio-ecomonic class
    - Upper: 1
    - Middle: 2
    - Lower: 3
- Sex: Gender of the passenger (Male or Female)
- Age: Age in years (Age is fractional if less than 1. If the age is estimated, it is in the form of xx.5)
- SibSp: Number of siblings / spouses aboard the Titanic
- Parch: Number of parents / children aboard the Titanic
- Ticket: Ticket number
- Fare: Passenger fare
- Cabin: Cabin number
- Embarked: Port of Embarkation
    - C: Cherbourg
    - Q: Queenstown
    - S: Southampton

Project Structure:

- Preprocessing & EDA (preprocessing&EDA.ipynb)
    - Load the dataset.
    - Explore the data structure, types, and summary statistics.
    - Visualize relationships between features and the target variable.
    - Perform univariate and multivariate Analyis
    - Identify missing values and fill what required.

- Feature Engineering (feature_eng.ipynb)
    - Create new features
    - create column transformers with transformation like scaling, imputation, encoding, etc
    - Split the data into training and testing sets.
    - Create and Ffit the pipeline

- Model Building and Evaluation (model_building_evaluate.ipynb)
    - Separate train and test data (split the data)
    - Training Logistic and RandomForest model and then perform hypertuning.
    - Matrics Evaluation
    - Use ANN to predict, evalaute metrics as well

## 🚀 Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:

- Python 3.7 or higher
- pip (Python package installer)

### Installation

Follow these steps to set up and run the project on your local machine:

1. **Clone the Repository**

   Clone the repository using the following command:

   ```bash
   git clone 
   cd titanic-survival-prediction
   
2. **Create a Virtual Environment (Optional but Recommended)**

   Clone the repository using the following command:

   ```bash
    python -m venv venv
    # Activate the virtual environment
    source venv/bin/activate    # On Windows, use: venv\Scripts\activate
   
   
3. **Install Required Dependencies**

   pip install -r requirements.txt
   
4. Run different ipynb file for different purpose. 
- For preprocessing, preprocessing&EDA.ipynb
- For Feature Engineering, feature_eng.ipynb
- For model building, evaluation and prediction,model_building_evaluate.ipynb



 
