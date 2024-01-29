# Market-Basket-Analysis with apriori algorithm and association rules
## Overview
This project performs Market Basket Analysis using the Apriori algorithm to discover associations and patterns in grocery sales data. Market Basket Analysis is a technique widely used in retail and e-commerce to understand customer purchasing behavior and optimize product placement.

## Code Structure
Data Loading and Cleansing:

Load the grocery sales data and initiate the preliminary data cleaning process.
Change 'Member_number' to a string format and convert 'Date' to datetime.
Distinct Transactions:

Introduce a 'uniqueTransaction' column to organize items purchased by each customer on a daily basis.
Tabulation (Basket Formation):

Generate a cross-tabulation ('basket') to illustrate the occurrence of items in each distinct transaction.
Construct a binary-encoded DataFrame ('apriori_df').
Apriori Algorithm and Association Rules:

Utilize the Apriori algorithm to produce frequent itemsets.
Implement association rules, with a focus on evaluating using Zhang's metric.
Visualization with Heatmap:

Represent product associations visually through a heatmap.
Analyze the heatmap to comprehend prevalent itemsets.
Visualization of Positive Associations:

Examine pairs exhibiting a positive Zhang's metric to emphasize positive associations.

## Visualization
Create a heatmap to visualize product associations, considering both positive and negative Zhang's metric values. Positive values indicate a positive association, while negative values indicate the opposite.

## Conclusion
Market Basket Analysis yields valuable insights into customer purchasing patterns, enabling businesses to optimize product placement, cross-selling strategies, and promotional efforts.

## Future Endeavors:
Explore interactive visualizations to enrich user exploration experiences.
Adjust parameters for the Apriori algorithm to observe their influence on outcomes.
Conduct additional data exploration for a more profound understanding of customer behavior.
