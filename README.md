Predicting Positive Reception of Women’s Clothing Categories by Age Group Using E-Commerce Reviews

Course Information
Course Name: Sentiment Analysis and Text Mining
Course Code: BAN200NAA
Professor: William Dick
Institution: Seneca Polytechnic / Business Analytics / Summer 2025

Group Members
Dhairya Negandhi
Priyanka
Sarvagya Gupta
Balraj Goud Oruganti
Manish Venkatesh
Praveenkumar Ramesh

Project Overview
This project aims to analyze customer reviews from an e-commerce women’s clothing retailer to identify which product categories and styles are most positively received by different age groups. The objective is to generate actionable insights that can inform:

- Inventory management decisions
- Targeted marketing strategies
- Personalized e-commerce recommendations

Ultimately, the project seeks to develop a predictive model that estimates the likelihood of a product recommendation based on customer demographics, review sentiment, and product attributes.

Dataset Description
The dataset used for this analysis is publicly available on Kaggle:

Dataset Name: Women’s Clothing E-Commerce Reviews
Source: Kaggle 
Size: 23,486 reviews

Key Variables:

Clothing ID: Unique identifier for each clothing item
Age: Age of the reviewer (numeric)
Title: Short text summarizing the review
Review Text: Full customer review text
Rating: Customer rating (1–5 scale)
Recommended IND: Binary indicator (1 = recommended, 0 = not recommended)
Positive Feedback Count: Number of customers who found the review helpful
Division Name, Department Name, Class Name: Product categorization attributes

Methodology

Data Cleaning:

Removal of duplicate entries and missing reviews
Creation of age group bins: Under 30, 30–50, 50+

Exploratory Data Analysis (EDA):

Distribution of ratings across age groups
Recommendation rates per category and demographic
Visualization of trends in customer feedback

Text Preprocessing:

Lowercasing text, punctuation removal, whitespace trimming

Sentiment Analysis:

Keyword-based sentiment scoring to evaluate review polarity

Predictive Modeling (Planned):

Logistic regression or decision tree model to predict recommendation likelihood
Features include age group, sentiment score, and product category


