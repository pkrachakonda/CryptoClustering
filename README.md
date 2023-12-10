# CryptoClustering
As part of this challenge, initial Cryptocurrency dataset is standardised using *StandardScaler* module (Table 1), for comparison of data. A plot is generated using *hvPlot* (Figure 1) to view the entire data.

### Table 1 - Original Scaled Data 

![Table 1 - Original Scaled Data](https://github.com/pkrachakonda/CryptoClustering/assets/20739237/11ca864e-9640-4f43-87d6-5ad2e1e2dfe7)

### Figure 1 - Original Data

![Figure 1 - Original Data](https://github.com/pkrachakonda/CryptoClustering/assets/20739237/5e646290-e639-4af1-9668-11d3db025d0b)

## Original Scaled Data

Using *Elbow method*, it was observed that **four** clusters (k) are good fit for the data, and this value is used to fit and predict KMeans model using the original scaled datasets (Figure 2). Using hvPlot, a scatter plot is generated for the original scaled data (Figure 3).

### Figure 2 - Elbow Curve Orginal Scaled Data

![Figure 2 - Elbow Curve Orginal Scaled Data](https://github.com/pkrachakonda/CryptoClustering/assets/20739237/90a2f06f-6e0a-481c-bf5b-9c611020541d)

### Figure 3 - Scatter Plot for Original (Scaled) Data - Clustering

![Figure 3 - Scatter Plot for Original (Scaled) Data - Clustering](https://github.com/pkrachakonda/CryptoClustering/assets/20739237/eda71652-d905-453b-878f-82047f848604)

## Principal Component Analysis (PCA)

Using PCA on original scaled data, a reduction in dimensionality is estimated (Table 2). ***Approximately 89.5% of total variance was explained by the three principal components***. Using Elbow method on the PCA data, ***it was observed that like the original scaled data, four clusters (k) is a good match for the data*** (Figure 4). A K-Means model based on the Elbow data, is used to predict the clusters to group the cryptocurrencies using the PCA data and hvPlot is used to plot the scatter plot (Figure 5).

### Table 2 - PCA Values  for CryptoCurrency Data

![Table 2 - PCA Values  for CryptoCurrency Data](https://github.com/pkrachakonda/CryptoClustering/assets/20739237/db1c9164-a660-4341-97b3-f5a2e78927c0)

### Figure 4 - Elbow Curve Using PCA Data

![Figure 4 - Elbow Curve Using PCA Data](https://github.com/pkrachakonda/CryptoClustering/assets/20739237/e8219960-806f-4e56-81f5-e3698ce8b8e2)

### Figure 5 - Scatter Plot for CrytoCurrency Using PCA

![Figure 5 - Scatter Plot for CrytoCurrency Using PCA](https://github.com/pkrachakonda/CryptoClustering/assets/20739237/9d4b4500-3799-4cb2-a494-41da4dc2478b)

## Composite Graphs

Composite hvPlots were generated for both Elbow method as well as Scatter plots based on Original scaled data and PCA data (Figures 6 – 7). Based on the figures, ***“it could be inferred that fewer features (i.e. reducing the dimensionality) results in lower inertia, therefore lesser noise/outliers and also the data are more clustered”***.

### Figure 6 - Composite Curve - Elbow

![Figure 6 - Composite Curve - Elbow](https://github.com/pkrachakonda/CryptoClustering/assets/20739237/97a417c6-d047-46f9-904c-05cf0f8dfb61)

### Figure 7 - Composite Curves - Scatter Plot

![Figure 7 - Composite Curves - Scatter Plot](https://github.com/pkrachakonda/CryptoClustering/assets/20739237/72d7b245-42b2-484d-9e0e-d85ed2576078)
