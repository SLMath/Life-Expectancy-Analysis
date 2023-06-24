# Life Expectancy Analysis On Different Countries

![Screen Shot 2023-06-24 at 11 21 49](https://github.com/SLMath/Life-Expectancy-Analysis/assets/52578481/20fad8f0-8bd9-4f0b-8de9-beb4c6ee210d)


## Description
Using the ["Life Expectancy (WHO)" dataset](https://www.kaggle.com/datasets/kumarajarshi/life-expectancy-who), 
we have generated insights about the correlation between the 22 parameters.

We have also trained some linear regression models to try to predict "Life Expectancy (in ages)".

### Dataset Metadata
1. Country
2. Year
3. Status: Developed or Developing status (for each country)
4. Life Expectancy (in ages)
5. Adult Mortality: rates of both sexes (probability of dying between 15 and 60 years per 1000 population)(%)
6. infant deaths: Number of Infant Deaths per 1000 population
7. Alcohol: recorded per capita (15+) consumption (in litres of pure alcohol)
8. percentage expenditure: Expenditure on health as a percentage of Gross Domestic Product per capita(%)
9. Hepatitis B: HepB immunization coverage among 1-year-olds (%)
10. Measles (sarampo): number of reported cases per 1000 population 
11. BMI: Average Body Mass Index of entire population
12. under-five deaths: Number of under-five deaths per 1000 population 
13. Polio: Pol3 immunization coverage among 1-year-olds (%)
14. Total expenditure: General government expenditure on health as a percentage of total government expenditure (%)
15. Diphtheria: diphtheria tetanus toxoid and pertussis (DTP3) immunization coverage among 1-year-olds (%)
16. HIV/AIDS: Deaths per 1000 live births HIV/AIDS (0-4 years)
17. GPD: Gross Domestic Product per capita (in USD)
18. Population
19. thinness 1-19 years: Prevalence of thinness among children and adolescents for Age 10 to 19 (%)
20. thinness 5-9 years: Prevalence of thinness among children for Age 5 to 9(%)
21. income composition of resources: Human Development Index in terms of income composition of resources (index ranging from 0 to 1)
22. Schooling (in years)

## Getting Started
You can try this code on your own by opening google colab, and chossing "File"> "Open notebook" > "GitHub" and inserting the URL for this project. Then you only need to select the notebook file that is shown there.

When running the code in a notebook environment, two files are generated:
"fill_missing_gdp.csv" and "fill_missing_population.csv". 
You may fill them with real data so that the code use it instead of removind these records.

## Tools
Python,
Pandas,
Data Visualization (Matplotlib, Seaborn),
Scikit-learn (for training and evaluation models)

## Improvements
- Understand why the model is performing so well at the testing data (there may be data leakage)
- Input missing data
- Search for better ways to treat data

## Notes
This project was initially developed during ADA's Data Science Path course - Statistics II module,
along with collaborators.
