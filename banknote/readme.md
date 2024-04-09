Dataset description:

Cleaned dataset, moderate difficulty

This data set was pulled from [UCI](https://archive.ics.uci.edu/ml/datasets/banknote+authentication). It was collected by photos of genuine and forged banknotes. A Wavelet Transform tool was then used on the images to get the following attributes for each
sample:
1. variance of Wavelet Transformed image (continuous)
2. skewness of Wavelet Transformed image (continuous)
3. curtosis of Wavelet Transformed image (continuous)
4. entropy of image (continuous)
5. class (integer)

ML algorithms:
1. Classification: KNN

This dataset contains 1,372 instances and is good for classification. Note that the inputs are not
very intuitive, so an explantation should be provided. A KNN model with k = 5 with variance
and entropy has ~88% accuracy.

You can use the following code to load the data into google colaboratory:
```
import pandas as pd
url = "https://raw.githubusercontent.com/the-codingschool/TRAIN/main/banknote/banknote.csv"
df = pd.read_csv(url)
```
