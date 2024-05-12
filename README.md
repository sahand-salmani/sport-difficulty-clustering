# Sports Difficulty Analysis

## Overview

This project aims to analyze the difficulty of various sports based on multiple metrics such as endurance, strength, power, speed, agility, flexibility, nerve, durability, hand-eye coordination, and analytical aptitude. The dataset contains information about each sport's difficulty across these metrics.

## Steps Taken

1. **Correlation Analysis**: 
   - To understand the relationships between different metrics, a correlation analysis was conducted. Metrics showing a correlation coefficient greater than 0.6 were identified to explore potential patterns.

2. **Data Distribution Visualization**: 
   - Histograms were plotted for each metric to visualize their distribution and understand the range and spread of values.

3. **Determining Optimal Clusters**: 
   - The Elbow Method was employed to determine the optimal number of clusters for the KMeans clustering algorithm. This helped in identifying the appropriate number of clusters for grouping similar sports based on their difficulty metrics.

4. **Dimensionality Reduction with t-SNE**: 
   - The t-distributed Stochastic Neighbor Embedding (t-SNE) technique was used to reduce the dimensionality of the data to 2 dimensions for visualization purposes while preserving the structure of the data as much as possible.

5. **KMeans Clustering**:
   - KMeans clustering was applied to group sports into clusters based on their difficulty metrics. The number of clusters was determined using the Elbow Method.

6. **Visualization of Clusters**: 
   - The resulting clusters were visualized in 2D using t-SNE components. Each cluster was assigned a unique color for easy identification.

## Conclusion

Through this analysis, we were able to gain insights into the difficulty levels of various sports based on a range of metrics. The clustering helped in identifying groups of sports with similar characteristics, which can be valuable for various stakeholders such as athletes, coaches, and sports enthusiasts in understanding the demands and challenges posed by different sports.
