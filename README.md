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

<h5>Is PCA better than Kernel PCA?</h5>
 <p> At This part working on Stander scaler data, Log Transformed data using n_components = 11 for stander scaler and 7 for Log Transformed data.
  for kernel PCA using Radial Basis Function Kernel.
 <h5>The results for stander scaler data almost same.</h>
 <p>For log Data Kernel PCA adds boundaries for data compared to PCA As Shown below:</p>
<p align="center">
  <img src="https://raw.githubusercontent.com/FatmaAlZhraaMarzouk/Credit-Card-Data-Clustering/main/Imgs/kPCA.jpg"/>
</p>
<p align="center">
  <img src="https://raw.githubusercontent.com/FatmaAlZhraaMarzouk/Credit-Card-Data-Clustering/main/Imgs/PCA.jpg"/>
</p>


