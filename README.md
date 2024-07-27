# Welcome! <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="40px">

## About Me

Hi there! I’m into data & analytics and always on the lookout for projects that bring value. I have a degree in Actuarial Science, which fuels my passion for numbers. Outside of work, I love to run, travel, and try my hand at cooking delicious meals.

-  [**LinkedIn**](https://www.linkedin.com/in/patricio-villanueva/)

## Languages and Tools

Here are some of the languages and tools I work with:

### Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=sql&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=white)

### Tools

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=for-the-badge&logo=apache-airflow&logoColor=white)
![PySpark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=for-the-badge&logo=apache-spark&logoColor=white)
![Airbyte](https://img.shields.io/badge/Airbyte-3723BC?style=for-the-badge&logo=airbyte&logoColor=white)
![Data Building Tool](https://img.shields.io/badge/DBT-FF694B?style=for-the-badge&logo=dbt&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google%20Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)


## Showcase Projects

### Predicting User Churn for Sparkify

- **Description:** This project focuses on building a supervised learning classification model to predict user churn for a music streaming service called Sparkify. By analyzing time-series data, the goal is to identify users likely to cancel their subscription, thereby enabling the service to take preventive measures.
- **Technologies:** Python, Spark Framework (version 2.4.4), Pandas, NumPy, PySpark, Plotly, OS, DateTime, Seaborn.
- **Highlights:** 
  - **Data Exploration and Cleaning:** Loaded and cleaned the dataset, removing rows with no user ID and converting timestamps to a human-readable format.
  - **Feature Engineering:** Created 8 features for the model to improve prediction accuracy.
  - **Modeling:** Compared three models—Random Forest (RF), Gradient Boosted Trees (GBM), and Supported Vector Machine (SVM). Selected the RF model after cross-validation and grid search fine-tuning.
  - **Performance:** Achieved an accuracy of about 82% and an F1 score of 78%, showing a 20% improvement over the baseline model.
  - **Scalability:** Designed the code using the Spark Framework to handle larger datasets with ease, allowing for easy refactoring and deployment on clusters.
  - **Improvement Potential:** Highlighted potential improvements by considering more features, domain knowledge, and larger sample sizes for better performance.

For more details, check out the [project repository](https://github.com/pato0301/sparkify_capstone_udacity).

### Starbucks Rewards Program Analysis

- **Description:** This project involves analyzing simulated data from the Starbucks rewards mobile app to understand customer behavior. Starbucks sends various offers through the app, ranging from advertisements to actual promotions like discounts or BOGO (buy one get one free). The task was to combine transaction, demographic, and offer data to determine which demographic groups respond best to different offer types. The data set used is a simplified version of the real Starbucks app, focusing on a single product instead of the actual variety offered by Starbucks.
- **Technologies:** Python, Jupyter Notebook (Anaconda), Pandas, NumPy, Math, JSON, Matplotlib, Seaborn, Scikit-learn, TensorFlow, Keras.
- **Highlights:**
  - **Data Analysis:** Integrated and analyzed transaction, demographic, and offer data to predict which offers generate deeper customer engagement.
  - **Problem Statement:** Aimed to predict which purchase offers would lead to higher customer engagement and usage of promotions.
  - **Implementation:** Utilized a combination of data processing and machine learning techniques to build a predictive model.
  - **File Descriptions:**
    - `Starbucks_Capstone_notebook.ipynb`: The code notebook with the full analysis.
    - `Starbucks Capstone Project Proposal.pdf`: The project proposal document.
    - `Data/`: Directory containing data files:
      - `Profile.json`: Customer profile data.
      - `Portfolio.json`: Offer portfolio data.
      - `Transcript.json`: Transaction and offer response data.
      - `Data.csv`: Cleaned data with combined information from the above JSON files.

You can view the full analysis in the [Medium post](#).

For more details, check out the [project repository](#).

<!-- ### Project 3 Name

- **Description:** A brief description of what the project does.
- **Technologies:** List of technologies used.
- **Highlights:** Key features or highlights of the project. -->