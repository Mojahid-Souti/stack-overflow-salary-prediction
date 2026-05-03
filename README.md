# Stack Overflow Developer Survey – CRISP-DM Machine Learning Project

## Motivation
The technology industry is highly competitive, and understanding the factors that influence developer compensation is valuable for both professionals and employers. This project analyzes data from the Stack Overflow Developer Survey to explore relationships between professional experience and salary, and to build a machine learning model that predicts whether a developer earns above the median salary.

## Business Questions
This project seeks to answer the following questions:
1. How does professional coding experience relate to developer salary?
2. What is the distribution of developer annual compensation?
3. Are developers with more experience more likely to earn above the median salary?
4. Can a machine learning model predict whether a developer earns above the median salary?

## Dataset

This project uses data from the Stack Overflow Developer Survey.
Due to GitHub file size limitations, the dataset is not stored in this repository.

The full dataset is publicly available at:
https://survey.stackoverflow.co/

## Libraries Used
The analysis was conducted using Python with the following libraries:
*   `pandas`
*   `numpy`
*   `matplotlib`
*   `seaborn`
*   `scikit-learn`

## CRISP-DM Process
The project follows the CRISP-DM framework:
1. **Business Understanding** – Defined business questions related to developer salaries.
2. **Data Understanding** – Performed exploratory data analysis and visualizations.
3. **Data Preparation** – Handled missing values and converted non-numeric fields.
4. **Modeling** – Trained a logistic regression model.
5. **Evaluation** – Evaluated the model using accuracy, precision, and recall.
6. **Deployment** – Used the trained model to make a prediction for a new scenario.

## Results Summary
*   Developer salary is positively associated with years of professional coding experience.
*   The logistic regression model was able to predict whether a developer earns above the median salary with reasonable performance.
*   Evaluation metrics such as accuracy, precision, and recall provided insight into the model’s strengths and limitations.

## Files in This Repository
*   `notebook.ipynb` – Jupyter notebook containing the full data analysis, modeling, and evaluation.
*   `survey_results_public.csv` – Raw dataset used for the project.
*   `README.md` – Overview and documentation for the project.

## Acknowledgements
*   Stack Overflow for making the Developer Survey data publicly available.
*   Udacity Data Science Nanodegree program for project guidelines and structure.
