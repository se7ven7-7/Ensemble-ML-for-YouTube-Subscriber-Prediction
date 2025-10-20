## Dataset: 
https://www.kaggle.com/datasets/thedevastator/youtube-video-and-channel-analytics

## Problem Statement:

On YouTube, knowing how many subscribers a channel might get is very important for creators, marketers, and analysts. Subscriber count is a key measure of a channel's popularity, audience interest, and potential success. However, it is hard to predict subscriber counts because many different things affect user behavior.

This project focuses on building a machine learning model to predict YouTube channel subscriber counts. We use different types of data from videos, such as numerical features and categories, to make these predictions. Our process includes cleaning the data, analyzing it, selecting useful features, and testing several machine learning models. We also improved the best models by tuning their settings and using ensemble methods like bagging and stacking.

By predicting subscriber counts, this project aims to give useful insights into what helps a channel grow. These predictions can help creators and marketers make better decisions to increase their channel's success.


## Dataset Describe:

The dataset has 575,610 rows, 26 columns. Types of variables included are: Numerical variables, Categorical variables and Data/Time variables.

**Video Performance Metrics:**
videoViewCount, videoLikeCount, videoDislikeCount, VideoCommentCount

**Channel Performance Metrics:**
channelViewCount, subscriberCount, channelCommentCount, videoCount, channelelapsedtime

**Engagement Ratios:**
likes/subscriber, views/subscribers, dislikes/subscriber, comments/subscriber, likes/views, dislikes/views, comments/views, likes/dislikes, totalviews/channelelapsedtime, views/elapsedtime

**Video and Channel Identifiers:**
channelId, videoId, videoCategoryId

**Derived Ratios and Counts:**
totvideos/videocount, totviews/totsubs

**Temporal Variables:**
elapsedtime, videoPublished
