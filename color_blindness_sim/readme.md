**Dataset description:**

**Source:** This is technically an original dataset created using the RGB data from [color_classification](https://github.com/the-codingschool/TRAIN-datasets/tree/main/color_blindness_sim) and other tools.

- Original normal vision colors are from the [color classification dataset](https://raw.githubusercontent.com/the-codingschool/TRAIN/main/color_classification/color_data.csv).

- Simulated RGB colors were calculated and extracted from this [color blindness simulator by David Nichols](https://davidmathlogic.com/colorblind/).


<br />

Clean, moderate difficulty dataset, but the notebook makes heavier use of python programming.


This folder contains three files:
- `color_blind_RGB.csv` - **Recommended** Contains 5053 color samples broken down into their RGB representations for 4 vision types: true (normal vision), prot (protanopia), deut (deuteranopia), and trit (tritanopia).
- `color_blind_HEX.csv` - Contains the same color samples except all RGB values are condensed into hex codes. This version of the data is not referenced in the notebook and is only here just in case.
- `vision_deficiency_and_accessibility.ipynb` - Outlines a project in which students train a regression model to predict how colors appear to individuals with different forms color blindness. This also includes output styling instructions for visual evaluation. After training a model, students move on to assessing the accessibility of color combinations (palettes) using color difference metrics. Finally, part 3 outlines the necessary steps to simulate entire images for the three vision deficiency types.


The dataset in `color_blind_RGB.csv` has the following 12 attributes (each vision type has 3 attributes pertaining to it): 
- True (normal vision)
    - true_red - red RGB value ( integer 0-255 )
    - true_green - green RGB value ( integer 0-255 )
    - true_blue - blue RGB value ( integer 0-255 )
- Protanopia
    - prot_red 
    - prot_green
    - prot_blue 
- Deuteranopia
    - deut_red 
    - deut_green
    - deut_blue 
- Tritanopia
    - trit_red 
    - trit_green
    - trit_blue 


<br />

**ML Algorithms:**
- LinearRegression
- DecisionTreeRegressor
- RandomForestRegressor

<br />


```
import pandas as pd
url = "https://raw.githubusercontent.com/the-codingschool/TRAIN/main/color_blindness_sim/color_blind_RGB.csv"
df = pd.read_csv(url)
```
