# Adobe-Behaviour-Smulation-Challenge
# Task: 
This task focuses on behavior simulation, where the goal is to give the user, an estimated number of likes that a particular tweet will recieve on twitter if the tweet is posted on the platfrom from the community. Therefore, the outline of this task was to make a machine learning model that will simulate the people present on twitter and give a numerical value that will correspond to the number of likes it may recieve on the platform.
# Appprocah:
Extracted visual features using ViT and textual features using BERT from media and text provided in Twitter dataset.
Trained a CNN model to combine all the different media features into a single visual feature.
Applied cross-attention mechanism to combine both the textual and visual features into one.
Incorporated date and time feature using the heatmap values of Twitter user engagement data.
Trained a Regression model to predict the number of likes on the Twitter post using the extracted features.
Trained an LSTM model first to extract the caption and then the tweet content from the media features
