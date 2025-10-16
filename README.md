## Finetuning-pretrained-model-assignment-3
This repository contains my approach for finetuning a DistilBERT model for the task of sentiment analysis on mental health.

## Motivation
Mental health is an important part of an individual’s well-being, affecting how individuals think, feel and behave. Despite its importance, it is often overlooked or neglected because the symptoms are not as easily identified, unlike physical health. The first step in promoting mental wellness then, is to promote self-awareness. This project aims to finetune a DistilBERT model to build a classifier for detecting signs of mental health issues given social media or clinical text.

## Dataset
The dataset taken from ([https://www.kaggle.com/datasets/suchintikasarkar/sentiment-analysis-for-mental-health/data](url)) consists of statements written by people labeled with a certain mental health status. This data have been sourced from social media posts, Reddit posts, Twitter posts, and more. There are 7 statuses: Normal, Depression, Suicidal, Anxiety, Stress, Bi-Polar, Personality Disorder. 

## Finetuned models
I have experimented with two methods for finetuning DistilBERT model on the mental health data. The first is a full finetuning. The second is by Low-Rank Adaptation (LORA).

## Platform
These models were trained on Google Colab using the T4GPU.
