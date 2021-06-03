# Creating_Customer_Segments_with_Aravato
# Unsupervised Learning Project
## Dependencies:
- sklearn : 0.23.2
- seaborn : 0.11.1
- numpy : 1.19.2
- pandas : 1.1.5
- matplotlib : 3.3.2
- jupyter core : 4.7.0
- jupyter-notebook : 6.3.0
- qtconsole : 4.7.7
- ipython : 7.19.0
- ipykernel : 5.3.4
- jupyter client : 6.1.7
- jupyter lab : 2.2.6
- nbconvert : 6.0.7
- ipywidgets : 7.5.1
- nbformat : 5.0.8
- traitlets : 5.0.5
- The dataset used is not allowed to be shared
## Details regarding Implementation (will be further updated):
Performed data wrangling on a dataset with about 900,000 rows and 85 features on population dataset of Germany provided by Bertelsmann Arvato in collaboration with Udacity which included:
  1) Removing rows and columns with too much missing data, re-encoding categorical and mixed features.
  2)Imputed the data and apllied Feature Scaling
  3)Performed Feature Extraction using PCA (37 latent features) and interpreted the Principal Components
  4)Applied Elbow method to obtain optimum clusters for KMeans Clustering
  5) Applied all these steps to Customer Dataset provided by Bertelsmann Arvato Udacity (Not Public)
  6) Compared the cluster distributions to find Potential Customers for the Company
