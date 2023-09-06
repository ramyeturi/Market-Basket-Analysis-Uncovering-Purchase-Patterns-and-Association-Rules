# Title: Market Basket Analysis of Stationary and Health & Beauty Aids Departments: Uncovering Purchase Patterns and Association Rules

Abstract:

This project delves into a comprehensive market basket analysis of transactions made at a store's Stationary and Health & Beauty Aids departments. Leveraging a dataset containing 200,000 transactions spanning a three-month period, our objective is to identify meaningful associations between products purchased by customers. The dataset comprises two columns: Transaction ID and Product, encompassing 17 different products.

Summary:

Data Transformation: We begin by transforming the dataset into a transactional format, creating a new file named "groupxxtransactions01.csv" (where "xx" represents the group number). Each row now represents a single transaction, with "True" indicating items present in the transaction and "False" representing items not purchased.

Frequent Itemset Identification: Using a minimum support threshold of 1%, we identify frequent itemsets, revealing the combinations of products frequently purchased together. We determine the total number of frequent itemsets.

Association Rules Generation: Our analysis generates association rules with a minimum confidence of 10%, shedding light on the relationships between items. We quantify the total number of generated rules.

Highest Lift Rules: We pinpoint the association rules with the highest lift values, showcasing their significance in revealing purchase patterns. We provide a detailed breakdown of how lift is calculated for one of these high-lift rules.

Leverage and Conviction Calculation: For the same rule with the highest lift, we illustrate the computation of leverage and conviction, offering insights into their implications.

Interpretation of High-Value Rules: We interpret and discuss the top 5 rules based on different criteria—highest confidence, highest lift, highest leverage, and highest conviction. We explore the implications, potential surprises, and redundancy within these rules while assessing their utility.

Comparison of Metrics: We compare the various evaluation metrics (confidence, lift, leverage, conviction) to assess their suitability for this dataset. We provide insights into the strengths and limitations of each metric.

Strategic Implications: We conclude by exploring how the results of this market basket analysis can inform strategic planning for the Stationary and Health & Beauty Aids departments. We encourage innovative thinking on how the discovered associations can guide inventory management, marketing strategies, and customer engagement.

This project aims to uncover valuable insights into customer behavior, helping the store's management make data-driven decisions to enhance product placement, promotions, and overall shopping experiences in these departments.




