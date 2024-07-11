# Emotion Intensity Prediction in Tweets
Background and Significance
The current landscape of emotion datasets primarily focuses on categorical annotations without indicating the degree of emotion. These datasets often frame tasks as classification problems, where the goal is to identify one emotion out of many for a given sentence. However, for many applications, it is beneficial to understand the intensity or degree to which an emotion is expressed in text. This project addresses this gap by introducing a task where systems automatically determine the intensity of emotions in tweets.

Task Description
The task is to determine the intensity or degree of a specified emotion expressed in a given tweet. Each instance in this task consists of a tweet and an associated emotion X. The objective is to assign a real-valued score between 0 and 1 to each instance, indicating the intensity of emotion X felt by the speaker.

Score 1: Represents the maximum possible intensity of emotion X, indicating that the speaker feels the maximum amount of this emotion.
Score 0: Represents the minimum possible intensity of emotion X, indicating that the speaker feels the least amount of this emotion.
It is important to note that these scores are relative and serve to compare the intensity of emotion X across different instances. Higher scores correspond to a greater degree of emotion X, while lower scores correspond to a lesser degree.
