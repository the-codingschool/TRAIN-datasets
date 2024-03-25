**Dataset description:**

**Sources:**
- [Article by Ajinkya Chavan](https://medium.com/analytics-vidhya/building-rgb-color-classifier-part-1-af58e3bcfef7)
- [Github Repo](https://github.com/AjinkyaChavan9/RGB-Color-Classifier-with-Deep-Learning-using-Keras-and-Tensorflow) - associated with Ajinkya's article/project
- [Research Paper](https://europepmc.org/backend/ptpmcrender.fcgi?accid=PMC1618485&blobtype=pdf) - Ajinkya references this paper for defining the 11 target categories

Cleaned dataset, easy difficulty

This folder contains three files:
- `color_data.csv` - 5053 randomly generated RGB color samples, each with a manually selected color label.
- `color_classification.ipynb` - Notebook containing a project introduction, new instructions + functions on notebook output styling (very handy for evaluating color stuff!), a basic project implementation, and instructions on how to expand the dataset. **Note:** There are some instructor notes in here, this notebook (though extensive) is meant to be a starting point to build out a project and should probably **not** be distributed to students as is.
- `RGB to HEX.jpg` - Infographic referenced in the notebook that outlines the process of converting RGB colors to hexadecimal format.

The dataset in `color_data.csv` has the following attributes: 
- **<font color="red">red</font>** - RGB red value ( integer 0-255 )
- **<font color="green">green</font>** - RGB green value ( integer 0-255 )
- **<font color="#3344ff">blue</font>** - RGB blue value ( integer 0-255 )
- **label** - color category, there are 11 total:

    - *Red, Orange, Yellow, Green, Blue, Purple, Pink, Brown, Black, Gray, White*


<br />

**Project Applications**

Ideally, this dataset + notebook could be used to create accessibility tools for color blind individuals! 

After training a model, students can feed it their own RGB colors to see how they are classified. Theoretically, even students with partial or total color blindness could do this project and use their ML skills to improve model metrics, as long as they trust the initial target labelings of the data.


**ML Algorithms:**

- Random Forest Classifier
- Decision Tree
- KNN
- Neural Networks (advanced)


```
import pandas as pd
url = "https://raw.githubusercontent.com/the-codingschool/TRAIN/main/color_classification/color_data.csv"
df = pd.read_csv(url)
```
