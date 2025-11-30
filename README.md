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

- README.md
- requirements.txt         # Danh sách các thư viện Python cần thiết
- .gitignore               # Các file/thư mục cần bỏ qua bởi Git
- src                      # Thư mục Mã nguồn Chính
    + crawler              # 1. Thu thập dữ liệu (Web Scraping)
    + preprocessing        # 2. Tiền xử lý dữ liệu và Phân tích Khám phá (EDA)
    + mongo_db             # 3. Kết nối và Quản lý Cơ sở dữ liệu MongoDB
    + hypothesis_testing   # 4. Kiểm định Giả thuyết Thống kê
    + model                # 5. Huấn luyện Mô hình Học máy/Dự đoán
