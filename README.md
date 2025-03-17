# Market-Basket-Analysis
Market Basket Analysis uses the FP-growth algorithm to analyze retail transaction data, uncovering frequent itemsets and generating association rules. Key metrics like support, confidence, and lift help identify product relationships, optimizing cross-selling, promotions, and product placement strategies.


## Project Overview
This project performs Market Basket Analysis on retail transaction data to uncover hidden patterns and insights about customer purchase behavior. The goal is to identify frequent itemsets, analyze associations between items, and derive actionable insights for retail strategies such as product recommendations, cross-selling, and promotions.

## Tools & Technologies Used
- **Programming Language**: Python
- **Libraries**: 
  - pandas (for data manipulation)
  - mlxtend (for frequent itemset mining and association rule generation)
- **Algorithms**: FP-growth for finding frequent itemsets and generating association rules.
- **Metrics**: Support, Confidence, Lift, Leverage, Conviction

## Key Features & Steps
1. **Data Preprocessing**: 
   - Converted transactional data into a format suitable for association rule mining using `TransactionEncoder` from mlxtend.
   - Cleaned and filtered data to ensure accuracy in analysis.

2. **Frequent Itemset Mining**:
   - Applied the FP-growth algorithm to find frequent itemsets with a minimum support threshold.
   - Filtered and analyzed the most and least frequent itemsets.

3. **Association Rule Mining**:
   - Generated association rules from the frequent itemsets with metrics such as confidence, lift, leverage, and conviction.
   - Identified strong associations between items like "whole milk," "yogurt," and "vegetables" to provide insights on customer buying patterns.

4. **Metrics Interpretation**:
   - Evaluated the strength of the association rules using metrics:
     - **Support**: Measures how often items are purchased together.
     - **Confidence**: Likelihood that an item is purchased when another is present.
     - **Lift**: Measures how much more likely items are to be purchased together than independently.
     - **Leverage**: Difference between observed and expected frequency.
     - **Conviction**: Measures how much more likely the consequent is purchased when the antecedent is present compared to when it’s absent.

5. **Outcome**:
   - Identified key items that are frequently purchased together.
   - Provided insights for businesses to optimize product placements, cross-selling, and promotional campaigns based on item associations.

## Impact
- The project provides valuable insights into customer purchasing behavior, helping businesses design more effective marketing strategies, improve inventory management, and enhance customer experience through personalized product recommendations and promotions.

## Getting Started
1. Clone the repository: 
   ```bash
   git clone https://github.com/your-username/market-basket-analysis.git
