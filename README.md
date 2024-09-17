# Lead Scoring Model for X Education company
Building a logistic regression model to predict the conversion of leads into paying customers for an online education company.

## Project Overview
X Education is an education company that sells online courses to industry professionals. The goal of this project is to build a model that assigns a lead score to each lead, indicating the likelihood of conversion into a paying customer. The target lead conversion rate is approximately 80%.

## Objectives
1. To identify the variables that help identify the leads that are most likely to convert into paying customers.

2. To assign a lead score to each of the leads such that the customers with a higher lead score have a higher conversion chance and the customers with a lower lead score have a lower conversion chance.

3. To calculate the confusion matrix and know the overall accuracy,sensitivity,specificity and recall of the model i.e. how well these variables describe the lead conversion probability.
  

## Methodology

1. **Data Preprocessing**:
   - Clean and preprocess the data.
   - Handle missing values and outliers.
   - Encode categorical variables.

2. **Feature Selection**:
   - Identify and select key variables that influence lead conversion.
   - Use techniques such as correlation analysis, RFE and manual selection based  on p-values and VIFs.

3. **Model Development**:
   - Split the data into training and testing sets.
   - Train the logistic regression model.
   - Evaluate model performance using cross-validation.

4. **Lead Scoring**:
   - Assign lead scores based on the model's predictions.
   - Rank leads by their scores to prioritize follow-ups.

5. **Model Evaluation**:
   - Calculate the confusion matrix.
   - Evaluate accuracy, sensitivity, specificity, precision and recall.


## Evaluation Metrics

- **Accuracy**: The proportion of true results (both true positives and true negatives) among the total number of cases examined.
- **Confusion Matrix**: A table used to describe the performance of the model.
- **Sensitivity**: The ability of the model to correctly identify positive cases.
- **Specificity**: The ability of the model to correctly identify negative cases.
- **Recall**: The ability of the model to correctly identify all relevant positive instances.
- **Precision**: The ability of the model to measure the accuracy of the positive predictions made by the model.


## Tools and Technologies

- **Programming Language**: Python
- **Libraries**: pandas, numpy, matplotlib, seaborn, scikit-learn, statsmodels
- **Environment**: Jupyter Notebook

## Getting Started

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-repo/Lead_Scoring.git
   cd Lead_Scoring
   ```

2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Notebook**:
   Open `LeadScoring_PythonFile.ipynb` in Jupyter Notebook and follow the steps.


## Contributors
https://github.com/pavprasaddh
