# Document-Clustering
In this project we use K-means and NMF for document clustering. The datasets are TDT2 and Reuters-21578.    


The TDT2 corpus consists of data collected during the first half of 1998 and taken
from six sources, including two newswires (APW, NYT), two radio programs (VOA,
PRI), and two television programs (CNN, ABC). It consists of 11201 topic documents
which are classified into 96 semantic categories.  
We use the documents coming from the 30 categories which are the largest collections
in the data set and divide them into 2 subsets:  
•TDT2-Top10: We consider the documents in the 10 categories with the largest
number of documents in the data set and then construct the subset containing
10 percents of each category.  
•TDT2-Top10: We consider the documents in the 10 categories with the largest
number of documents in the data set and then construct the subset containing
10 percents of each category.    


The Reuters-21578 data set is a collection of documents from Reuters newswire in
1987. It contains 21578 documents. They can be divided into 135 categories. In this
data set, we use the following subsets for testing :  
•Reuters-Top10: From 10 categories with largest number of documents in
Reuters data set, we collect 5 percents from the 1st category with the largest
number documents and 10 percents from the 2nd category with the 2nd
largest number documents, and from the 3rd to 20th categories, we choose
40 percents of each category.  
•Reuters-Top20: Similarly, from 20 categories with largest number of documents in Reuters data set, we collect 5 percents from the 1st category with
the largest number documents and 10 percents from the 2nd category with
the 2nd largest number documents, and from the 3rd to 20th categories, we
choose all documents. These documents construct the subset.    


To show the effectiveness of document clustering results, we use two evaluation
measures, purity and entropy.  
Purity measures the dominance of the largest class per cluster. The larger the value of purity is, the better
the clustering solution is. Entropy is a measure on uncertainty about the distribution
of clustering results. The smaller the entropy value is, the better the clustering quality is.    


In final result we see that NMF is a more effective method that Kmeans.
