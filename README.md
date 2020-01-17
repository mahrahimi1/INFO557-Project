## Overview

Given:

- a tweet

Task: classify the tweet as zero or more of eleven emotions that best represent the mental state of the tweeter:

- anger (also includes annoyance and rage) can be inferred
- anticipation (also includes interest and vigilance) can be inferred
- disgust (also includes disinterest, dislike and loathing) can be inferred
- fear (also includes apprehension, anxiety, concern, and terror) can be inferred
- joy (also includes serenity and ecstasy) can be inferred
- love (also includes affection) can be inferred
- optimism (also includes hopefulness and confidence) can be inferred
- pessimism (also includes cynicism and lack of confidence) can be inferred
- sadness (also includes pensiveness and grief) can be inferred
- suprise (also includes distraction and amazement) can be inferred
- trust (also includes acceptance, liking, and admiration) can be inferred

## Evaluation

The evaluation metric is multi-label accuracy (or Jaccard index). Since this is a multi-label classification task, each tweet can have one or more gold emotion labels, and one or more predicted emotion labels. Multi-label accuracy is defined as the size of the intersection of the predicted and gold label sets divided by the size of their union. This measure is calculated for each tweet, and then is averaged over all tweets in the dataset.
