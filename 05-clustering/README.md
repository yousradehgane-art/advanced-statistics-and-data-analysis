# Clustering: River Chemical Concentrations

This folder contains a clustering homework from the Advanced Statistics and Data Analysis course. The analysis uses chemical concentration measurements from rivers or creeks to identify groups with similar water composition.

## Research Questions

1. Are the chemical concentration variables already standardized?
2. How many natural groups are present in the river data?
3. Do hierarchical clustering and k-means clustering give similar results?
4. How do the results change when using 2, 3, or 4 clusters?
5. How can PCA help visualize and interpret the clusters?

## Files

- `river-chemical-clustering-analysis.Rmd`: R Markdown file containing the full clustering analysis
- `fiumi.rda`: dataset containing river chemical concentration measurements

## Methods Used

- Data standardization check
- Euclidean distance calculation
- Hierarchical clustering
- Single linkage
- Complete linkage
- Ward’s method
- K-means clustering
- Silhouette analysis
- Adjusted Rand Index
- PCA biplot visualization

## Tools Used

- R
- dplyr
- cluster
- RColorBrewer
- factoextra
- mclust

## Summary

The analysis shows that the river chemistry data are already standardized. Hierarchical clustering and 
k-means clustering both support a clear two-cluster solution, with perfect agreement between the two methods 
for `k = 2`. A four-cluster solution is also possible and gives more detailed chemical groupings,
but the separation is less clear. PCA biplots help interpret the clusters in relation to nitrate, sulfate,
chloride, and calcium concentrations.
