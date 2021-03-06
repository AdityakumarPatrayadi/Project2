# Twitter Data Analysis using Apache Spark

Nowadays, data is growing and accumulating faster than ever before. Currently, around 90% of all data generated in our world was generated only in the last two years. Due to this staggering growth rate, big data platforms had to adopt radical solutions in order to maintain such huge volumes of data.

Spark Streaming discretizes the data into tiny, sub-second micro-batches. In other words, Spark Streaming receivers accept data in parallel and buffer it in the memory of Spark’s workers nodes. Then the latency-optimized Spark engine runs short tasks to process the batches and output the results to other systems.Unlike the traditional continuous operator model, where the computation is statically allocated to a node, Spark tasks are assigned to the workers dynamically on the basis of data locality and available resources.This enables better load balancing and faster fault recovery.

One of the main sources of data today are social networks.We worked on dealing, analyzing, and extracting insights from social network data in real time using one of the most important big data echo solutions out there—Apache Spark, and Python.

We build a simple application that reads online streams from Twitter using Python, then processes the tweets using Apache Spark Streaming to identify hashtags and, finally, returns top trending hashtags and represents this data in real-time.We also worked on historical data and made analatical insights on it.

## Technologies used

- Apache Spark
- Git + GitHub
- pySpark
- Python

## FEATURES

1. Process the downloaded data analyze the data.
2. Find, organize, and format Historical Data of any particular user.
3. Having a developer API Account of Twitter that helps in Direct Authentication to Live Data
4. Filter out the Hashtag from live as well as historical Data.

## Problem Statement

- Retrieving the trending hashtags of a famous personality.
- Analyzing the real time streaming tweets on famous personality.
- Retrieving the information of a person who retweeted on a particular hashtag.
- Historical Data Analysis on Twitter Data.

## API & Required Modules

- Twitter API - for Building Apps and analyzing on twitter streaming & historical data
- Tweepy - is an open source Python package that gives you a very convenient way to access the Twitter API with Python.

## Contributors

Here list the people who have contributed to this project.
 
 - Hemanth Soma
 - Jayshree C S
 - Suresh Mallakunta
 - Aditya Kumar P

## Reference 

* https://www.followersanalysis.com/
* https://api.twitter.com/2/users/:id/likes
* https://www.geeksforgeeks.org/python-status-object-in-tweepy/
* https://developer.twitter.com/en/docs/tutorials/getting-historical-tweets-using-the-full-archive-search-endpoint
* https://www.kaggle.com/vidyapb/elon-musk-tweets-2015-to-2020/version/1
