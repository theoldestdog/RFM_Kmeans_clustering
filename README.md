This is an exercise from a tutorial by TrentDoesMath
It uses an excel file of sales data that is cleaned, engineered and then visualized to 
demonstrate how KMeans and silhouette scores are developed and used and it is a good example
There is a page two of the spreadsheet that can be used to replicate the tutorial processes
in another project.
Here is a link to the github for this tutorial:  [https://github.com/trentpark8800/](https://github.com/trentpark8800/online-retail-data-clustering)
Here is the link to the data. It is large so not posted up here: https://archive.ics.uci.edu/dataset/502/online+retail+ii

The kmeans_agg_data notebook is an exercise in running the main preprocessing scaling methods on the full dataset instead of breaking it up into
outlier and non-outlier dataframes.
The scaling methods weren't effective but performing a log transformation on the three feature columns seemed to work just fine. Those violin plots
looked similar to the isolated violin plots in the original tutorial.
