# Youtube_Trending_Video_Analysis

YouTube is one of the popular platforms suitable for the trend of video content. Analyzing content on YouTube and user interaction behaviors is crucial. From the available data, the problem is to analyze the content on YouTube, the interaction, and the time for those videos, analyze and provide insights to content administrators/creators for producing suitable videos.

Problem Questions:
- How are the statistics and timing for trending videos currently?
- How does interaction with videos of different content and timing affect them?
- Which channels are receiving the most attention?
- What video genres are the most viewed and produced?
- How do the length and popularity of titles and keywords impact videos?
- Is the number of videos for each topic a significant analysis factor?

The dataset was collected from <a href="https://www.kaggle.com/datasets/rsrishav/youtube-trending-video-dataset?select=US_youtube_trending_data.csv">Kaggle</a> and continuously updated from the YouTube platform, including videos from the Top Trending US section, spanning from August 12, 2020, to October 13, 2023. The dataset consists of 231,787 rows with 16 data fields:

| Variables        | Description                                  |
|-------------------|----------------------------------------------|
| `video_id`          | Video ID                                     |
| `title`             | Video title                                  |
| `publishedAt`       | Video upload/production timestamp           |
| `channelId`         | Channel ID                                   |
| `channelTitle`      | Channel name                                |
| `categoryId`        | Category ID (44 categories available)       |
| `trending_date`     | Trending date                               |
| `tags`              | Tags/labels for the video                   |
| `view_count`        | Number of video views                       |
| `likes`             | Number of likes on the video                |
| `dislikes`          | Number of dislikes                          |
| `comment_count`     | Number of comments                          |
| `thumbnail_link`    | Link to the video thumbnail                  |
| `comments_disabled` | Comment disabling status (true/false)      |
| `ratings_disabled`  | Rating disabling status (true/false)       |
| `description`       | Video content description                   |
