# myopia-unsupervised-learning

This repository contains a jupyter notebook file that uses a dataset on Myopia (nearsightedness) and analyzes it using unsupervised machine learning to try to form patient clusters that will help in predicting Myopia in patients. After scaling the data, PCA was used to decrease the dimensions of the dataset. t-SNE was performed on the dimensionally reduced data to further reduce the dimensions and this data was plotted using MatPlotLib and analyzed for clusters. Using this in conjunction with the K-Means cluster analysis, a recommendation on the number of patient clusters was made below.

### Technologies

- Python
- Pandas
- Jupyter Notebook
- MatPlotLib
- Sci-Kit Learn
- StandardScaler
- PCA
- KMEANS
- t-SNE

### Analysis and Recommendation

Looking at the data as a whole and the elbow curve above, the patients can be clustered into 3 different clusters since there is a distinct elbow seen of k equals 3.
