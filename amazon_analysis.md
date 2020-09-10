## Amazon Vine Review program analysis

This report is focused on presenting the most important findings of Amazon's Vine program where reviewers receive free products in exchange for reviews. The steps that were followed are going to be presented as well as the results from these.

* First, the dataset used for the analysis was the video game dataset.
* The data set was filtered by reviews with twenty or more votes. It has to be mentioned that at least half of which were marked helpful. This was done calculating the rate between helpful votes and total votes greater than 0.5.
* Then, the dataset was filtered by Vine reviews and Non-Vine reviews, resulting in two new dataframes. Here, basical statistical information was obtained, showing that non-vine reviews has a greater variance(std=1.64) than vine reviews(std=0.98). Also, the mean for star rating, helpful votes, and total votes from vine reviews was greater than non-vine reviews.
* The rate between five star rating and total rating was calculated for both vine reviews and non.vine-reviews. The results show that over 50 percent of vine reviews had a 5 star rating. On the other hand, 39 percent of non-Vine reviews had a 5-star rating.


