# surfs_up

## Overview:

The purpose of this analysis was to find the temperatures for the months of june and december for the new surf/ice cream shop in Oahu, Hawaii and provide statistical summarys for the months. This was done by using SQLalchemy to filter the data for the tempertures for the months June and December each year and then put the filtered data into a list then a dataframe. The data used for this analysis was taken from a sqlite file containing weather information over the years.

## Results:

![junetemps](https://user-images.githubusercontent.com/107213807/183263326-f757bb5e-d597-446b-8caa-6943d1a87d69.png)

![dectemps](https://user-images.githubusercontent.com/107213807/183263332-6071a342-b240-4dfb-b133-cbab30839b8b.png)


- When looking at the statistical summarys, a key difference is the the minimum temperature. In June the minimum temperature is 64 degrees while in December it was 56 degrees.
- Another important difference is the mean temperature of June is higher than December. While the difference isn't massive, it still means the weather is warmer throughout June.
- A key differnce worth noting is that the count of temperatures in June is higher than December. This means that some of the data for December is missing and the summary doesn't fully reflect the December weather. Part of the difference of count could come from the fact December has 31 days and June has 30. Since the data has many years, the difference in days add up. 

## Summary:

When analyzing the summaries, the shop may be less sustainable in December. The reasoning behind this is overall lower tempertures. Although the mean temperatures aren't that different, the difference in the minimum temperatures are quite large. With overall lower tempertures, there is less amount of time for people to be more likely to want to buy surfing equipment or ice cream. While the temperatures are still relatively warm, the business would have to be organized around the fact that tempertures will be lower and there might be less customers. To get a better idea of the sustainibility of the shop, more queries could be done. Filtering the data to show the preciptiation of June and December would give more insight to what month has more rain. For example, if there is more rain in December than June, the combination of the tempertature and preciptiation might make the number of potential customers even lower.
