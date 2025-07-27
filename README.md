# Placement Project: Logistic Regression

This repository contains an end-to-end machine learning workflow using logistic regression to predict student placement outcomes based on CGPA and IQ. The project demonstrates the steps of data preprocessing, exploratory data analysis (EDA), feature selection, model training, evaluation, and deployment.

## Dataset

The dataset (`placement.csv`) contains the following features:
- `cgpa`: Student's CGPA (float) 
- `iq`: Student's IQ score (float)
- `placement`: Placement outcome (binary; 1 for placed, 0 for not placed)

## Workflow

The workflow in the Jupyter notebook (`end_to_end_ml.ipynb`) includes:

1. **Data Loading & Inspection**
   - Load dataset using pandas
   - Inspect data with `.head()`, `.info()`, `.shape()`

2. **Preprocessing**
   - Remove unnecessary columns
   - Visualize data using matplotlib

3. **Feature Selection**
   - Select relevant features (`cgpa`, `iq`) as input (X)
   - Target variable: `placement` (y)

4. **Train-Test Split**
   - Split data into training (90%) and testing (10%) sets

5. **Feature Scaling**
   - Standardize features using `StandardScaler`

6. **Model Training**
   - Train a logistic regression model (scikit-learn)

7. **Evaluation**
   - Assess model performance on the test set

8. **Deployment**
   - Prepare the model for deployment (additional steps can be added)

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook
- pandas
- numpy
- matplotlib
- scikit-learn

### Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/campusx-official/placement-project-logistic-regression.git
   cd placement-project-logistic-regression
   ```

2. Open the notebook:
   ```bash
   jupyter notebook end_to_end_ml.ipynb
   ```

3. Follow the steps in the notebook to run the workflow on the dataset.

## Project Structure

```
├── end_to_end_ml.ipynb
├── placement.csv
└── README.md
```
