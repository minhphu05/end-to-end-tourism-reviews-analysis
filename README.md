# DS304 - Travel Review Sentiment Analysis

![](/resources/traveloka-head.jpg)

![](/resources/agoda-head.jpg)

## Project Overview

This project collects travel service reviews from Agoda and Traveloka platforms, applies pretrained models and manual annotation methods to label sentiment, and then trains machine learning models to classify review sentiments. The goal is to analyze customer opinions on travel services to support better business decisions.

---

## Features

- **Data Collection:** Web scraping of reviews and service details from Agoda and Traveloka.
- **Sentiment Labeling:** Combination of pretrained NLP models and manual labeling for accurate sentiment tags.
- **Data Preprocessing:** Cleaning and exploratory data analysis of Vietnamese travel reviews.
- **Model Training:** Applying machine learning algorithms for sentiment classification.
- **Database Integration:** Storing and querying review data using MongoDB.

---

## Project Structure

- README.md  
- requirements.txt         : List of required Python libraries  
- .gitignore               : Files/folders to be ignored by Git  
- src                      : Main source code folder  
    + crawler              : Data collection (Web Scraping)  
    + preprocessing        : Data preprocessing and Exploratory Data Analysis (EDA)  
    + mongo_db             : MongoDB connection and management  
    + hypothesis_testing   : Statistical hypothesis testing  
    + model                : Machine learning model training and prediction  

