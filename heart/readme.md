Dataset description:

Cleaned dataset, moderate difficulty

This data set was pulled from [UCI](https://archive.ics.uci.edu/ml/datasets/SPECTF+Heart). The dataset describes diagnosing cardiac Single Proton Emission Computed Tomography (SPECT) images. Each instance has a classification: normal or abnormal. The original images were processed to obtain 22 binary feature patterns. The CLIP3 algorithm was used to generate classification rules from these patterns. The CLIP3 algorithm generated rules that were 84.0% accurate (as compared with cardilogists' diagnoses). This dataset contains the following information for each instance:
1. OVERALL_DIAGNOSIS: 0,1 (class attribute, binary)
2. F1: 0,1 (the partial diagnosis 1, binary)
3. F2: 0,1 (the partial diagnosis 2, binary)
4. F3: 0,1 (the partial diagnosis 3, binary)
5. F4: 0,1 (the partial diagnosis 4, binary)
6. F5: 0,1 (the partial diagnosis 5, binary)
7. F6: 0,1 (the partial diagnosis 6, binary)
8. F7: 0,1 (the partial diagnosis 7, binary)
9. F8: 0,1 (the partial diagnosis 8, binary)
10. F9: 0,1 (the partial diagnosis 9, binary)
11. F10: 0,1 (the partial diagnosis 10, binary)
12. F11: 0,1 (the partial diagnosis 11, binary)
13. F12: 0,1 (the partial diagnosis 12, binary)
14. F13: 0,1 (the partial diagnosis 13, binary)
15. F14: 0,1 (the partial diagnosis 14, binary)
16. F15: 0,1 (the partial diagnosis 15, binary)
17. F16: 0,1 (the partial diagnosis 16, binary)
18. F17: 0,1 (the partial diagnosis 17, binary)
19. F18: 0,1 (the partial diagnosis 18, binary)
20. F19: 0,1 (the partial diagnosis 19, binary)
21. F20: 0,1 (the partial diagnosis 20, binary)
22. F21: 0,1 (the partial diagnosis 21, binary)
23. F22: 0,1 (the partial diagnosis 22, binary)

ML Algorithms:
1. Classification: This dataset has been already split into testing and training data. You will need to upload both.
Training has 80 instances and the testing has 187 instances. 


You can use the following code to load the data into google colaboratory:

```
import pandas as pd
# training
url = "https://raw.githubusercontent.com/the-codingschool/TRAIN/main/heart/heart_train.csv"
df1 = pd.read_csv(url,
names = ["OVERALL_DIAGNOSIS", "F1", "F2", "F3", "F4", "F5", "F6", "F7", "F8",
"F9", "F10", "F11", "F12", "F13", "F14", "F15", "F16", "F17", "F18",
"F19", "F20", "F21", "F22"])
# testing
url = "https://raw.githubusercontent.com/the-codingschool/TRAIN/main/heart/heart_test.csv"
df2 = pd.read_csv(url,
names = ["OVERALL_DIAGNOSIS", "F1", "F2", "F3", "F4", "F5", "F6", "F7", "F8",
"F9", "F10", "F11", "F12", "F13", "F14", "F15", "F16", "F17", "F18",
"F19", "F20", "F21", "F22"])
```
