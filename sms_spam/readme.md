### 🔴 **This dataset is probably unsuitable for K-12 learners!**
- Contains real text messages, some with references to substances, lewd behavior, etc

<br></br>
**Dataset description:**

Source: [Kaggle](https://www.kaggle.com/datasets/thedevastator/sms-spam-collection-a-more-diverse-dataset?select=train.csv)

Cleaned dataset, easy difficulty

This folder contains three `.csv` files:
- `sms_spam_uncleaned.csv` - **original dataset** with  all original samples, some formatting issues, and unsupported characters.
- `sms_spam_unsanitized.csv` - good formatting, but still contains all samples (some of which are overly explicit/obscene).
- `sms_spam.csv` - **Recommended** 'clean' version. **Note:** this still contains samples with explicit language and/or suggestive themes, feel free to edit at your discretion.

Each file contains SMS messages with the following attributes: 
- **SMS** - text message content
- **Label** - indicates whether it is spam (0-not spam, 1-spam).



ML Algorithms:

- Logistic regression
- KNN


```
import pandas as pd
url = "https://raw.githubusercontent.com/the-codingschool/TRAIN/main/sms_spam/sms_spam.csv"
df = pd.read_csv(url)
```
