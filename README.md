# Diaquest

## Dataset - CDC Diabetes Health Indicators

The Behavioral Risk Factor Surveillance System (BRFSS) is a health-related telephone survey that is collected annually by the CDC. Each year, the survey collects responses from over 400,000 Americans on health-related risk behaviors, chronic health conditions, and the use of preventative services. It has been conducted every year since 1984. For this project, a csv of the dataset available on Kaggle for the year 2015 was used. This original dataset contains responses from 441,455 individuals and has 330 features. These features are either questions directly asked of participants, or calculated variables based on individual participant responses. The data set used was consolidated by Alex Teboul.

The consolidated dataset comprises the following variables:

| Variable Name           | Role      | Type    | Description                                                                                                 | Units       |
|-------------------------|-----------|---------|-------------------------------------------------------------------------------------------------------------|-------------|
| ID                      | ID        | Integer | Patient ID                                                                                                  | -           |
| Diabetes_binary         | Target    | Binary  | 0 = no diabetes, 1 = prediabetes or diabetes                                                                | -           |
| HighBP                  | Feature   | Binary  | 0 = no high BP, 1 = high BP                                                                                 | -           |
| HighChol                | Feature   | Binary  | 0 = no high cholesterol, 1 = high cholesterol                                                               | -           |
| CholCheck               | Feature   | Binary  | 0 = no cholesterol check in 5 years, 1 = yes cholesterol check in 5 years                                   | -           |
| BMI                     | Feature   | Integer | Body Mass Index                                                                                             | -           |
| Smoker                  | Feature   | Binary  | 0 = no, 1 = yes (smoked ≥100 cigarettes in life)                                                            | -           |
| Stroke                  | Feature   | Binary  | 0 = no, 1 = yes (ever told had a stroke)                                                                    | -           |
| HeartDiseaseorAttack    | Feature   | Binary  | 0 = no, 1 = yes (coronary heart disease or myocardial infarction)                                           | -           |
| PhysActivity            | Feature   | Binary  | 0 = no, 1 = yes (physical activity in past 30 days)                                                         | -           |
| Fruits                  | Feature   | Binary  | 0 = no, 1 = yes (consume fruit ≥1 times per day)                                                            | -           |
| Veggies                 | Feature   | Binary  | 0 = no, 1 = yes (consume vegetables ≥1 times per day)                                                       | -           |
| HvyAlcoholConsump       | Feature   | Binary  | 0 = no, 1 = yes (heavy alcohol consumption)                                                                 | -           |
| AnyHealthcare           | Feature   | Binary  | 0 = no, 1 = yes (any healthcare coverage)                                                                   | -           |
| GenHlth                 | Feature   | Integer | General health status                                                                                       | scale 1-5   |
| MentHlth                | Feature   | Integer | Days in past 30 where mental health was not good                                                            | scale 1-30  |
| PhysHlth                | Feature   | Integer | Days in past 30 where physical health was not good                                                          | scale 1-30  |
| DiffWalk                | Feature   | Binary  | 0 = no, 1 = yes (difficulty walking/climbing stairs)                                                        | -           |
| Sex                     | Feature   | Binary  | 0 = female, 1 = male                                                                                        | -           |
| Age                     | Feature   | Integer | Age category using _AGEG5YR: 1=18-24, 2=25-29, 3=30-34, 4=35-39, 5=40-44, 6=45-49, 7=50-54, 8=55-59, 9=60-64, 10=65-69, 11=70-74, 12=75-79, 13=80 or older | scale 1-13  |
| Education               | Feature   | Integer | Education level using EDUCA: 1=Never attended school or only kindergarten, 2=Grades 1-8, 3=Grades 9-11, 4=Grade 12 or GED, 5=College 1-3 years, 6=College 4+ years | scale 1-6   |
| Income                  | Feature   | Integer | Income scale using INCOME2: 1=Less than $10,000, 2=$10,000-$14,999, 3=$15,000-$19,999, 4=$20,000-$24,999, 5=$25,000-$34,999, 6=$35,000-$49,999, 7=$50,000-$74,999, 8=$75,000 or more | scale 1-8   |


Link: https://archive.ics.uci.edu/dataset/891/cdc+diabetes+health+indicators

## Exploratory Data Analysis

## Data Visualization

## Predictive Analysis

