# B105-Applied-Statistical-Modelling-Assignment

# Titanic Survival Prediction

## Overview
This project demonstrates how to predict survival on the **Titanic** using a **logistic regression model**. The project is implemented in **Google Colab** using **R**, where various techniques such as **data preprocessing**, **model training**, and **evaluation** using metrics like **Precision**, **Recall**, and **F1-Score** are applied. The objective is to predict whether a passenger survived based on their features.

The notebook follows the steps of:
- Handling missing data.
- Preprocessing features (including encoding categorical variables).
- Building a logistic regression model.
- Evaluating the model's performance using key metrics.

## Dataset
The project uses the **Titanic dataset** provided by Kaggle, which contains data about passengers on the Titanic. The dataset includes the following columns:
- `PassengerId`: Unique identifier for each passenger.
- `Survived`: Target variable (1 = survived, 0 = did not survive).
- `Pclass`: Passenger class (1, 2, or 3).
- `Name`: Name of the passenger.
- `Sex`: Gender of the passenger.
- `Age`: Age of the passenger.
- `SibSp`: Number of siblings/spouses aboard.
- `Parch`: Number of parents/children aboard.
- `Ticket`: Ticket number.
- `Fare`: Fare paid by the passenger.
- `Cabin`: Cabin number.
- `Embarked`: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).

You can download the Titanic dataset from [Kaggle Titanic Competition](https://www.kaggle.com/competitions/titanic/data).

## Project Structure
- `titanic_survival_prediction.ipynb`: Jupyter Notebook containing the code for the Titanic survival prediction model, including data preprocessing, model training, and evaluation.

## How to Run in Google Colab

### Requirements
- **Google Colab**: No need for local setup. You can run the notebook directly on Google Colab.

### Steps to Run:
1. **Open Google Colab**:
   - Go to [Google Colab](https://colab.research.google.com/).
   - Click on **File** > **Open notebook** and select **GitHub** or upload the `.ipynb` file from your local system.

2. **Install Necessary Libraries**:
   In the Google Colab environment, install required libraries with:
   ```python
   # Install necessary R packages
   !apt-get install -y r-base
   !Rscript -e "install.packages('IRkernel')"
   !Rscript -e "IRkernel::installspec(user = FALSE)"
