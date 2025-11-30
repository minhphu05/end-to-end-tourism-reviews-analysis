# DS304 - Travel Review Sentiment Analysis

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

├── README.md
├── requirements.txt
├── .gitignore
├── src
│ ├── crawler
│ │ ├── Agoda_Reviews_Scraping.ipynb
│ │ ├── Details_Scraping.ipynb
│ │ ├── Pages_Collection.ipynb
│ │ ├── Traveloka_Link_BasicDetails_Scraping.ipynb
│ │ ├── auxilliary_function
│ │ │ ├── metadata.py
│ │ │ └── setup_module.py
│ │ ├── crawl_function
│ │ ├── Agoda_Details_Scraping_Modules.py
│ │ └── Agoda_Reviews_Scraping_Modules.py
│ ├── hypothesis_testing
│ │ ├── Hypothesis_Testing.ipynb
│ │ └── Hypothesis_Testing_.ipynb
│ ├── model
│ │ ├── Model_Training.ipynb
│ │ └── Training_Model_Module.py
│ ├── mongo_db
│ │ ├── db_agoda.py
│ │ └── db_traveloka.py
│ └── preprocessing
│ ├── Exploratory_Data_Analysis.ipynb
│ ├── Preprocessing.ipynb
│ ├── Vietnamese_Reviews_Preprocessing.ipynb
│ └── preprocessing_pipeline.ipynb

