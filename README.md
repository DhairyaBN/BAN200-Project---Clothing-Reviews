
# Predicting Positive Reception of Women’s Clothing Categories by Age Group Using E-Commerce Reviews

## Course Information
- **Course Name:** [Insert Course Name]
- **Course Code:** [Insert Course Code]
- **Professor:** [Insert Professor's Full Name]
- **Institution:** [Insert Institution Name]

---

## Project Title
**Predicting Positive Reception of Women’s Clothing Categories by Age Group Using E-Commerce Reviews**

---

## Group Members
- Dhairya Negandhi
- Priyanka
- Sarvagya Gupta
- Balraj Goud Oruganti
- Manish Venkatesh
- Praveenkumar Ramesh

---

## Project Overview
This project aims to analyze customer reviews from an e-commerce women’s clothing retailer to identify **which product categories and styles are most positively received by different age groups**. The objective is to generate actionable insights that can inform:
- Inventory management decisions
- Targeted marketing strategies
- Personalized e-commerce recommendations

Ultimately, the project seeks to develop a **predictive model** that estimates the likelihood of a product recommendation based on customer demographics, review sentiment, and product attributes.

---

## Dataset Description
The dataset used for this analysis is publicly available on Kaggle:

- **Dataset Name:** Women’s Clothing E-Commerce Reviews
- **Source:** [Kaggle Dataset Link](https://www.kaggle.com/datasets/nicapotato/womens-ecommerce-clothing-reviews)
- **Size:** 23,486 reviews
- **Key Variables:**
  - **Clothing ID:** Unique identifier for each clothing item
  - **Age:** Age of the reviewer (numeric)
  - **Title:** Short text summarizing the review
  - **Review Text:** Full customer review text
  - **Rating:** Customer rating (1–5 scale)
  - **Recommended IND:** Binary indicator (1 = recommended, 0 = not recommended)
  - **Positive Feedback Count:** Number of customers who found the review helpful
  - **Division Name, Department Name, Class Name:** Product categorization attributes

---

## Methodology
1. **Data Cleaning:**
   - Removal of duplicate entries and missing reviews
   - Creation of age group bins: Under 30, 30–50, 50+

2. **Exploratory Data Analysis (EDA):**
   - Distribution of ratings across age groups
   - Recommendation rates per category and demographic
   - Visualization of trends in customer feedback

3. **Text Preprocessing:**
   - Lowercasing text, punctuation removal, whitespace trimming

4. **Sentiment Analysis:**
   - Keyword-based sentiment scoring to evaluate review polarity

5. **Predictive Modeling (Planned):**
   - Logistic regression or decision tree model to predict recommendation likelihood
   - Features include age group, sentiment score, and product category

---

## Tools and Technologies
- **Programming Language:** Python (Pandas, NumPy, Matplotlib)
- **Data Source:** Kaggle dataset (linked above)
- **Version Control:** GitHub (public repository for scripts and documentation)

---

## Project Deliverables
- Cleaned dataset saved as `Womens_Clothing_Cleaned.csv`
- Data exploration and sentiment analysis scripts
- Visualizations highlighting customer preferences by age group
- Predictive model estimating recommendation likelihood (final stage)
- Final report summarizing methodology, findings, and business recommendations

---

## Repository Structure
```
├── data
│   ├── Womens Clothing E-Commerce Reviews 2.csv
│   └── Womens_Clothing_Cleaned.csv
├── scripts
│   ├── data_cleaning_and_analysis.py
│   ├── eda_and_sentiment_analysis.py
│   └── predictive_model.py (planned)
├── visuals
│   ├── rating_distribution.png
│   ├── recommendation_by_age.png
│   └── sentiment_by_age.png
├── README.md
└── final_report.docx
```

---

## License
This project is intended for **academic purposes only**. The dataset is publicly available and subject to Kaggle's data-sharing policies.
