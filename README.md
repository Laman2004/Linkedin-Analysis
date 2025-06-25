# LinkedIn Profile Analysis (with Python)
This project was developed during the industrial internship as part of the Faculty of Information Technologies and Management at Azerbaijan State Oil and Industry University. The internship was completed at Codemarketing LLC, where the focus was on real-world data analysis using LinkedIn user profile data.

###  Project Objective
The main goal of the project was to analyze user profile data obtained from the LinkedIn platform, including:

Grouping data by education levels, experience, and location

Cleaning and structuring real-world datasets

Detecting and handling outliers

Building simple models and performing data transformations

Visualizing insights using charts and statistical methods

### Tools & Technologies
Python – main programming language

Jupyter Notebook – for development and presentation

Pandas / NumPy – data manipulation and processing

Matplotlib / Seaborn – for visualizations

Scikit-learn (Sklearn) – for preprocessing, scaling, and outlier detection

### Dataset Information
The data was sourced from Kaggle’s public dataset on LinkedIn user profiles and includes fields such as:

timestamp, id, name – time and identification

position, experience – job-related information

education, educations_details – educational background

following, recommendations_count – engagement and networking

country_code, region, city, current_company:name – geographic and professional details

### Data Cleaning Highlights
Missing values were handled using mean, mode, and forward/backward fill

city and region columns were filled contextually based on country_code

education values were standardized into three categories: BA, MS, PhD using a custom function

Outliers were detected using Z-score and IQR methods

### Analysis & Visualizations
Exploratory Data Analysis (EDA):
Top countries and regions by profile count were identified

Bar charts and heatmaps showed trends in following and recommendations

Boxplots revealed outliers in numeric features

Grouped bar charts showed average following by education level and region

### Key Insights
Users with MS and PhD degrees follow more profiles on average

Most users are concentrated in EU and AS regions

Correlation between following and recommendations_count was weak (≈ 0.02)

Outliers significantly impacted some numeric features

### Technical Skills Gained
Through this project, the following skills were developed and applied:

Data wrangling with real datasets

Proficiency in Python for data analysis

Experience with EDA, feature engineering, and model preparation

Visualization and interpretation of analytical results


