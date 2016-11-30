# customer-segments
In this project I applied unsupervised learning techniques on product spending data collected for customers of a wholesale distributor in Lisbon, Portugal to identify customer segments hidden in the data. 

First explored the data by selecting a small subset to sample and determine if any product categories highly correlate with one another. Afterwards, preprocessed the data by scaling each product category and then identified (and removed) unwanted outliers.
With the good, clean customer spending data, I applied PCA transformations to the data and implemented clustering algorithms to segment the transformed customer data. Finally, I compared the segmentation found with an additional labeling and consider ways this information could assist the wholesale distributor with future service changes.

In this project, I explained the following key techniques of unsupervised learning in the reports (customer_segments_YOONSUPARK.ipynb, customer_segments_YOONSUPARK.html) :
####How to apply preprocessing techniques such as feature scaling and outlier detection.
####How to interpret data points that have been scaled, transformed, or reduced from PCA.
####How to analyze PCA dimensions and construct a new feature space.
####How to optimally cluster a set of data to find hidden patterns in a dataset.
####How to assess information given by cluster data and use it in a meaningful way.

### Data
The dataset for this project can be found on the UCI Machine Learning Repository.
( https://archive.ics.uci.edu/ml/datasets/Wholesale+customers )

### Installation and usage

Program is written in python 2.7, it one may need anaconda shoulde be installed(including numpy, scipy, pandas, matplotlib, jupyter) 
( https://docs.continuum.io/anaconda/install )
or install python 2.7 and then install Numpy, Scipy, Pandas, matplotlib,jupyter manually as follows.
> sudo pip install numpy scipy matplotlib 

- after anaconda installed , one may need to jupyter run, by type in command line and hit the enter.
> jupyter notebook 
and then click customer_segments_YOONSUPARK.ipynb in web page.  


### Meta
Yoonsu Park - http://www.patternics.com
Distributed under the MIT license. See LICENSE for more information( https://en.wikipedia.org/wiki/MIT_License ).
http://www.patternics.com/customer-segments/
