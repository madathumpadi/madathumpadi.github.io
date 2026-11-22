# Vinay Krishnan 
### Data Science | Software Quality Assurance | Automation

[About](#about-me) | [Projects](#projects) | [Contact](#contact)

## About Me
I am an IT professional with more than 20 years of experience, primarily in software quality assurance, currently working at an
investment firm.
I hold a degree in Engineering and an MBA, and I am pursuing a Master of Science in Data Science at Bellevue University.
My background includes software testing, quality assurance, and automation. Through my graduate studies and projects, I am
developing my skills in Python, SQL, data analysis, visualization, and machine learning.
My career goal is to apply data science within the investment industry, create automations that improve efficiency and accuracy,
and grow into roles with greater technical and leadership responsibility.
This portfolio showcases my projects and my progress in using data to solve practical business problems.


## Projects


### Airline Reviews Analysis Using Natural Language Processing
Analyzed a dataset of 23,171 passenger reviews to identify airline service problems across seven categories, including
seat comfort, cabin staff, ground service, and value for money.
**Methods:** Cleaned the data, explored customer feedback, and built seven classification models using TF-IDF and
Logistic Regression. 
**Results:** On held-out test data, problem-class F1 scores ranged from 0.873 to 0.942. Value for Money and Ground Service
achieved the strongest results. Missing ratings and class imbalance were important limitations.
**Tools:** Python, pandas, NumPy, NLTK, scikit-learn, Matplotlib, and WordCloud.
**Business value:** Demonstrates how automated review analysis could help airlines identify recurring customer concerns
and prioritize service improvements.
[View Project Notebook](https://github.com/madathumpadi/madathumpadi.github.io/blob/main/AirlineReviewAnalysis.ipynb)


### Global Population Analysis
Combined population and geographic information from a CSV dataset, Worldometers web tables, and the REST Countries API to prepare
data for exploring global demographic patterns.
**Methods:** Standardized country identifiers and data formats, checked missing values and duplicates, examined outliers,
and integrated cleaned datasets using SQLite and SQL joins.
**Analysis:** Created visualizations exploring population by country and continent, population density, land area, growth
rates, median age, and fertility rates.
**Tools:** Python, pandas, NumPy, Requests, pycountry, SQLite, Matplotlib, and Seaborn.
**Practical value:** Demonstrates how to transform information from different sources into a consolidated dataset for
demographic research and planning. Differences in reporting years and data-cleaning choices require careful interpretation.
[View Project Notebook](https://github.com/madathumpadi/madathumpadi.github.io/blob/main/GlobalPopulationAnalysis.ipynb)


### U.S. Retail Sales Forecasting
Explored monthly U.S. retail sales from January 1992 through June 2021 to examine trends and seasonal patterns and compare
two forecasting approaches.
**Methods:** Reshaped sales data into a chronological time series and built Holt-Winters Exponential Smoothing and
SARIMA models. Used July 2020–June 2021 as a held-out test period and evaluated forecasts using RMSE.
**Key insight:** Both approaches struggled to capture the sharp increase in sales during the test period, illustrating
the limitations of forecasting when historical patterns change.
**Tools:** Python, pandas, NumPy, Matplotlib, statsmodels, and scikit-learn.
**Business value:** Demonstrates how to evaluate forecasts for demand planning, inventory management, and resource
allocation while communicating uncertainty.
[View Project Notebook](https://github.com/madathumpadi/madathumpadi.github.io/blob/main/RetailSalesForecasting.ipynb)


### U.S. Gasoline Price Prediction
Explored weekly U.S. regular gasoline prices using energy market and economic data from Federal Reserve Economic Data
(FRED) and the U.S. Energy Information Administration (EIA).
**Methods:** Cleaned and combined datasets at weekly frequency, explored relationships between variables, and compared Random
Forest, XGBoost, LSTM, and SARIMAX models. Examined the effect of adding historical price features.
**Analysis:** Evaluated predictions using error metrics and examined model behavior through feature importance and SHAP.
The project explores how recent price history and external market indicators contribute to predictions.
**Tools:** Python, pandas, NumPy, scikit-learn, XGBoost, TensorFlow/Keras, statsmodels, Matplotlib, and SHAP.
**Business value:** Demonstrates predictive modeling for fuel-cost analysis and planning, while recognizing uncertainty
from market changes and the timing of data availability.
[View Project Notebook](https://github.com/madathumpadi/madathumpadi.github.io/blob/main/GasolinePricePrediction.ipynb)


### U.S. Family Credit Card Debt by Income and Age
How common is credit card debt among U.S. families, and how much do families with debt typically owe? This project uses survey weights
and all five imputed datasets from the Federal Reserve’s 2022 Survey of Consumer Finances to compare credit card debt by income and age.
**Key finding:** An estimated 45.22% of U.S. families carried credit card debt. Among families with debt, the weighted median balance
was $2,942 in 2025 dollars. By age, debt was most common among families whose reference person was 45–54, at 57%.
[View the Jupyter notebook](https://github.com/madathumpadi/madathumpadi.github.io/blob/main/U.S.%20Family%20Credit%20Card%20Debt.ipynb)


### Childcare Affordability Analysis
This project uses the National Database of Childcare Prices to compare U.S. childcare costs by age group and type of care. It also
examines how much of median household income families would need to spend on infant care.
**Key finding** — From 2008 to 2018, center-based childcare prices rose about 22%–23% across the age groups studied, while
inflation-adjusted median household income rose about 3%.
[View Project Notebook](https://github.com/madathumpadi/madathumpadi.github.io/blob/main/Childcare%20Affordability%20Analysis.ipynb)


### Movie Recommendation System
Built a hybrid recommender in Python using MovieLens data. Users enter a movie they like and receive a ranked list of
10 similar movies. 
**Method** — The recommender uses cosine similarity to compare user rating patterns and TF-IDF genre vectors. The final score
weights rating similarity at 70% and genre similarity at 30%. 
**Tools** — Python, pandas, scikit-learn, and SciPy.
[View Project Notebook](https://github.com/madathumpadi/madathumpadi.github.io/blob/main/Movie%20Recommendation%20System.ipynb)



### Kia and Hyundai Vehicle Theft Analysis
Used R to explore reported thefts of Kia and Hyundai vehicles and visualize patterns in the data.
[View Project Notebook](https://github.com/madathumpadi/madathumpadi.github.io/blob/main/Kia%20and%20Hyundai%20Vehicle%20Theft%20Analysis.ipynb)



### Student Mental Health Analysis
Analyzed survey responses from 101 students at International Islamic University Malaysia. The project explored mental health
patterns and compared logistic regression and random forest models for predicting self-reported depression from academic
and demographic characteristics.
**Key finding** — On the 21-student test set, random forest identified 6 of the 7 students who reported depression, while
logistic regression identified 4. Results are preliminary because the sample was small and came from a single university.
[View Project Notebook](https://github.com/madathumpadi/madathumpadi.github.io/blob/main/Student%20Mental%20Health%20Analysis.ipynb)



### Diabetes Prediction
Used 70,692 records from the 2015 Behavioral Risk Factor Surveillance System to examine how health behaviors,
health indicators, and demographic characteristics relate to reported diabetes status.
**Method** — Built a logistic regression model and used odds ratios to interpret associations between individual
predictors and diabetes status. Also evaluated a random forest model for comparison.
**Key finding** — The random forest showed little improvement over logistic regression in this analysis.
[View Project Notebook](https://github.com/madathumpadi/madathumpadi.github.io/blob/main/Diabetes%20Prediction.ipynb)


## Contact

[View my GitHub profile](https://github.com/madathumpadi)
