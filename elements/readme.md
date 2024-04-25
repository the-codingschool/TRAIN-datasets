**Dataset description:**

The periodic elements dataset contains information about 117 different elements and their properties like atomic number, weight, melting point, etc. With machine learning, this data can be used in several ways. It helps in quickly identifying elements, predicting their properties, and understanding trends across the periodic table. Moreover, it can be used to create interactive educational tools for learning about the periodic table and its elements. Overall, combining this dataset with machine learning opens up avenues for scientific research, innovation, and education in chemistry and related fields.

With additional info on elemental reactions and chemical compounds, this dataset could aid in designing new materials with specific characteristics and predicting chemical reactions.

<br />

**Sources:**
- [Kaggle](https://www.kaggle.com/datasets/jwaitze/tablesoftheelements?select=periodic_table.csv) - original dataset
- [periodictable.com](https://periodictable.com) - supplementary data
- [ptable.com](https://ptable.com) - supplementary data
- Wikipedia - supplementary data

<br />

**Files:**
- `periodic_elements.csv` - Cleaned dataset. Added missing values, simplified column data, and removed columns that offer little insight/utility in ML, contain complex string info, and/or are missing many values.
- `periodic_table_raw.csv` - Original, uncleaned dataset. 

<br />

**Attribute Information:**

|     |     |     |     |
| :-: | :-- | :-: | --- |
|   1 | name | *string* | Name of the element |
|   2 | symbol | *string* | Element name abbreviation |
|   3 | atomic_number | *int* | Typically equal to the number of protons |
|   4 | atomic_weight | *float* | Weighted mean of the relative masses of all isotopes (mass of protons and neutrons in an atom) in g/mol or amu |
|   5 | period | *int* | Row on the periodic table where elements share the same number of electron shells *([see here](https://upload.wikimedia.org/wikipedia/commons/thumb/0/03/Simple_Periodic_Table_Chart-blocks.svg/780px-Simple_Periodic_Table_Chart-blocks.svg.png))*  |
|   6 | group | *int* | Column on the periodic table where elements share the same number of valence electrons *([see here](https://upload.wikimedia.org/wikipedia/commons/thumb/0/03/Simple_Periodic_Table_Chart-blocks.svg/780px-Simple_Periodic_Table_Chart-blocks.svg.png))* |
|   7 | block | *string* | Corresponds to trends in electron configuration *([see here](https://upload.wikimedia.org/wikipedia/commons/thumb/f/f2/Periodic_table_blocks_spdf_%2832_column%29.svg/1000px-Periodic_table_blocks_spdf_%2832_column%29.svg.png))* |
|   8 | category | *string* | Set of elements that have similar properties, recognized by IUPAC *([see here](https://ptable.com/image/periodic-table.svg))*
|   9 | phase | *string* | Physical form at standard temperature and pressure |
|  10 | melting_point | *float* | Temperature (K) at which the solid substance melts at standard pressure (273.15 K, 1 bar) |
|  11 | boiling_point | *float* | Temperature (K) at which the liquid substance becomes a vapor at standard pressure (273.15 K, 1 bar) |
|  12 | electronegativity | *float* | Tendency for an atom to attract shared electrons and form a chemical bond, measured on Pauling scale |
|  13 | atomic_radius | *float* | Measure of the size of an atom from center of nucleus to outermost electron (pm) | 
|  14 | covalent_radius | *float* | Measure of the size of an atom that forms part of one covalent bond in picometers (pm) |
|  15 | at_t_(k) | *float* | Temperature (K) at which vapor pressure is 1 pascal (or 0.00001 bar) |


<br />

**ML Algorithms:**
- Regression
- Classification

Also good for preprocessing / feature encoding practice.


<br />

```
import pandas as pd
url = "https://raw.githubusercontent.com/the-codingschool/TRAIN/main/elements/periodic_elements.csv"
df = pd.read_csv(url)
```