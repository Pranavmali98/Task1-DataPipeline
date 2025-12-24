# Task-1: Data Pipeline Development (ETL)

## Internship: CODTECH  
## Domain: Data Science  

---

##  Project Overview
This project demonstrates the development of a **Data Pipeline** for **data preprocessing, transformation, and loading (ETL)** using **Python**, **Pandas**, and **Scikit-learn**.

The pipeline automates the process of:
- Extracting raw data from a CSV file
- Cleaning and preprocessing the data
- Transforming numerical and categorical features
- Saving the processed data into a new CSV file

This task is completed as part of the **CODTECH Data Science Internship – Task 1**.

---

## Objective
To build an automated and reusable **ETL pipeline** that:
1. Extracts data from a CSV dataset  
2. Applies preprocessing and transformations  
3. Loads the transformed data for further analysis or modeling  

---

## Dataset
- **Source:** Kaggle – Titanic Dataset  
- **File Used:** `train.csv`  
- **Description:** Contains passenger information such as age, gender, class, fare, etc., and the target variable `Survived`.

---

## Tools & Technologies Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Google Colab (Jupyter Notebook)

---

## ETL Pipeline Workflow

### Extract
- Loaded the dataset using `pandas.read_csv()`

### Transform
- Handled missing values using forward fill
- Separated features and target variable
- Identified numerical and categorical columns
- Applied:
  - **StandardScaler** for numerical features
  - **OneHotEncoder** for categorical features
- Combined transformations using **ColumnTransformer**
- Automated preprocessing using **Pipeline**

### Load
- Converted the transformed output into a DataFrame
- Saved the cleaned data as `processed_data.csv`

---

## Project Structure
Task-1-Data-Pipeline/
│── train.csv
│── processed_data.csv
│── Task1_Data_Pipeline.ipynb
│── README.md

---

## How to Run the Project
1. Open the notebook `Task1_Data_Pipeline.ipynb` in Google Colab or Jupyter Notebook  
2. Upload `train.csv` to the working directory  
3. Run all cells sequentially  
4. The processed data will be saved as `processed_data.csv`

---

## Output
- A fully automated data preprocessing pipeline
- Cleaned and transformed dataset ready for machine learning tasks

---

## Conclusion
This project demonstrates a clean and modular approach to building a **data preprocessing pipeline** using industry-standard tools.  
It follows best practices in data science and fulfills the requirements of **CODTECH Task-1**.

---

## Author
**Pranav Mali**  
Data Science Intern – CODTECH
