# YouTube Adview Prediction
Machine Learning Project under Guidance of Internship Studio

# Data Description

The file train.csv contains metrics and other details of about 15000 youtube
videos. The metrics include number of views, likes, dislikes, comments and
apart from that published date, duration and category are also included.

The train.csv file also contains the metric number of adviews which is our
target variable for prediction.

# Context

Youtube advertisers pay content creators based on adviews and clicks for the
goods and services being marketed. They want to estimate the adview based
on other metrics like comments, likes etc. The problem statement is therefore
to train various regression models and choose the best one to predict the
number of adviews. The data needs to be refined and cleaned before feeding
in the algorithms for better results.

# Attribute Information

'vidid' : Unique Identification ID for each video

'adview' : The number of adviews for each video

'views' : The number of unique views for each video

'likes' : The number of likes for each video

'dislikes' : The number of likes for each video

'comment' : The number of unique comments for each video

'published' : The data of uploading the video

'duration' : The duration of the video (in min. and seconds)

'category' : Category niche of each of the video

# Objective

To build a machine learning regression to predict youtube adview count based
on other youtube metrics.
