# Heart Disease Analysis

This repository contains the code and analysis for a heart disease dataset. In this project, we explore the dataset, perform data cleaning, and visualize various aspects of the data to gain insights into heart disease and its potential risk factors. Below is an overview of the key steps and findings of the analysis.

## Dataset Information

The dataset used in this analysis is named `heart.csv` and contains the following columns:

- `age`: Age of the individual
- `sex`: Gender (0: Female, 1: Male)
- `cp`: Chest Pain Type (0: Typical Angina, 1: Atypical Angina, 2: Non-anginal pain, 3: Asymptomatic)
- `trestbps`: Resting blood pressure (in mm Hg on admission to the hospital)
- `chol`: Serum cholesterol in mg/dl
- `fbs`: Fasting blood sugar > 120 mg/dl (1: True, 0: False)
- `restecg`: Resting electrocardiogram results (0: Normal, 1: Abnormality with ST-T wave, 2: Probable or definite left ventricular hypertrophy)
- `thalach`: Maximum heart rate achieved during exercise
- `exang`: Exercise-induced angina (1: Yes, 0: No)
- `oldpeak`: ST depression induced by exercise relative to rest
- `slope`: The slope of the peak exercise ST segment (1: Upsloping, 2: Flat, 3: Downsloping)
- `ca`: Number of major vessels colored by fluoroscopy (0-3)
- `thal`: Thalassemia type (3: Normal, 6: Fixed defect, 7: Reversible defect)
- `target`: Target variable indicating the likelihood of heart disease (0: Less chance, 1: More chance)

## Analysis Steps

1. **Data Loading and Initial Exploration**: We start by loading the dataset and displaying the first five and last five rows to get an initial understanding of the data's structure.

2. **Data Shape**: We determine the number of rows and columns in the dataset.

3. **Data Information**: We provide an overview of the data types and null values in the dataset.

4. **Data Cleaning**: We check for duplicate rows and remove them if any duplicates are found.

5. **Statistical Summary**: We calculate and display overall statistics for the dataset, including mean, standard deviation, minimum, maximum, and quartiles for numerical columns.

6. **Data Correlation**: We create a heatmap to visualize the correlation between different features in the dataset.

7. **Distribution of Target Variable**: We analyze the distribution of the target variable `target` to understand the number of people with and without heart disease.

8. **Gender Distribution**: We investigate the distribution of gender (`sex`) in the dataset and plot the results.

9. **Gender vs. Heart Disease**: We visualize the relationship between gender and the likelihood of heart disease.

10. **Age Distribution**: We plot a histogram to visualize the distribution of ages in the dataset.

11. **Chest Pain Type Distribution**: We analyze the distribution of chest pain types (`cp`) and plot the results.

12. **Chest Pain Type vs. Heart Disease**: We explore the relationship between chest pain types and the likelihood of heart disease.

13. **Fasting Blood Sugar vs. Heart Disease**: We investigate the distribution of fasting blood sugar levels (`fbs`) in relation to heart disease.

14. **Resting Blood Pressure Distribution**: We visualize the distribution of resting blood pressure (`trestbps`) in the dataset.

15. **Resting Blood Pressure by Gender**: We compare resting blood pressure by gender.

16. **Serum Cholesterol Distribution**: We plot a histogram to visualize the distribution of serum cholesterol levels (`chol`).

17. **Continuous Value Distributions**: We visualize the distributions of columns with continuous values.

## Usage

You can use the provided Python code to perform similar analyses on the heart disease dataset. Feel free to customize and extend the analysis as needed for your specific research or project.

## Dependencies

To run the code in this repository, you will need the following Python libraries:

- pandas
- matplotlib
- seaborn

You can install these dependencies using `pip` or `conda`.

## Acknowledgments

The dataset used in this analysis is credited to its original source, which should be referenced appropriately in any further use or publication.

## Author

This analysis was conducted by [Samuel Yaula Dutse].

If you have any questions or suggestions regarding this analysis, please feel free to contact me.
