# Project Name

## Overview
This project contains ML pipeline for explainable model using Llama2 7b. There are two main Jupyter notebooks: one for diabetes detection and another for heart failure prediction.


## STEPS:
Both the notebooks follow similar workflow detailed below:
1. Importing necessary libraries and loading data
2. Data Preprocessing
3. Generating prompts for the types of questions identified.
4. Loading Llama2 7b. 
5. Prompting LLM on the generated prompts to answer each type of question using LLama2
6. Using GPT3.5 API to infer the suggestions made by Llama2( If questions asks for changes in vitals)
7. Predicting probability scores based on Llama2 suggestions
8. Combining all results into single results file.
## Notebooks

### Diabetes Detection
- **File**: `diabetes_detection.ipynb`
- **Description**: A notebook that contains the workflow for detecting diabetes using patient data.
- **Usage**: Follow the instructions within the notebook to preprocess the data, train the model, and evaluate its performance.

### Heart Failure Prediction
- **File**: `heart_failure_prediction.ipynb`
- **Description**: This notebook outlines the process of predicting heart failure using clinical data.
- **Usage**: Execute the notebook cells in order to process the input data, train the prediction model, and visualize the results.

## Data
The Datasets required for the project are available in the datasets folder

