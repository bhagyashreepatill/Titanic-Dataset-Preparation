# Titanic Dataset Preparation & EDA

## Project Overview
This project demonstrates data preparation and exploratory data analysis (EDA) using the Titanic Passenger Dataset. It covers data inspection, missing-value handling, duplicate checking, visualization, categorical encoding, and numerical feature scaling.

## Objectives
- Inspect dataset structure, columns, and data types.
- Identify and handle missing values.
- Check duplicate records and data consistency.
- Perform exploratory data analysis using charts.
- Encode categorical features using one-hot encoding.
- Scale numerical features using StandardScaler.
- Export the prepared dataset to CSV format.

## Dataset Information
- **Dataset:** Titanic Passenger Dataset
- **Domain:** Transport
- **Original shape:** 891 rows × 12 columns
- **Source:** [DataScienceDojo Titanic CSV](https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv)
- **Format:** CSV

## Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab / Jupyter Notebook

## Data Preparation
1. Loaded and inspected the dataset.
2. Filled missing Age values using the median.
3. Filled missing Embarked values using the mode.
4. Removed the Cabin column because it contained many missing values.
5. Checked duplicate records before removing identifying columns.
6. Visualized passenger age distribution, gender counts, and survival counts.
7. Applied one-hot encoding to Sex and Embarked.
8. Standardized selected numerical features using StandardScaler.
9. Saved the prepared data as `prepared_titanic.csv`.

## Key Findings
- The original dataset contains 891 rows and 12 columns.
- Age and Embarked contained missing values.
- Cabin had a high percentage of missing values and was removed.
- The cleaned dataset contained no duplicate rows before feature selection.
- Numerical and categorical features were prepared for future machine learning workflows.

## Output Files
- `Activity1_Dataset_Preparation.ipynb` — Notebook with code, outputs, and visualizations.
- `prepared_titanic.csv` — Prepared dataset.

## Conclusion
This project demonstrates the importance of data cleaning and preprocessing before machine learning. Missing values were handled using suitable methods, categorical features were encoded, and selected numerical features were standardized. The final prepared dataset was exported to CSV for future analysis.

**Note:** The target column `Survived` is retained for potential future prediction tasks. No prediction model was trained in this project.
