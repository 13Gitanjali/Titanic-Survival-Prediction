# Titanic-Survival-Prediction
This repository hosts a machine learning project aimed at predicting the survival of passengers on the Titanic. The project utilizes historical data such as passenger class, age, sex, and fare to train a variety 
of classification models. The goal is to accurately predict whether a passenger would have survived the Titanic disaster.

## Project Overview
This project aims to predict the survival of passengers on the Titanic, using machine learning techniques. The Titanic dataset is a popular dataset for beginners in data science and machine learning.

## Dataset
The dataset used in this project is the Titanic dataset from Kaggle. It includes passenger information like name, age, gender, socio-economic class, etc. The dataset is split into two parts - training set and
testing set.

## Dependencies
- Python 3.7+
- Pandas
- Numpy
- Scikit-learn
- Matplotlib
- Seaborn

## Files
- `titanic_train.csv`: The training set containing details of a subset of the passengers on board (891 passengers, to be exact) and importantly, will reveal whether they survived or not.
- `titanic_test.csv`: The test set contains similar information but does not disclose the “ground truth” for each passenger. It’s your job to predict these outcomes.
- `titanic.py`: The main Python script that contains the machine learning model and data processing steps.

## Usage
1. Clone the repository: `git clone https://github.com/username/titanic_survival_prediction.git`
2. Install the dependencies: `pip install -r requirements.txt`
3. Run the Python script: `python titanic.py`

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
