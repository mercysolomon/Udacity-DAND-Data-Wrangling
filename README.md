## Udacity-DAND-Data-wrangling
‘WeRateDogs' is a Twitter account that posts pictures of dogs with a witty caption and a rating. These ratings mostly have a denominator of 10 and a numerator ranging from 10-15, at most.

I gathered data in three ways; Manually, programmatically, and from an API.
Manually, I downloaded the ‘twitter-archive-enhanced’ csv file provided for us in the classroom, and read it into a dataframe.

Programmatically, I downloaded an ‘image-predictions’ tsv file using the requests library and read that into a dataframe as well.

By means of a Twitter developer account, I gathered data from the ‘WeRateDogs’ account using the ‘Tweepy’ library. I queried Twitter’s API and extracted in JSON form, the retweet count and
favorite count for each tweet. This data was appended into a list, read line by line into a 'tweet-json.txt’ file and finally converted into a dataframe just like the other sources of data.

## Reports
* wrangle_act.ipynb includes the data wrangling process and analysis.
* wrangle_report.ipynb, wrangle_report.html: documentation for the data wrangling steps.
* act_report.ipynb, act_report.html: documentation of analysis and insights.
