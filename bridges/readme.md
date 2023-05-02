
# Pittsburgh Bridges

This data set was pulled from [UCI](https://archive.ics.uci.edu/ml/datasets/Pittsburgh+Bridges). It also contains the following information for each bridge:
1. Id - bridge’s identifier
2. river - river of the bridge
a. A: Allegheny
b. M: Monongahela
c. O: Ohio
3. location - bridge’s location (1 - 52)
4. erected - bridge’s construction year (1818 - 1986)
5. purpose - bridge’s purpose
a. WALK, AQUEDUCT, RR (Railroad), HIGHWAY
6. length - bridge’s length
7. lanes - bridge’s lanes
8. clear-g - vertical clearance requirement (enforced or not)
a. N: Not enforced
b. G: Enforced
9. t-or-d - the roadway location on the bridge
a. THROUGH, DECK
10. material - bridge’s predominant material
a. WOOD, IRON, STEEL
11. span - bridge’s span
a. SHORT, MEDIUM, LONG
12. rel-l - relative length of the span to the crossing length
a. S: short
b. S-F: short-full
c. F: full
13. type - bridge’s type
a. WOOD, SUSPEN (Suspension), SIMPLE-T (Simple Truss), ARCH, CANTILEV
(Cantilever), CONT-T (Continuous Truss)

<br>
This dataset is good for classification. This dataset also requires come cleaning as it contains
NaN values.
You can use the following code to load the data into google colaboratory:

```
import pandas as pd
url = "https://raw.githubusercontent.com/the-codingschool/TRAIN/main/bridges/bridge.csv"
df = pd.read_csv(url)
```