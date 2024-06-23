## Equity in Healthcare: Women in Data Science Datathon 2024

### 1. Description
I participated in the WiDS Datathon 2024 to challenge myself with real-life data analysis. According to the information on the WiDS website, Gilead Sciences provided a comprehensive real-world dataset containing information about demographics, diagnosis and treatment options, and insurance details for patients diagnosed with breast cancer from 2015-2018. This dataset originated from Health Verity, one of the largest healthcare data ecosystems in the US, and was enriched with third-party geo-demographic data to provide insights into socioeconomic factors that may contribute to health equity. For this challenge, the dataset was further enriched with zip code level toxicology data from NASA/Columbia University.

The task was to predict if patients received a metastatic cancer diagnosis within 90 days of screening. Metastatic TNBC is considered the most aggressive form of TNBC and requires urgent treatment. Delays in diagnosis and treatment can have devastating effects. Differences in wait times for treatment are a good proxy for disparities in healthcare access. The primary goal of building these models was to detect relationships between patient demographics and the likelihood of receiving timely treatment. The secondary goal was to see if environmental hazards impact proper diagnosis and treatment.

To address these questions, I performed data cleaning and analysis. The dataset contained many missing values, so I compared two approaches: data imputation using machine learning techniques versus data removal and imputing only where the missing values constituted less than 50% of the records in the entire dataset. I found that while ML imputation introduced some noise, it yielded slightly better results. Next, I experimented with feeding the data into different types of Gradient Boosting Models, performing hyperparameter tuning, and comparing their metrics and scalability.

### 2. Next Steps
To further improve and understand the model, I plan to:

- Experiment with feature selection to identify the most significant variables.
- Inspect feature importances to understand which factors contribute most to the predictions.
- Analyze the results and explore possible relationships between demographics and timely diagnosis, and determine if environmental hazards impact proper diagnosis and treatment.

### 3. Lessons learned
Throughout this project, I gained several valuable insights and skills:

I learned how to inspect a dataset with more than 80 columns of numerical, categorical, and textual data, employing various types of plots including geoplots to better understand the data. I also identified correlated variables and designed new features based on the existing ones. Additionally, I gained experience in imputing data using machine learning techniques and tuning hyperparameters. Finally, I honed my ability to compare metrics to evaluate model performance.
