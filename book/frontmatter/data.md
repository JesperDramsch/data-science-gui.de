# Data

The original data is collected in {cite:ts}`Kelley`

Modifications were made by {cite:ts}`Geron`

made available under the CC0 license on [Kaggle](https://www.kaggle.com/camnugent/california-housing-prices), with the following modifications from the original:


- 207 values were randomly removed from the total_bedrooms column, so we can discuss what to do with missing data.

- An additional categorical attribute called ocean_proximity was added, indicating (very roughly) whether each block group is near the ocean, near the Bay area, inland or on an island. This allows discussing what to do with categorical data.


```{bibliography}
:filter: docname in docnames
```