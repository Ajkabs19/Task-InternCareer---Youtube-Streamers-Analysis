# Youtube Streamers Analysis

## About The Dataset

It contains valuable information about the top YouTube streamers, including their ranking, categories, subscribers, country, visits, likes, comments, and more. Download [here](https://drive.google.com/file/d/1TRPPHAA2nn2NtpHn5GZaxKYVKzj27jQ5/view?usp=drive_link)

### Project Task

The task is to perform a comprehensive analysis of the dataset to extract insights about the top YouTube content creators

### Table of Content
- [Data Exploration](#data-exploration)

- [Trend Analysis](#trend-analysis)

- [Audience Study](#audience-study)

- [Performance Metrics](#performance-metrics)

- [Content Categories](#content-categories)

- [Brands and Collaborations](#brands-and-collaborations)

- [Benchmarking](#benchmarking) 

- [Content Recommendation](#content-recommendation)

### Data Exploration

1. It contains 9 columns with 1,000 rows
2. The rank column seems quite okay.
3. The username column contains an inconsistent naming format, a blend of numbers and letters, and then a missing name which had to be filtered out
4. The category column has about 306 blank rows, which had to be removed due to their hugeness
5. The Counrtry column has 171 rows unknown. I decided to leave it.
6. The Visit column has a single value entered incorrectly in decimal. I assume it is a mistake and the decimal point was removed to have a balanced whole number
7. I figured that I wouldn't need the links in this analysis. So, I removed it.

Altogether after the data cleaning, about 695 rows of data were left. I assume it is still a good representation of the whole dataset. Hence, I continued with my analysis.

### Trend Analysis

Among the top YouTube streamers, each YouTube streamer is identified with a particular category, and the most popular categories were obtained by subscribers. There was no correlation between the number of subscribers and the number of likes or comments

### Audience Study

It is observed that there are regional preferences for specific content categories.

### Performance Metrics

An average of subscribers, likes, comments, and visits was done.
  
|Average of Suscribers|Average of Likes|Average of Comments|Average of Visits|
|---------------------|---------------|--------------------|-----------------|
|22415561.96|53473.59798|1558.793948|1210729.683|


### Content Categories

MÃºsica y baile category has the highest number of streamers. And certainly, there are a couple of other categories with exceptional performance.




### Brands and Collaborations

The given data is not enough to determine whether streamers with high-performance metrics received more brand collaboration and marketing campaigns

### Benchmarking

All (689) Streamers performed above average in terms of subscriptions
654 in terms of Likes performed above average
532 in terms of comments
670 in terms of Visits


### Content Recommendation 

Since the analysis shows that a significant portion dropped below average in Comments mostly, and then Likes much fairly, Youtube users can be given content recommendations based on top performing categories, especially the ones with the most comments engagements as top on the priority list, then Likes.



