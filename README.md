# La Liga Relevancy

## Overview

```sh
This repository is dedicated to exploring the pivotal role of young players in the Real Madrid Football Club's first-team squad, with a focus on their impact in La Liga and other competitions like the Copa del Rey and UEFA Champions League. 
```

## Data Source

Data was meticulously sourced from Wyscout, a leading provider of second-order sports data, ensuring the highest quality and relevance.

## Players Analysed

- Eduardo Camavinga
- Aurelien Tchouameni
- Jude Bellingham
- Daniel Ceballos (included for his effective passing range and deep understanding of Madrid's play style)

## Objective

The primary focus was on 'passes', a fundamental aspect of team play. The data is continuous, leading to the use of regression trees rather than classifiers. The analysis aims to quantify these players' relevance in domestic leagues and their regularity, as well as their impact on other competitions.

## Methodology

1. **Data Loading and Library Importation**
2. **Data Preprocessing**: Dropping and consolidating columns, managing missing data, converting percentage columns to floats.
3. **Position Relevance**
4. **Average Playing Minutes**
5. **Interceptions**
6. **Exploratory Data Analysis**: Employing Pearson and Spearman for heatmap analysis, creating dispersion matrices, and applying OneHotEncoding to categorical position columns.
7. **Feature Engineering**:
    - **Step 1 (Feature Establishment)**: Addition of new features based on dispersion matrix.
    - **Step 2 (Imputation Process)**: Applied to the processed data.
   
These steps were meticulously crafted to homogenise the data, making it more conducive for machine learning model application.

## Machine Learning Models
```sh
The repository includes decision tree visualisations and model validation curves to 
provide clear insights into the models' functioning and efficacy. 
The analysis hinges on machine learning models using Random Forests in both Scikit-Learn and XGBoost, chosen for their robust decision tree frameworks that can be finely tuned for optimised results.
```

## Audience

This repository is intended for experts in Data Science, Machine Learning Engineering, and Statisticians.

## Tone
```sh
The content is presented in a scholarly and professional manner, 
befitting the audience's expertise and the analytical nature of the subject.
```


### Virtual Environment
```sh
pip install --upgrade pip
python3 -m pip install virtualenv
python3 -m venv env
source env/bin/activate
source env/bin/deactivate
pip3 install -r requirements.txt
```

# Github Environment

Performed from Terminal Console
```sh
1. git init
2. git remote add origin ["copy here ssh or https"]
3. git remote -v
4. git add -A
5. git add .
6. git commit -m "insert here your commit"
7. git status
8. git push origin master
```

### Additional GitHub Commands
if you already created your repository, then:
```sh
1. git remote add origin ["copy here ssh or https"] 
2. same procedure applied above
3. Note: if you already got your ReadMe.md & License.md then,
firstly request your git pull origin master. THIS IS ALWAYS A RECOMMENDED PRACTICE.
4. git push origin master
```
