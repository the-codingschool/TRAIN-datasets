Dataset description:

Cleaned/messy dataset, moderate difficulty

This data set was pulled from [UCI](https://archive.ics.uci.edu/ml/datasets/Automobile). It contains the following information:
1. The specification of an auto in terms of various characteristics
2. Its assigned insurance risk rating
3. Its normalized losses in use as compared to other cars

<br>

Cars are initially assigned a risk factor symbol associated with its price. A value of +3 indicates that the auto is risky, -3 that it is probably pretty safe.

<br>
It also contains the following information for each car:

1. symboling
2. normalized-losses
3. make
4. fuel-type
5. aspiration
6. num-of-doors
7. body-style
8. drive-wheels
9. engine-location
10. wheel-base
11. length
12. width
13. height
14. curb-weight
15. engine-type
16. num-of-cylinders
17. engine-size
18. fuel-system
19. bore
20. stroke
21. compression-ratio
22. horsepower
23. peak-rpm
24. city-mpg
25. highway-mpg
26. price


ML Algorithms:

1. Linear regression

You can use the following code to load the data into google colaboratory:

```
import pandas as pd
url = "https://raw.githubusercontent.com/the-codingschool/TRAIN/main/automobile/cars.csv"
df = pd.read_csv(url)
```
