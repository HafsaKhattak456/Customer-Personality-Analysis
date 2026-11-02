# Customer Personality Analysis

An exploratory data analysis project focused on customer behaviour, purchasing patterns, spending segmentation, and marketing campaign responses using Python and Pandas.

## Project Overview

This project explores customer personality and purchasing behaviour through data cleaning, preprocessing, exploratory data analysis (EDA), and visualization.

The objective is to identify meaningful patterns in customer spending, understand shopping channel preferences, explore demographic differences, and derive actionable business insights.

## Dataset

- **Dataset:** Customer Personality Analysis
- **Source:** [Kaggle Dataset](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis)
- **Original Records:** 2,240 customers
- **Original Features:** 29 columns

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Project Workflow

1. Data loading and initial exploration
2. Data quality investigation
3. Missing-value handling and data preprocessing
4. Outlier investigation and data validation
5. Exploratory data analysis
6. Customer spending segmentation
7. Data visualization
8. Business insights and recommendations

## Data Cleaning and Preprocessing

- Investigated missing income values and applied median imputation.
- Checked for duplicate records and unique customer IDs.
- Investigated unusual marital-status categories.
- Flagged unusual birth years for review.
- Identified income outliers using the IQR method without automatically deleting them.
- Converted customer registration dates into datetime format.
- Created additional analytical features, including total spending, age groups, and spending segments.

## Key Business Findings

- Wines contributed approximately 50.17% of total recorded product spending.
- Wines and meat products together accounted for approximately 77.73% of recorded spending.
- Physical stores represented the largest shopping channel, with 46.18% of recorded purchases.
- Seniors had the highest average spending among the analyzed age groups.
- High-spending customers also had the highest average income.
- The latest marketing campaign had an acceptance rate of approximately 14.91%.

## Visualizations

The project includes charts exploring:

- Total spending by product category
- Purchases by shopping channel
- Customer distribution by spending segment
- Average spending by age group
- Marketing campaign response
- Average income by spending segment

## Repository Structure

```text
customer-personality-analysis/
│
├── README.md
├── requirements.txt
├── customer_personality_analysis.ipynb
├── marketing_campaign.csv
└── output/
```

## How to Run

1. Clone or download the repository.
2. Install dependencies:

   `pip install -r requirements.txt`

3. Place the original dataset inside the `data/` directory.
4. Open the notebook inside `notebooks/`.
5. Run the cells sequentially.

## Important Notes and Limitations

- Median imputation was used for missing income values; these are estimated values, not actual customer incomes.
- Unusual marital-status labels were grouped as `Unknown` as a project-specific assumption.
- Income outliers and unusual birth years were flagged rather than automatically removed.
- Age was estimated using 2014 as the reference year.
- Spending amounts do not represent profit.
- The analysis is descriptive and does not establish causation.

## Author

**Hafsa Khattak**

[GitHub Profile](https://github.com/HafsaKhattak456)

This is a personal learning and portfolio project demonstrating practical data cleaning, exploratory analysis, and data visualization skills.