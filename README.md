# cab-investment-analysis
# Cab Industry Investment Analysis Portfolio
**Author:** Cielo  
**Project Objective:** Advise a private equity firm on whether to invest in Yellow Cab or Pink Cab based on multi-source historical datasets.


##  Steps Followed in My Analysis
1. **Data Integration:** Unified separate transaction, customer demographic, and city log files using relational database joins (`pd.merge`).
2. **Data Cleaning & Quality Check:** Audited the dataset for duplicates, shape, and missing values. Handled string-formatting issues to convert population data into usable numbers.
3. **Feature Engineering:** Calculated individual trip `Profit` by subtracting `Cost of Trip` from `Price Charged`. Grouped customer data into generational age bins and economic income brackets.
4. **Loyalty Metrics Mapping:** Aggregated transaction frequencies per customer to calculate brand retention thresholds for repeat riders (>= 5 and >= 10 trips).


## Core Data Insights Uncovered

### 1. Market Scale vs. Efficiency
While Pink Cab has a lower operating cost, it lacks pricing power. Yellow Cab dominates both total gross volume and maintains a significantly higher **Average Profit per Ride**.

### 2. Demographic Capture
Yellow Cab completely dominates the "High" and "Very High" income brackets. These premium customers are less sensitive to price changes, protecting the company's margins during economic downturns.

### 3. Brand Retention & Stickiness
When filtering for power users (customers with >= 10 rides), Yellow Cab holds a massive advantage. Pink Cab is primarily a utility for one-time users, whereas Yellow Cab builds long-term customer lifetime value (LTV).


##  Final Strategic Investment Verdict
**Recommendation: Allocate capital investment entirely to Yellow Cab.**

Investing in Pink Cab is a high-risk gamble on a low-margin competitor struggling for scale. Yellow Cab represents a highly efficient, premium, sticky ecosystem that scales cleanly, owns high-value customer segments, and delivers superior, predictable profits.
