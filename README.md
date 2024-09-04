# Diaquest

## Dataset - CDC Diabetes Health Indicators

The Behavioral Risk Factor Surveillance System (BRFSS) is a health-related telephone survey that is collected annually by the CDC. Each year, the survey collects responses from over 400,000 Americans on health-related risk behaviors, chronic health conditions, and the use of preventative services. It has been conducted every year since 1984. For this project, a csv of the dataset available on Kaggle for the year 2015 was used. This original dataset contains responses from 441,455 individuals and has 330 features. These features are either questions directly asked of participants, or calculated variables based on individual participant responses. The data set used was consolidated by Alex Teboul.

The consolidated dataset comprises the following variables:

| Variable Name           | Role      | Type    | Description                                                                 | Units      |
|-------------------------|-----------|---------|-----------------------------------------------------------------------------|------------|
| ID                      | ID        | Integer | Patient ID                                                                  | -          |
| Diabetes_binary         | Target    | Binary  | 0 = no diabetes, 1 = prediabetes or diabetes                                | -          |
| HighBP                  | Feature   | Binary  | 0 = no high BP, 1 = high BP                                                 | -          |
| HighChol                | Feature   | Binary  | 0 = no high cholesterol, 1 = high cholesterol                               | -          |
| CholCheck               | Feature   | Binary  | 0 = no cholesterol check in 5 years, 1 = yes cholesterol check in 5 years   | -          |
| BMI                     | Feature   | Integer | Body Mass Index                                                             | -          |
| Smoker                  | Feature   | Binary  | 0 = no, 1 = yes (smoked ≥100 cigarettes in life)                            | -          |
| Stroke                  | Feature   | Binary  | 0 = no, 1 = yes (ever told had a stroke)                                    | -          |
| HeartDiseaseorAttack    | Feature   | Binary  | 0 = no, 1 = yes (coronary heart disease or myocardial infarction)           | -          |
| PhysActivity            | Feature   | Binary  | 0 = no, 1 = yes (physical activity in past 30 days)                         | -          |
| Fruits                  | Feature   | Binary  | 0 = no, 1 = yes (consume fruit ≥1 times per day)                            | -          |
| Veggies                 | Feature   | Binary  | 0 = no, 1 = yes (consume vegetables ≥1 times per day)                       | -          |
| HvyAlcoholConsump       | Feature   | Binary  | 0 = no, 1 = yes (heavy alcohol consumption)                                 | -          |
| AnyHealthcare           | Feature   | Binary  | 0 = no, 1 = yes (any healthcare coverage)                                   | -          |
| NoDocbcCost             | Feature   | Binary  | 0 = no, 1 = yes (could not see doctor due to cost)                          | -          |
| GenHlth                 | Feature   | Integer | General health status                                                       | scale 1-5  |
| MentHlth                | Feature   | Integer | Days in past 30 where mental health was not good                            | scale 1-30 |
| PhysHlth                | Feature   | Integer | Days in past 30 where physical health was not good                          | scale 1-30 |
| DiffWalk                | Feature   | Binary  | 0 = no, 1 = yes (difficulty walking/climbing stairs)                        | -          |
| Sex                     | Feature   | Binary  | 0 = female, 1 = male                                                        | -          |
| Age                     | Feature   | Integer | Age category                                                                | -          |
| Education               | Feature   | Integer | Education level                                                             | scale 1-6  |
| Income                  | Feature   | Integer | Income scale                                                                | scale 1-8  |

Link: https://archive.ics.uci.edu/dataset/891/cdc+diabetes+health+indicators

## Exploratory Data Analysis

## Data Visualization

## Predictive Analysis

