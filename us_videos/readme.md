Dataset description:

Cleaned dataset, moderate difficulty

The US videos dataset contains information about trending videos on YouTube in the United States. Here is a summary of the available columns in the dataset:

video_id: Unique identifier for each video.
trending_date: Date when the video was trending on YouTube.
title: Title of the video.
channel_title: Name of the YouTube channel that published the video.
category_id: ID representing the category to which the video belongs.
publish_time: Date and time when the video was published.
tags: Tags associated with the video, providing additional information.
views: Number of views the video has received.
likes: Number of likes received by the video.
dislikes: Number of dislikes received by the video.
comment_count: Number of comments posted on the video.
thumbnail_link: URL link to the video thumbnail image.
comments_disabled: Indicates whether comments are disabled for the video (True/False).
ratings_disabled: Indicates whether ratings are disabled for the video (True/False).
video_error_or_removed: Indicates whether the video has encountered an error or has been removed (True/False).
description: Description or summary of the video provided by the publisher.
This dataset provides insights into the popularity, engagement, and characteristics of trending videos on YouTube in the United States. It can be used for various analysis and prediction tasks, such as understanding trends, identifying popular channels, or predicting video engagement based on the available features.

ML Algorithms:
1. Linear regression

```
import pandas as pd
url = "https://raw.githubusercontent.com/the-codingschool/TRAIN-datasets/main/us_videos/USvideos.csv"
df = pd.read_csv(url)
```
