# Credit-Card-Data-Clustering
This repository conations Machine learning project using unsupervised learning techniques.

# Evaluate the difference between data transformation techniques:
### At this part using different Data Transformation techniques.
  #### Feature Scaling:
    1. MinMax Scaler. 
    2. Standard Scaler. 
    3. MaxAbsScaler. 
    4. Robust Scaler.
    5. Quantile Transformer Scaler. 
  #### Feature Transformation:
    1. Log Transform. 
    2. Power Transformer Scaler.
#### The Best Case for our problem is Log Transform. It separates Data as seen below:
  <p align="center">
  <img src="https://raw.githubusercontent.com/FatmaAlZhraaMarzouk/Credit-Card-Data-Clustering/main/Imgs/Logdata.jpg"/>
</p>

<h4>Is PCA better than Kernel PCA?</h4>
 <p> At This part working on Stander scaler data, Log Transformed data using n_components = 11 for stander scaler and 7 for Log Transformed data.
  for kernel PCA using Radial Basis Function Kernel.
 The results for stander scaler data almost same.</p>
 <p>For log Data Kernel PCA adds boundaries for data compared to PCA As Shown below:</p>
<p align="center">
  <img src="https://raw.githubusercontent.com/FatmaAlZhraaMarzouk/Credit-Card-Data-Clustering/main/Imgs/kPCA.jpg"/>
</p>
<p align="center">
  <img src="https://raw.githubusercontent.com/FatmaAlZhraaMarzouk/Credit-Card-Data-Clustering/main/Imgs/PCA.jpg"/>
</p>
<h4>Try unsupervised algorithms to clusting data</h4>
<h5> 1.	Kmeans and Hierarchical Clustering.<h5/p>
At this part using Stander scaler data and Log transformed Data.
Results Kmeans on Log Data:
  <p align="center">
Results Hierarchical on Log Data:
Kernel PCA is best visualization in Hierarchical Clustring.
    <p align="center">
  <img src="https://raw.githubusercontent.com/FatmaAlZhraaMarzouk/Credit-Card-Data-Clustering/main/Imgs/KPCAHcl.jpg"/>
</p>

  <img src="https://raw.githubusercontent.com/FatmaAlZhraaMarzouk/Credit-Card-Data-Clustering/main/Imgs/LogKmeans.jpg"/>
</p>
  <p align="center">
  <img src="https://raw.githubusercontent.com/FatmaAlZhraaMarzouk/Credit-Card-Data-Clustering/main/Imgs/PCAmeans.jpg"/>
</p>
  <p align="center">
  <img src="https://raw.githubusercontent.com/FatmaAlZhraaMarzouk/Credit-Card-Data-Clustering/main/Imgs/KPCAKmeans.jpg"/>
</p>
  

 
