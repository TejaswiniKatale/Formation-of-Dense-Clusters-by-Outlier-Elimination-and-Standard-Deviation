Outliers are the uncommon data points which deviate from 
the majority of the Data from a dataset. Presence of Outliers can affect 
the model’s performance, leading to incorrect data analysis. Hence, 
identifying and eliminating Outliers is a crucial pre-processing step. 
This research paper suggests a method for removing outliers that takes 
standard deviation into account. Standard Deviation is a statistical 
measure which measures the dispersion within the dataset. In the 
proposed algorithm, the first step is to calculate Standard Deviations 
of all the features within the Dataset. Next, the feature with highest 
Standard Deviation is chosen. After normalization of this column, 
individual Standardized values for the data points are calculated from 
the standardized Median. Furthermore, these values are arranged in 
the ascending order. Selecting closest left 85% and right 85% values 
from the Standardized Median. For the remaining features, only those 
observations are selected which are corresponding to the above 
selected range of data points. To check the efficacy of this algorithm, 
it is implemented on 5 Standard datasets - Iris Species, Pima Diabetes 
Dataset, College Dataset, Seattle Weather, Water Quality Dataset. 
After elimination of Outliers, the proposed algorithm aims to form 
dense clusters. When compared with K-means clustering, for all the 5 
datasets, it gives a better Silhouette Score. The highest score of 0.7 is 
for Iris Species and the highest difference of 0.49 between the 
Silhouette score of K-means and the proposed algorithm is for Water 
Quality Dataset. 
