# Motivation

## What data are we working with?

The domain this project explores is different posts on Reddit found on the subreddit 'Change My View', or r/CMV, where users regularly post controversial questions and discussions in the community.

## What is the goal of this work?

The goal of this project is visualize the distribution of people's emotions and their reactions to posts of different types. We expect their comments' emotions to follow suit relative to the emotions of the post topic, but this is to be explored.

## How is this achieved?

This is achieved by leveraging the RoBERTa base Go Emotions model found on HuggingFace. This sentiment analysis pipeline is used to get emotions for a given text input, and ranks them by most likely probability (see code for examples). The Go Emotions dataset is comprised of 28 unqiue emotions and was trained on Reddit data, making it and the respective model an ideal candidate for this project's goals.

## Where can I learn more about this project?

Find the RoBERTa Go Emotions model link here (from HuggingFace)
https://huggingface.co/SamLowe/roberta-base-go_emotions

Find the Go Emotions dataset link here (from HuggingFace)
https://huggingface.co/datasets/go_emotions
