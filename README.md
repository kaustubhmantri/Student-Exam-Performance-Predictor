### Student Exam Performance Predictor

## Project Overview
```
The goal of this project is to predict student performance based on various socio-economic factors, including:

Gender
Ethnicity
Parental Education Level
Lunch Type
Test Preparation Course
The model helps identify how these factors contribute to students' test scores, offering insights into their performance.
```
# How to run?

### Create a conda environment after opening the repository

```bash
conda create -n predictor python=3.8 -y
conda activate predictor
```

### Install the requirements
```bash
pip install -r requirements.txt
```

### Download the data used from below link
```
https://www.kaggle.com/datasets/spscientist/students-performance-in-exams?datasetId=74977
```


### Run the Model Training file

```ini
python model_training.py

```

### Run the Flask App

```ini
python app.py

```
### The app is deployed on AWS Elastic Beanstalk. 


### Modules
```
Modular Code Structure:
Separate modules for data ingestion, data transformation, and model training to ensure maintainability.

Data Transformation:
A custom Data Transformer using Pipelines for transforming the raw data into a model-friendly format.

Exploratory Data Analysis (EDA):
Insights into data distribution and feature relationships through EDA and Feature Engineering techniques.

Predict Pipeline:
Implements a prediction pipeline to make performance predictions based on the trained model.
```


