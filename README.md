# Canada_YbAnalysis

canada-ybanalysis.ipynb dosyası kod dosyamdır diğerini canada-ybanalysis (5) yanlış yükledim ve silemedim geri maalesef.
Kaggle: https://www.kaggle.com/code/itselif/canada-ybanalysis

# Project Objective:
This project aims to analyze and predict the view counts of YouTube videos in Canada. The dataset includes variables such as the video's category, title, tags, comment count, likes, and dislikes. This analysis seeks to understand the factors affecting the popularity of videos and develop data-driven models to more accurately predict the view counts of future videos.

# Dataset:
The dataset used consists of 40,882 rows. The column names are as follows:
•	video_id: A unique identifier for each video.
•	trending_date: The date when the video was trending on YouTube.
•	title: The title of the video.
•	channel_title: The name of the channel that uploaded the video.
•	category_id: The category ID to which the video belongs.
•	publish_time: The time when the video was published.
•	tags: Keywords (tags) added to the video.
•	views: The number of views the video has received.
•	likes: The number of likes the video has received.
•	dislikes: The number of dislikes the video has received.
•	comment_count: The number of comments on the video.
•	comments_disabled: Whether comments on the video are disabled (True/False).
•	ratings_disabled: Whether the like/dislike feature is disabled (True/False).
•	video_error_or_removed: Whether the video is faulty or removed (True/False).
•	description: The description text of the video.
•	Video_Category: Categories include Entertainment, News & Politics, People & Blogs, Comedy, Music, Sports, Film & Animation, Howto & Style, Gaming, Science & Technology, Education, Travel & Events, Pets & Animals, Autos & Vehicles, Shows, Unknown, and Movies.

# Technologies Used:
The main technologies used in this project are:
•	Python
•	Pandas and NumPy (data processing)
•	Scikit-learn (machine learning models)
•	Matplotlib and Seaborn (data visualization)

# Model Selection:
Various supervised and unsupervised learning algorithms were tested in the project, including:
•	Linear Regression
•	Decision Trees
•	KMeans
•	DBSCAN
Models were evaluated using metrics such as MSE and R². The model with the best performance, after specific hyperparameter tuning, was selected. The Random Forest Regressor demonstrated the best performance, predicting view counts with 90% accuracy.


