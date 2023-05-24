Dataset description:

Cleaned dataset, moderate difficulty

The US videos dataset contains information about trending videos on YouTube in the United States. Here is a summary of the available columns in the dataset:

1. video_id: Unique identifier for each video.
2. trending_date: Date when the video was trending on YouTube.
3. title: Title of the video.
4. channel_title: Name of the YouTube channel that published the video.
5. category_id: ID representing the category to which the video belongs.
6. publish_time: Date and time when the video was published.
7. tags: Tags associated with the video, providing additional information.
8. views: Number of views the video has received.
9. likes: Number of likes received by the video.
10. dislikes: Number of dislikes received by the video.
11. comment_count: Number of comments posted on the video.
12. thumbnail_link: URL link to the video thumbnail image.
13. comments_disabled: Indicates whether comments are disabled for the video (True/False).
14. ratings_disabled: Indicates whether ratings are disabled for the video (True/False).
15. video_error_or_removed: Indicates whether the video has encountered an error or has been removed (True/False).
16. description: Description or summary of the video provided by the publisher.


This dataset provides insights into the popularity, engagement, and characteristics of trending videos on YouTube in the United States. It can be used for various analysis and prediction tasks, such as understanding trends, identifying popular channels, or predicting video engagement based on the available features.

ML Algorithms:
1. Linear regression

```
import pandas as pd
url = "https://raw.githubusercontent.com/the-codingschool/TRAIN-datasets/main/us_videos/USvideos.csv"
df = pd.read_csv(url)
```
