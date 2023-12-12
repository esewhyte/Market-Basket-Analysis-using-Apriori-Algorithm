# Market-Basket-Analysis-using-Apriori-Algorithm
This script uses the Apriori algorithm to analyze a grocery sales dataset to discover associations between different products.

Steps:
     Data preparation: Load and clean the data, creating a column for single transactions per customer per day.
     Basket creation: Generate a cross-tabulation (basket) to represent the frequency of items in each transaction.
     Apriori algorithm: Apply the Apriori algorithm to discover frequent itemsets.
     Association rules: Analyze association rules using Zhang's metric for evaluation.
     Visualization: Visualize product associations using heatmaps.

Benefits:
         Heatmaps: Provide clear and intuitive visualizations of product associations.
         Zhang's metric: Offers a comprehensive evaluation of association rules, considering the negative values.

Outcome:
        This script helps discover hidden patterns in customer purchase behavior, enabling better product placement, marketing strategies, and inventory management.
