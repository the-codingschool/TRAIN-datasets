**Dataset description:**

**Sources:**
- [UCI](https://archive.ics.uci.edu/dataset/40/flags) - *"Collected primarily from the Collins Gem Guide to Flags: Collins Publishers (1986)."*
- Flag image links - [World Flag Chart](https://flaglog.com)

<br />

**Files:**
- `flag_data.csv`
- `flag_data_cleaned.csv` - **Recommended**, cleaned dataset. All catigorical features are numerically encoded.
- `img_links.csv` - Contains links to images of all flags and the year/version so they can be displayed in addition to the other data.
- `flag.data` - **Original**, uncleaned dataset. Missing column labels, has some misspellings, etc.

<br />

**Attribute Information:**

|     |     |     |
| --: | --- | --- |
|  1. | name | Name of the country (or territory) |
|  2. | landmass | 1=North America, 2=South America, 3=Europe, 4=Africa, 5=Asia, 6=Oceania |
|  3. | zone | Geographic quadrant, based on Greenwich and the Equator 1=NE, 2=SE, 3=SW, 4=NW |
|  4. | area | in thousands of square km |
|  5. | population | in millions (rounded) |
|  6. | language | 1=English, 2=Spanish, 3=French, 4=German, 5=Slavic, 6=Other Indo-European, 7=Chinese, 8=Arabic, 9=Japanese/Turkish/Finnish/Magyar, 10=Others |
|  7. | religion | 0=Catholic, 1=Other Christian, 2=Muslim, 3=Buddhist, 4=Hindu, 5=Ethnic, 6=Marxist, 7=Others |
|  8. | bars | Number of vertical bars in the flag |
|  9. | stripes | Number of horizontal stripes in the flag |
| 10. | colors | Number of different colors in the flag |
| 11. | red | 0 if red absent, 1 if red present in the flag |
| 12. | green | ^^ |
| 13. | blue | ^^ |
| 14. | gold | ^^ (also yellow) |
| 15. | white | ^^ |
| 16. | black | ^^ |
| 17. | orange |  ^^ (also brown) |
| 18. | mainhue | Predominant color in the flag (tie-breaks decided by taking the topmost hue, if that fails then the most central hue, and if that fails the leftmost hue) |
| 19. | circles |  Number of circles in the flag |
| 20. | crosses | Number of upright crosses |
| 21. | saltires | Number of diagonal crosses |
| 22. | quarters | Number of quartered sections |
| 23. | sunstars | Number of sun or star symbols |
| 24. | crescent | 1 if a crescent moon symbol present, else 0 |
| 25. | triangle | 1 if any triangles present, 0 otherwise |
| 26. | icon | 1 if an inanimate image present (e.g., a boat), otherwise 0 |
| 27. | animate | 1 if an animate image (e.g., an eagle, a tree, a human hand) present, 0 otherwise |
| 28. | text | 1 if any letters or writing on the flag (e.g., a motto or slogan), 0 otherwise |
| 29. | topleft | Color in the top-left corner (moving right to decide tie-breaks) |
| 30. | botright | Color in the bottom-right corner (moving left to decide tie-breaks) |

<br />

Good for EDA / data visualizations.

ML Algorithms:
- Random Forest Classifier
- Decision Tree Classifier
- Clustering?

Additional Applications:
- Could eventually be extended for Image Classification/Recognition applications??

<br />

```
import pandas as pd
url = "https://raw.githubusercontent.com/the-codingschool/TRAIN/main/flags/flag_data_cleaned.csv"
df = pd.read_csv(url)

url2 = "https://raw.githubusercontent.com/the-codingschool/TRAIN/main/flags/img_links.csv"
img_df = pd.read_csv(url2)
```
