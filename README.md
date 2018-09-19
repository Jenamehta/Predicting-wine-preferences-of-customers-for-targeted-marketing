# Predicting-wine-preferences-of-customers-for-targeted-marketing

## Dataset
Dataset is from www.wiley.com/go/datasmart

## Objective 
To improve an import-export business focused on bringing bulk wine to the states and selling it to select wine and liquor stores across the country at a profit.

## Steps
- Segment the list into groups based on interest. 
- Whichever deal you thought matched up better with the segment could go in the subject line and would come first in the newsletter for targeted marketing and hence an increase in sale.

## Algorithms 
- K-means Clustering (Euclidean Distance)

## Technologies 
- Excel

## Dependencies
- Solver

## Conclusion/Findings
When we look at the 3MC-TopDealsByCluster Sheet in the Excel Workbook we can interpret this data as follows 
- Cluster 1 has a tie between people who prefer Champagne and Cabernet Sauvignon, when a cluster doesn't provide clear results it means we need to add or subtract clusters by finding silhoutte value for k, in our case it could be adding more. We assumed k=3 for simplicity of solving.
- Cluster 2 has people who buy minimum quantity as 6kg
- Cluster 3 has people who prefer wine which has 'France' as its country of origin
 
 ## Future Scope
 One can make a wine recommendation system based on this and bump up sales by targeted email marketing

