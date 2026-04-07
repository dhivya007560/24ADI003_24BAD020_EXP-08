# 24ADI003_24BAD020_EXP-08

SCENARIO 1 – ASSOCIATION RULE MINING USING APRIORI ALGORITHM


Problem Statement:
Identify frequent itemsets and generate association rules from transactional data using the Apriori algorithm.


Dataset (Kaggle – Public):
Market Basket Dataset / Grocery Dataset Example: https://www.kaggle.com/datasets/heeraldedhia/groceries-dataset

Discription of the code:
Association Rule Mining is performed using the Apriori algorithm to identify relationships between items in transactional data. The dataset consists of customer transactions containing items purchased together. The data is preprocessed by converting transactions into a structured format suitable for analysis. The Apriori algorithm is then applied to generate frequent itemsets based on a minimum support threshold. From these itemsets, association rules are derived using metrics such as confidence and lift. These rules help in understanding how items are related to each other. For example, if customers frequently buy milk along with bread, it indicates a strong association between these items. The results are evaluated using support, confidence, and lift values. Visualizations such as bar charts of frequent itemsets, support versus confidence plots, and network graphs are used to interpret the relationships effectively. This approach is widely applicable in market basket analysis, recommendation systems, and sales strategy optimization.





SCENARIO 2 – DIMENSIONALITY REDUCTION USING PCA


Problem Statement:
Reduce high-dimensional data into lower dimensions while preserving maximum variance using PCA.


Dataset (Same / Alternative Dataset):
Any dataset with multiple numerical features
Example: Iris Dataset / Wine Dataset

Discription of the code:
Principal Component Analysis (PCA) is used to reduce the dimensionality of a dataset while preserving the maximum possible variance. A dataset with multiple numerical features is selected and preprocessed by handling missing values and standardizing the features. PCA is applied to transform the original features into a new set of uncorrelated variables called principal components. These components are ranked based on the amount of variance they capture. The explained variance ratio is computed to understand the contribution of each component, and cumulative variance is used to determine the optimal number of components required. The dataset is then reduced to two dimensions for visualization purposes. Graphical representations such as scree plots, cumulative variance plots, and 2D scatter plots are used to analyze the results. PCA helps in simplifying complex datasets, reducing computational cost, and improving model performance while retaining important information.




Overall, this experiment demonstrates how association rule learning can uncover hidden relationships in transactional data, while PCA helps in reducing data complexity and enhancing interpretability. Both techniques play a significant role in real-world applications such as customer behavior analysis, recommendation systems, and data preprocessing for machine learning models.
Discription of the code:

