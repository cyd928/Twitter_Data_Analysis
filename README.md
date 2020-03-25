# Wrangling & Analysis of Twitter API Data



## Overview

> This analysis is focused on the WeRateDogs account from Twitter in order to provide
insights into the Tweets popularity by dog breed, rating scores as well as the number of
retweets/likes.

> The first step was gathering data. I loaded the Archive data from local drive using pandas’
read_csv function. Then I used the requests package to load the image_prediction file from
url and converted the file into .csv format. Finally, I pulled Twitter API in .txt file which I
converted into .json file, and then I translated the .json format into pandas dataframe named
retweet_fav_df , which makes the data easier to read.
The second step was assessing data. I assessed the three datasets individually and then
identified issues within each dataset as well as potential problems after merging them later
on.

> This analysis is part of a project I did for my Udacity onine course.