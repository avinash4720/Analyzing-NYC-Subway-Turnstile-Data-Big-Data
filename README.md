# CS-GY 6513 Big Data Project
This project analysis was created by - Avinash Vijayarangan, Nagharjun Mathi Mariappan, Nishal Sundarraman, Vikram Balaji

## Introduction

The project titled "Analyzing NYC Subway Turnstile Data: Understanding subway ridership pattern and Commuter Behavior" aims to address the problems of regulating traffic during rush hours and maximizing ad viewership at subway stations. By analyzing MTA turnstile data for the past 10 years and performing exploratory data analysis using big data tools such as Pyspark, Spark ML, Kafka, and MongoDB, this project seeks to infer insights into subway ridership patterns and commuter behavior. The findings of this analysis will enable the identification of stations with the highest foot traffic and the prediction of which stations are likely to experience huge foot traffic at specific hours. This report highlights the importance of leveraging big data tools and analysis to improve the management of essential public infrastructure such as the New York City subway system.

## Architecture
![arch1](https://github.com/avinash4720/Analyzing-NYC-Subway-Turnstile-Data-Big-Data/assets/59311336/20fc9ce0-b36e-4dc6-bbf7-e3cf92eec542)

![arch2](https://github.com/avinash4720/Analyzing-NYC-Subway-Turnstile-Data-Big-Data/assets/59311336/6906ce1b-d522-4512-8c82-3814effe5f23)

## Code Walkthrough

1) The `1. Data` contains the ipynb file that downloads all datasets of NYC Turnstile data from 2014 to current year. You  can run locally through Jupyter Notebook or Google Colab.
2) To perform EDA on the daatsets, go to `2. Data` and run the ipynb file to get insights of the subway stations.
3) To stream the data, go to `3. Kafka` to stream running data of the current year.
4) To make ML predictions, run spark ML code in `4. SparkML`

## Results
![eda1](https://github.com/avinash4720/Analyzing-NYC-Subway-Turnstile-Data-Big-Data/assets/59311336/49d2543d-88f9-48a2-bfff-eb5b002deb8b)
![MeanEntriesbyyear](https://github.com/avinash4720/Analyzing-NYC-Subway-Turnstile-Data-Big-Data/assets/59311336/daa34107-abc3-4b9d-b3b9-2b5741a2b46c)
![Holiday impact](https://github.com/avinash4720/Analyzing-NYC-Subway-Turnstile-Data-Big-Data/assets/59311336/1e90be30-7b3e-4470-a2d7-3eaea46a24ab)
<img width="580" alt="results" src="https://github.com/avinash4720/Analyzing-NYC-Subway-Turnstile-Data-Big-Data/assets/59311336/fceaed5b-1ec8-4f9f-b69e-6db51a47583f">


