# Project: WeRateDogs
In this project, we are going to wrangle, analyze and visualize tweets data of **WeRateDogs** Twitter user.

## Background of WeRateDogs:
The Twitter account [**WeRateDogs** (@dog_rates)](https://twitter.com/dog_rates?ref_src=twsrc%5Egoogle%7Ctwcamp%5Eserp%7Ctwgr%5Eauthor) is devoted to humorously reviewing pictures of dogs doing adorable poses, often giving them scores above 10/10. It has close to 8.7 million followers as of May 2020.

## Details:
We are going to perform
- Data wrangling i.e., Gather, Assess and Clean relevant tweet data of **WeRateDogs** from [multiple data sources](#the-data).
- Storing, analyzing, and visualizing the wrangled data.
- Reporting on
    1. Wrangling efforts
    2. Data Analysis and Visualization

## Contents:
Organization structure of this project is as follows:

|-data/
|-data/twitter_archive_enhanced.csv
|-data/image_predictions.tsv
|-data/tweet_json.txt
|
|-addons/
|-addons/twitter_api.py
|
|-notebooks/
|-notebooks/wrangle_act.ipynb
|-notebooks/wrangle_report.ipynb
|-notebooks/act_report.ipynb
|
|-reports/
|-reports/wrangle_report.html
|-reports/act_report.html
|
|-README.md


### Key Points:
- [ ] Original ratings (no retweets) that have images.
- [ ] Assess and clean atleast 8 qualities.
- [ ] Assess and clean atleast 2 tidiness issues.
- [ ] Tweet [image predictions neural network](https://d17h27t6h515a5.cloudfront.net/topher/2017/August/599fd2ad_image-predictions/image-predictions.tsv) is hosted on Udacity's server.


### Requirements:
- Python3.x

Make sure you have pip install on your machine to fiddle around with different python modules. If pip is not pre-installed, run:
```shell
    sudo apt-get install python3-pip
```
Some of the python modules don't come in-built with python3. You can download individual modules by running the following commands in your terminal.
```shell
    pip install --user wget
    pip install --user requests
```


### Visual Summary of the Project:
This is a new feature yet to be added.


## Acknowledgments:
1. Twitter API
2. Udacity Data Analyst Nanodegree
3. @WeRateDogs Twitter user
4.


