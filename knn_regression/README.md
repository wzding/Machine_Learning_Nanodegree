# KNN (k-nearest neighbors)

Python implementation of K-nearest neighbors (knn) regression and Nadaraya–Watson kernel regression. In this project, we built a simple pricing model using k-nearest neighbors and Nadaraya–Watson kernel (nwk) regression. Note that these two models are created to fit the unique structure of the data. It may not be useful for general purpose knn models.

### files
* knn_regression.py is the file with the main function of knn regression.
* nwk.py is the file with the main function of nwk regression.
* data.csv is the data file we used to create models.
* knn_data.ipynb is an example of how to apply these two models on data.csv.

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

## Contributing

* Fork it!
* Create your feature branch: git checkout -b my-new-feature
* Commit your changes: git commit -am 'Add some feature'
* Push to the branch: git push origin my-new-feature
* Submit a pull request :D

## Authors

* **Wenzhe Ding** - *Initial work*
