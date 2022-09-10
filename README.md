# Statistics: Performance Monitoring

Copyright © 2022 Alessio Borgi

PROJECT SCOPE: Detailed Analysis of some PC Components through Statistics and ML Techniques.

PROJECT RESULTS:
• Collection of data (about CPU, Memory, Physical Disk, Cache, and Battery) through the Windows' "Performance Monitoring" application.
• Found a distinction among the samples we have gathered: Idle VS Working Distinction (when the PC is switched on but it is currently doing nothing VS when the PC is Training a ML Model), through some Clustering Techniques (K-Means Clustering, K-Means++, GMM, K-Means with Elkan Algorithm).
• Implementation of a By-Hand K-Means and K-Means++ Versions.
• Individuation of the best number of clusters through the Elbow Method, Silhouette Coefficient, and AIC & BIC evaluation Criteria.
• Individuation of the Best Algorithm to use depending on a By-Hand Accuracy Implementation, and on Time Performances.
• Comparison between PCs and Individuation of the Best PC in terms of Time Performances.
• Focus on Average Page Faults (using Non-Parametric and Parametric Bootstrap).
• Anova-one-way-Test for determining whether the number of Page Faults between computers were similar. Anova-one-way-Test for determining whether the number of Cache Faults between computers were similar
• Pairwise T-Test between computers to see, more in dept, what are the PCs that had the same behaviour.
• Application of a Linear Regression in such a way to find a relation between "%Disk Time" and "Average Disk Write Queue Length", and also of "Data Maps/Sec" and "Copy Reads/Sec". Individuation of Points that have Highly Potential Influence on the least squares estimates through Leverage and Cook's Distance Techniques. Deletion of them in such a way to reach a higher Least Square Estimation.
• Investigation on correlations between some of the most important features in such a way to individuate the most correlated ones. 

PROJECT REPOSITORY: https://github.com/alessioborgi/Performance_Monitoring_Statistics_and_ML
