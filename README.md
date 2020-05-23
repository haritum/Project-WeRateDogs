# Project: WeRateDogs
In this project, we are going to wrangle, analyze and visualize tweets data of **WeRateDogs** Twitter user.

## Background of WeRateDogs:
The Twitter account [**WeRateDogs** (@dog_rates)](https://twitter.com/dog_rates?ref_src=twsrc%5Egoogle%7Ctwcamp%5Eserp%7Ctwgr%5Eauthor) is devoted to humorously reviewing pictures of dogs doing adorable poses, often giving them scores above 10/10. It has close to 8.7 million followers as of May 2020.

## Details:
We are going to do
- Data wrangling i.e., Gather, Assess and Clean relevant tweet data of **WeRateDogs** from [multiple data sources](#the-data).
- Storing, analyzing, and visualizing the wrangled data.
- Reporting on
    1. Wrangling efforts
    2. Data Analysis and Visualization

## Contents:
Organization structure of this project is as follows:

|- data/
    - twitter_archive_enhanced.csv
    - image_predictions.tsv
    - tweet_json.txt
|- addons/
    - twitter_api.py
|- scripts/
    - wrangle_act.ipynb
    - wrangle_report.ipynb
    - wrangle_act.ipynb
|- reports/
    - wrangle_report.html
    - wrangle_act.html
|- README.md


### The Data:
1. Enhanced Twitter Archive - The **WeRateDogs** twitter archive contains basic tweet data for all 5000+ of their tweets.

2. Additional Data via the Twitter API - Retweet count and favorite count will be gathered from Twitter's API.

3. Image Prediction File: A neural network that can classify breeds of dogs.


### Key Points:
- [ ] Original ratings (no retweets) that have images.
- [ ] Assess and clean atleast 8 qualities.
- [ ] Assess and clean atleast 2 tidiness issues.
- [ ] Tweet [image predictions neural network](https://d17h27t6h515a5.cloudfront.net/topher/2017/August/599fd2ad_image-predictions/image-predictions.tsv) is hosted on Udacity's server.


### Visual Summary of the Project:
This is a new feature yet to be added.


## Acknowledgments:
1. Twitter API
2. Udacity Data Analyst Nanodegree
3. @WeRateDogs Twitter user
4.


