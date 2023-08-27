# Flight Food & Beverage Experience Analysis

This repository contains an analysis of passenger feedback data to improve in-flight food and beverage experiences. The analysis involves exploratory data analysis (EDA), data visualization, natural language processing (NLP), and keyword extraction techniques. The goal is to uncover insights and pain points related to the food and beverage offerings during flights.

## Problem Statement

Passenger satisfaction with in-flight food and beverage experiences is crucial for airlines. This project aims to analyze passenger feedback data to identify pain points and areas for improvement in food and beverage services. The analysis focuses on identifying common complaints, preferences, and opportunities for enhancing the overall dining experience during flights.

## What We Did

1. **Exploratory Data Analysis (EDA):** We performed EDA to understand the overall trends and patterns in the dataset. This involved visualizing data, understanding distributions, and identifying key variables.

2. **Data Preprocessing:** Multiple datasets were joined and preprocessed to create a comprehensive data source for analysis.

3. **Natural Language Processing (NLP):** NLP techniques were utilized to extract insights from the text data. This included sentiment analysis, keyword extraction, and identifying frequent phrases and terms.

4. **Keyword Extraction:** We used techniques like TF-IDF vectorization and cosine similarity to extract keywords from passenger comments. This helped identify major pain points and common themes related to food and beverage experiences.

## Files in the Repository

- **Notebook:** The Jupyter Notebook (`flight_food_beverage_analysis.ipynb`) contains the code, analysis, and visualizations performed throughout the project.

- **Dataset:** The dataset used for analysis (`passenger_feedback.csv`) contains passenger comments and relevant information related to food and beverage experiences during flights.

- **PDF Report:** A detailed report summarizing the analysis, findings, and recommendations is available as a PDF (`flight_food_beverage_report.pdf`).

## Required Modules and Dependencies

The following Python libraries were used for this analysis:

- numpy
- pandas
- matplotlib
- seaborn
- textblob
- wordcloud
- nltk
- spacy
- rake_nltk
- scikit-learn

Please ensure you have these libraries installed to execute the code and reproduce the analysis.

## Next Steps

Due to limitations in data availability, the analysis primarily focuses on the provided dataset. However, to further enhance insights, obtaining a larger dataset spanning multiple summer months is recommended. This would provide a more comprehensive view of seasonal variations in passenger preferences.

Additionally, for better performance in TF-IDF vectorization and cosine similarity, experimenting with hyperparameters and considering advanced NLP techniques could yield more accurate results.

## Conclusion

The analysis of passenger feedback data has identified key pain points related to in-flight food and beverage experiences. The project highlights the importance of addressing these pain points to enhance passenger satisfaction and improve overall flight experiences.

For a detailed overview, refer to the [PDF Report](flight_food_beverage_report.pdf).

