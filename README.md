# 🛒 Market-Basket-Analysis using FP-Growth and Apriori Algorithms

Market Basket Analysis is a powerful data mining technique used to uncover hidden patterns in customer purchasing behavior. This project uses both **FP-Growth** and **Apriori algorithms** to analyze retail transaction data, extract frequent itemsets, and generate association rules that help in driving **product recommendations**, **cross-selling**, **inventory planning**, and **marketing strategies**.

## 📊 Project Overview

This project performs Market Basket Analysis on transactional retail data to identify frequently co-purchased items and derive valuable association rules. The aim is to optimize business decisions such as product placements, promotions, and recommendations.

To ensure a comprehensive analysis, **both FP-Growth and Apriori algorithms** have been applied and compared based on performance and output. This comparative approach helps in understanding the scalability and efficiency of both algorithms in real-world scenarios.

## 🔧 Tools & Technologies Used

- **Programming Language**: Python  
- **Libraries**:
  - `pandas` – Data handling
  - `mlxtend` – Frequent itemset mining and association rule generation
  - `matplotlib / seaborn` – Data visualization
- **Algorithms**:
  - **FP-Growth Algorithm**
  - **Apriori Algorithm**
- **Evaluation Metrics**:
  - Support
  - Confidence
  - Lift
  - Leverage
  - Conviction
    
## 🚀 Key Features & Workflow

### 1️⃣ Data Preprocessing
- Loaded transactional data into a pandas DataFrame.
- Used `TransactionEncoder` to transform data into a binary matrix.
- Cleaned and structured data for accurate mining.

### 2️⃣ Frequent Itemset Generation
- Applied **FP-Growth** and **Apriori** algorithms to extract frequent itemsets based on minimum support.
- Compared the itemsets generated by both methods.

### 3️⃣ Association Rule Mining
- Generated association rules using `mlxtend.association_rules()` function.
- Analyzed rules using key metrics: **Support**, **Confidence**, **Lift**, **Leverage**, and **Conviction**.
- Identified key product associations like **whole milk**, **yogurt**, and **other vegetables**.

### 4️⃣ Metrics Interpretation
- **Support**: Frequency of itemset occurrence.
- **Confidence**: Probability of purchasing consequent given antecedent.
- **Lift**: Measures correlation strength between items.
- **Leverage**: Difference between actual and expected frequency.
- **Conviction**: Indicates the strength of implication in the absence of antecedent.

## ⚖️ Why Both FP-Growth and Apriori?

| Algorithm   | FP-Growth                                  | Apriori                                   |
|-------------|--------------------------------------------|--------------------------------------------|
| Method      | Tree-based mining                          | Iterative candidate generation             |
| Efficiency  | More scalable for large datasets           | Slower due to multiple database scans      |
| Memory Use  | Efficient due to compact FP-tree           | Higher memory usage for candidate sets     |
| Use Case    | Suitable for high-dimensional data         | Useful for small to medium datasets        |

👉 **Reason for Dual Use**:  
To compare how each algorithm performs in terms of speed, accuracy, and usability across different dataset sizes. FP-Growth is efficient, while Apriori provides interpretability in small datasets — making both essential for a thorough understanding of association rule mining.

## 💡 Impact

- Uncovered hidden purchase behavior patterns for better **recommendation systems**.
- Enabled insights for **cross-selling** opportunities and **promotional strategies**.
- Provided a foundation for **inventory optimization** and **customer-centric retail planning**.

## Getting Started
1. Clone the repository: 
   ```bash
   git clone https://github.com/Aakanksha160/Market-Basket-Analysis.git
