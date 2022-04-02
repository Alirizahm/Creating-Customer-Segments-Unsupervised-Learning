## Creating-Customer-Segments-Unsupervised-Learning

Author's : Aliriza Hamonangan Matondang

## Introduction
We will analyze a dataset containing data on various customers annual spending amounts (reported in monetary units) of diverse product categories for internal structure

The goals of the project are :
- To find the best clusters of the dataset
- To find the characteristic of the the best clusters
- Give the recommendation from the best clusters

## Data Information
- Fresh: annual spending (m.u.) on fresh products (Continuous);
- Milk: annual spending (m.u.) on milk products (Continuous);
- Grocery: annual spending (m.u.) on grocery products (Continuous);
- Frozen: annual spending (m.u.) on frozen products (Continuous);
- Detergents_Paper: annual spending (m.u.) on detergents and paper products (Continuous);
- Delicatessen: annual spending (m.u.) on and delicatessen products (Continuous);
- Channel: {Hotel/Restaurant/Cafe - 1, Retail - 2} (Nominal)
- Region: {Lisbon - 1, Oporto - 2, or Other - 3} (Nominal)

## Steps
- Data Cleaning
- Exploratory Data Analysis
- Data Preprocessing
- Modeling (PCA, Dimensionality Reduction, KMeans)

## The Results
<img width="535" alt="Screenshot 2022-04-02 213623" src="https://user-images.githubusercontent.com/92624520/161388155-49f82728-b22f-40b6-bac5-d58a346b38f2.png">

Findings :

Clusters 0 : has high annual spending on milk, grocery, Fresh, and detergents_Paper (retail goods)
Clusters 1 : has high annual spending on Fresh, grocery, froze, and Milk (Hospitality goods)


![download](https://user-images.githubusercontent.com/92624520/161388015-d95e7c69-8e61-4878-a2ec-3060140d2503.png)

Findings:

- Here is the plot of clusters distribution pattern
- The clusters is not quiet gathering well
- But i think this clusters is well separated since we only have 2 clusters
- If you want to gathering well the cluster you can use another method such as T-SNE

![download (1)](https://user-images.githubusercontent.com/92624520/161388062-0bef9332-46c6-4807-9315-876079338887.png)

Findings :

- Such as the analyze that we have done it, clusters 1 has higher annual spending on Fresh and Frozen then Clusters 0 (Hospitality) and Clusters 1 has higher annual spending on Fresh and Frozen then Clusters 0 (Retail)
- Clusters 1 has more annual spending then Clusters 0

## Conclusion

- The best clusters of the dataset is 2 Clusters
- The characteristic of the the best Clusters:
- Clusters 0 : has high annual spending on milk, grocery, Fresh, and detergents_Paper (retail goods)
- Clusters 1 has higher annual spending on Fresh and Frozen then Clusters 0

## Recommendation

- From the characteristics of the clusters, we can stock products according to the needs of each clusters
- We can create warehouses with standards that match product characteristics in clusters near the clusters area to reduce operational costs
- We can do the marketing program based on the characteristics of the clusters


## Note
Please contact me if you guys have any suggest or anything. Im newbie :))) 🤖
