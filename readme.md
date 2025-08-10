# Heart Attack Risk Prediction

## ABOUT THE PROJECT

This project aims to develop a predictive model for assessing heart attack risk using Body Mass Index (BMI) as main predictor and controlled demographic variables for covariates. The project uses the CDC’s 2015 Behavioral Risk Factor Surveillance System (BRFSS) dataset, which includes responses from 441,456 U.S. adults. The model incorporates variables BMI, age, sex, income, race, and insurance coverage to estimate the probability of having heart attack. By using large dataset and controlling for demographic confounding variables, this project build a comprehensive and robust prediction model. The project also examines multicollinearity, explores interaction effects, and validates performance using error tests.

## GOALS
1. Identify key predictors of heart attack risk using nationally representative survey data.
2. Develop a robust logistic regression model to estimate heart attack probability.
3. Assess model performance.
4. Explore interaction effects between BMI and demographic variables.
5. Provide reproducible code and documentation for public health researchers and data scientists.

## REPOSITORY STRUCTURE
- **Code/**: Contains R scripts and R Markdown files for analysis.
- **Data/**: Contains cleaned datasets and a README describing data details.
- **Results/**: (If applicable) Stores output tables and plots.
- **readme.md**: Project overview and usage instructions.

## HOW TO USE REPOSITORY

### Reproducing the R Environment
This project uses [**renv**](https://rstudio.github.io/renv/) to ensure reproducibility.  
The `renv.lock` file contains the exact versions of all packages needed for this project, including:
- ggplot2
- car
- carData
- ResourceSelection
- pROC
- dplyr
- emmeans
- ggeffects

### HOW TO USE REPOSITORY
1. **Clone the repository**
   ```bash
   git clone https://github.com/Ytan54/EDA_Project.git
   cd EDA_Project
   ```
   
2. **Restore the package environment**
   ```bash
   renv::restore()
   ```
   
4. **Verify installation**
   ```bash
   renv::status()
   ```
   
5. Open the .Rmd files in the Code/ folder to view or re-run the analysis.
6. The Data/ folder contains cleaned_data.csv used for modeling.
7. Modify scripts or R Markdown files to test additional predictors or adjust the model.

