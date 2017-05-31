# KNN (k-nearest neighbors)

Python implementation of K-nearest neighbors (knn) regression and Nadaraya–Watson kernel regression. In this project, we built a simple pricing model using k-nearest neighbors and Nadaraya–Watson kernel (nwk) regression. Note that these two models are created to fit the unique structure of the data. It may not be useful for general purpose knn models.

### Files
* knn_regression.py is the file with the main function of knn regression.
* nwk.py is the file with the main function of nwk regression.
* data.csv is the data file we used to create models.
* knn_data.ipynb is an example of how to apply these two models on data.csv.

### Data
The input data is a house sale dataset, consisting of four columns: latitude, longitude, close_date, close_price. The corresponding data types are float, float, string and integer. The close_date are in format '%Y-%m-%d %H:%M:%S.%f'.
One example is "36.26001	-98.37648	2014-04-04 21:57:21.422720	79241.864341". 

### Installing

We can use the model by downloading the knn_regression.py and nwk.py files.Then we imported these files for useage.

```
from knn_regression import KNN 
from nwk import NWK
```
There are several modules we needed to create the KNN class and NWK class.
```
import numpy as np
import random
from datetime import datetime
import sys
from scipy.stats import norm
```

### Main functions
One requirement of this predictive model is that a home j should be considered a neighbor to home i only if the close data of j occurred prior to the close date of i. So, we need to filter out all the records that happen after home i when searching for neighbors of home i.
We converted the string to datetime object and then to total seconds after January 1, 1970 to make comparisions between the time of a test data to all the training data points. 

The main function of knn class applied quick select algorithm to search the k nearest neighbors of a test data point in order to reduce the time complexity of the model. If we want to make a prediction on the price of a house sell at a certain time, the most intuitive estimator would be just the average price of the K nearest houses sold before. 

We could also give each house price in the data set a weight depending on whether it is in the neighbourd rather than taking the average to get the price. The Nadaraya–Watson kernel regression model serves as a comparision to the knn model, whereas the Kernal method puts weights on all prices in the data set according to the kernel function. 

### Contributing

* Fork it!
* Create your feature branch: git checkout -b my-new-feature
* Commit your changes: git commit -am 'Add some feature'
* Push to the branch: git push origin my-new-feature
* Submit a pull request :D

## Authors

* **Wenzhe Ding**
