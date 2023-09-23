# TEDX-Talks-Regression

# Problem Objective

The primary goal is to create a predictive model capable of forecasting the number of views that videos uploaded to the TEDx website will receive, using a dataset that encompasses more than 4,000 TED talks with transcripts available in multiple languages.
# Project Work Flow

1. Library Importation
2. Dataset Retrieval
3. Data Cleansing
4. Exploratory Data Analysis (EDA) and Feature Engineering
5. Selecting Relevant Features
6. Training Regression Models and Tuning Hyperparameters
7. Concluding Model Selection

# Feature Information

talk_id: A unique identifier for each TED Talk video.

title: The title of the talk.

speaker_1: The primary speaker for the talk.

all_speakers: A list of all the speakers for the talk.

occupations: The occupations of the speakers.

about_speakers: Information about the speakers, such as their backgrounds and expertise.

views: The number of views the video has received.

recorded_date: The date the talk was recorded.

published_date: The date the talk was published on the TED Talks YouTube channel.

event: The name of the TED event where the talk was given.

native_lang: The language the talk was given in.

available_lang: The languages the talk is available in.

duration: The length of the video.(in sec.)

topics: The topics covered in the talk.

related talks: Other TED Talks that are related to this talk.

url: The URL of the video.

description: A brief description of the talk.

transcript: A transcript of the talk.

Target Variable: Views(The number of views the video has received.

# Model Implementation

Creating predictive models using a variety of regression techniques including linear regression, ridge regression, and lasso regression, as well as tree-based models like decision trees, random forests, gradient boosting, and XGBoost.

# Conclusion

Random Forest stands out as the most effective regression model for this task. Nevertheless, in the future, we may explore alternative techniques to potentially achieve even better results.
