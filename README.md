# Book Pricing & Rating Analysis

## Project Overview

This project demonstrates an end-to-end Data Science workflow using real-world web data. The dataset was collected through web scraping from the BooksToScrape website and transformed into actionable business insights through data cleaning, exploratory data analysis, machine learning, and Power BI dashboarding.

The objective was to analyze book pricing patterns, rating behavior, and category performance while predicting whether a book would receive a good rating.

---

## Project Objectives

- Collect real-world book data using web scraping.
- Clean and preprocess raw data for analysis.
- Perform Exploratory Data Analysis (EDA) to identify trends and patterns.
- Build a Machine Learning model to predict good-rated books.
- Create an interactive Power BI dashboard for business insights.
- Generate recommendations based on data-driven findings.

---

## Dataset Information

**Source:** BooksToScrape

**Records Collected:** 1,000+

### Features Collected

- Title
- Price
- Rating
- Category
- Product URL

### Features Engineered

- Price_Band
- Rating_Category
- Title_Length
- Category_Code
- Target Variable

---

## Technologies Used

### Programming & Analysis

- Python
- SQL
- Pandas
- NumPy
- Matplotlib
- Seaborn

### Web Scraping

- Requests
- BeautifulSoup

### Machine Learning

- Scikit-learn
- Logistic Regression

### Visualization

- Power BI

---

## Project Workflow

Web Scraping → Data Cleaning → Feature Engineering → Exploratory Data Analysis → Machine Learning → Power BI Dashboard → Business Insights

---

## Key Findings

- Total Books Analyzed: **1,000**
- Average Rating: **2.92**
- Average Price: **35.07**
- Good Rated Books: **37.5%**
- Price-Rating Correlation: **0.028**
- Total Categories: **50**
- Logistic Regression Accuracy: **51.5%**

---

## Exploratory Data Analysis Highlights

### Rating Analysis

- Most books received ratings between 2 and 4.
- Rating 1 was the most common rating.

### Category Analysis

**Top Performing Categories:**

- Adult Fiction
- Erotica
- Novels

**Lowest Performing Categories:**

- Crime
- Psychology
- Parenting

### Price Analysis

- Most books belonged to Medium and High price bands.
- Higher-priced books did not necessarily receive higher ratings.

### Correlation Analysis

- Price showed almost no relationship with ratings.
- Title length also had negligible impact on ratings.

---

## Machine Learning Model

### Model Used

**Logistic Regression**

### Prediction Goal

Predict whether a book would be classified as Good Rated or Not Good Rated.

### Features Used

- Price
- Title Length
- Category Code

### Model Performance

- Accuracy: **51.5%**
- Precision: **42%**
- Recall: **53%**

### Key Observation

The model achieved moderate performance because the dataset lacked strong predictive features such as review counts, author popularity, customer engagement, and sales metrics.

---

## Power BI Dashboard

The project includes a 3-page interactive Power BI dashboard.

### Page 1: Summary Dashboard

- Total Books
- Average Rating
- Average Price
- Good Rating %
- Rating Distribution
- Price Band Distribution
- Price vs Rating Analysis

### Page 2: Category Insights

- Top 10 Categories by Rating
- Bottom 10 Categories by Rating
- Number of Books by Category
- Price Band vs Average Rating
- Rating Category Breakdown

### Page 3: Model Insights

- Model Accuracy
- Confusion Matrix
- Classification Summary
- Feature Importance Explanation
- Machine Learning Insights

---

## Business Recommendations

- Focus on high-performing categories such as Adult Fiction and Novels.
- Improve content quality within low-performing categories.
- Do not rely on pricing alone to improve customer satisfaction.
- Collect richer behavioral data for stronger predictive modeling.
- Use machine learning as a decision-support tool rather than a standalone predictor.

---

## Conclusion

This project successfully demonstrates an end-to-end Data Science workflow from web scraping to business intelligence. The analysis revealed that category has a stronger influence on ratings than price, while machine learning showed that predicting book ratings requires richer and more informative features.

The project highlights the ability to transform raw web data into meaningful insights and interactive dashboards for data-driven decision-making.
