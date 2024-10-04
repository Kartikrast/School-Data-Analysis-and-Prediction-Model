
![School Prediction](https://github.com/user-attachments/assets/c1ecbb74-e025-47e4-a294-b82437ef7fef)



# Predicting Urgency of New Schools in Districts

## Overview
In this project, we analyze two datasets: School Data and Population Data. Our goal is to build machine learning models that predict the urgency of the need for new schools in each district. The "Need_Category" is divided into three levels: RED (most urgent), Yellow (moderate urgency), and Green (least urgent).

## Data Description
### School Data
- **Year Built**: The year each school was established. We extract only the year from the date (since all dates are 01-01) and observe the following:
  - Minimum year: 1908
  - 50% of data goes up to 1987
  - 25% of data goes up to 1975
  - The frequency of school construction increased after 1975.
- **Capacity**: The capacity of each school. Key observations:
  - 50% of data is evenly distributed.
  - The next 25% (75%) shows slightly lower capacity.
  - There are outliers (e.g., maximum capacity).
  - Standard deviation indicates a wide range.
- **Shifts**: Number of shifts (1, 2, or 3) in each school.
- **Total Students**: Sum of boys and girls. Notable points:
  - Minimum value of 3 (an outlier).
  - Data distribution around 250-300.
  - Large difference between 75% and maximum values (upper limit outliers).
- **Boys and Girls**: These columns are evenly divided, except for maximum values.
- **Transport Stops**: Contains missing values. Most data falls within 200 stops, with a maximum of 500. Good connectivity within 500 meters.

## Workflow
![S C A M P E R](https://github.com/user-attachments/assets/db9b93ab-1e87-4841-b327-94f9604c88a4)

1. **Data Exploration**: Started with the School Dataset, which is our primary dataset.
2. **Data Preprocessing and Wrangling**: Cleaned missing values, handle outliers, and extract relevant features.
3. **Feature Engineering**: Created additional features if needed.
4. **Dependent Variable Creation**: Created the dependent variable as per the analysis and requirements.
5. **Model Building**: Developed four ML models to predict urgency levels.
6. **Evaluation and Fine-Tuning**: Assessed model performance and optimize hyperparameters.
7. **Documentation**: Wrote clear code comments and documented process.

## Project Presentation Link:-
https://www.notion.so/Presentation-899f5c6474e5436f8297c54995ed2362?pvs=4

## Project Report Notion Link:-
https://www.notion.so/Project-Files-and-Dashboard-9be6b8bc039b4e05a86085bdafa583f0?pvs=4
