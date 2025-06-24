# Titanic Survival Prediction Project

## Overview
This project implements a machine learning model to predict survival on the Titanic based on passenger data. The analysis explores various features such as passenger class, age, gender, fare, and family size to build predictive models.

## Project Structure
- `titanic_final_project.ipynb` - Main Jupyter notebook containing the complete analysis and modeling pipeline

## Features Analyzed
- **Passenger Class** - Socioeconomic status indicator
- **Age** - Passenger age with handling for missing values
- **Gender** - Sex of the passenger
- **Fare** - Ticket price
- **Family Size** - Combined SibSp (siblings/spouses) and Parch (parents/children)
- **Embarkation Port** - Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)
- **Cabin** - Cabin number (with feature engineering for deck level)

## Models Implemented
The project explores multiple machine learning algorithms:
- Logistic Regression
- Random Forest
- Support Vector Machine (SVM)
- Gradient Boosting
- Neural Networks

## Setup Instructions

### Prerequisites
- Python 3.7+
- Jupyter Notebook
- Required packages (install via pip):
  ```
  pandas
  numpy
  matplotlib
  seaborn
  scikit-learn
  tensorflow (for neural networks)
  ```

### Installation
1. Clone the repository:
   ```bash
   git clone git@github.com:rymurray1/titanic.git
   cd titanic
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

4. Open `titanic_final_project.ipynb` and run the cells

## Usage
1. Open the Jupyter notebook
2. Run all cells sequentially to execute the complete analysis
3. The notebook includes:
   - Data loading and exploration
   - Feature engineering
   - Model training and evaluation
   - Results visualization
   - Final predictions

## Results
The project evaluates model performance using:
- Accuracy score
- Cross-validation
- Confusion matrix
- Classification report

## Contributing
Feel free to submit issues and enhancement requests!

## License
This project is for educational purposes as part of the University of Colorado MSCS Machine Learning course.

## Author
Ryan Murray - University of Colorado MSCS Student 