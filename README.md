# UserEngagementPrediction
Machine learning approach to predict the engagement score of the video on the user level without any data points regarding the video/content itself
Problem Statement
ABC is an online content-sharing platform that enables users to create, upload and share content in the form of videos. It includes videos from different genres like entertainment, education, sports, technology, and so on. The maximum duration of the video is 10 minutes.
Users can like, comment and share the videos on the platform. 
Based on the user’s interaction with the videos, an engagement score is assigned to the video with respect to each user. The engagement score defines how engaging the content of the video is. 
Understanding the engagement score of the video improves the user’s interaction with the platform. It defines the type of content that is appealing to the user and engages the larger audience.



Objective
The main objective of the problem is to develop the machine learning approach to predict the engagement score of the video on the user level.



Data Dictionary
You are provided with 3 files - train.csv, test.csv and sample_submission.csv
Training set


train.csv contains the user and video information along with the engagement score
Variable
Description
row_id 
Unique identifier of the row
user_id
Unique identifier of the user
category_id
Category of the video
video_id
Unique identifier of the video
age
Age of the user
gender
Gender of the user (Male and Female)
profession
Profession of the user (Student, Working Professional, Other)
followers
No. of users following a particular category
views
Total views of the videos present in the particular category
engagement_score
Engagement score of the video for a user

 
Test set
test.csv contains only the user and video information, and you have to predict the engagement score
Variable
Description
row_id 
Unique identifier of the row
user_id
Unique identifier of the user
category_id
Category of the video
video_id
Unique identifier of the video
age
Age of the user
gender
Gender of the user (Male and Female)
profession
Profession of the user (Student, Working Professional, Other)
followers
No. of users following a particular category
views
Total views of the videos present in the particular category

 
Submission File Format
sample_submission.csv contains only 2 variables - row_id and engagement_score
Variable
Description
row_id
Unique identifier of the row
engagement_score
Engagement score of the video for a user

 
Evaluation metric
The evaluation metric for this hackathon is r2 score. 
