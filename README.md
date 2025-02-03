# PC Performance Monitoring

**Copyright © 2022 Alessio Borgi, Martina Doku, Giuseppina Iannotti**

**PROJECT SCOPE**: Main PC Components Analysis through Statistics and ML Techniques. A project focused on monitoring system performance using statistical analysis and machine learning techniques. This repository provides tools and methods for collecting, analyzing, and visualizing performance metrics, enabling effective performance tuning and anomaly detection. Suitable for developers and data scientists interested in optimizing system performance and predictive maintenance.

**PROJECT RESULTS**:
- Data collection (CPU, Memory, Physical Disk, Cache, and Battery) through the Windows' "Performance Monitoring" application over multiple PCs.
- Clustering Techniques application (K-Means Clustering, K-Means++, GMM, K-Means Elkan Algorithm) classifying the data collected either idle or working. 
- By-Hand K-Means and K-Means++ implementation. 
- Elbow Method, Silhouette Coefficient, and AIC & BIC evaluation Criteria determining the best number of clusters.
- Best Algorithm  choice based on Accuracy and Time Performances.
- Best PC choice based on Time Performances.
- Average Page Faults measurements (using Non-Parametric and Parametric Bootstrap).
- Anova-one-way-Test for Page and Cache Faults comparison test. 
- Pairwise T-Test for finding similar Pcs’ behaviours.
- Linear Regression Application to determine "%Disk Time" vs "Average Disk Write Queue Length", and "Data Maps/Sec" vs "Copy Reads/Sec" relationships.
- Highly Potential Influence points individuation with Leverage and Cook's Distance Techniques.
