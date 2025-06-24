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
- Google Colab account
- Titanic dataset files (train.csv, test.csv, gender_submission.csv)
- Required packages (automatically available in Colab):
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
   ```

2. Upload the notebook to Google Colab:
   - Open Google Colab
   - Go to File > Upload notebook
   - Select `titanic_final_project.ipynb`

3. Upload the dataset files:
   - The notebook will prompt you to upload the CSV files
   - Upload `train.csv`, `test.csv`, and `gender_submission.csv` when prompted

## Usage
1. Open the notebook in Google Colab
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
