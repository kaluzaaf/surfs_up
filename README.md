# surfs_up
## Overview of the statistical analysis:
The purpose of the project is to compare the weather in Hawaii between June 2010 and December 2010. We accomplish this by building a query of the Hawaii SQLite document to pull out the June weather and analyze it, then we do the same for the December weather. The data in the SQLite file was derived from several weather stations around the Hawaiian Islands.

## Results:
There are three main differences between June and December weather. There are 11% fewer December weather readings than June weather readings, December appears to have some cold weather outliers, and the temperature variation is small over the majority of the temperature range. 

### Fewer December readings
There are 1700 weather readings in June vs 1517 in December. As an analyst, this ~11% reduction could have an adverse impact on the accuracy of the overall analysis and is something we should think about potentially correcting for in future analysis by reducing the number of June readings to 1517. 

### December's minimum temperature appears to be an outlier
December’s minimum temperature was 56 vs 64 for June. This is notable because this 8-degree swing is much larger than observed across the range of other temperatures where normal swings were only 2 to 3 degrees. This cold snap could negatively affect the accuracy of our analysis and might need to be deleted if it was a true weather anomaly that is not expected to repeat in the future. 

### General consistency of the weather
Hawaii weather is remarkably consistent. The 25th, 50th, 75th and max temperature range between the coldest and hottest months were 4, 4, 3, 2 degrees respectively. This demonstrates that Hawaii's weather generally stays in a very narrow band of temperature ranges. The Standard Deviation measurement also demonstrates this, through it might have been inflated due to unusually cold temperature in December. More analysis would be needed to prove out this theory though and is beyond the scope of this project.

![Weather_dec](https://user-images.githubusercontent.com/100163289/167235451-50528ef3-def0-4769-ac4d-6670b0da1b1a.png)
![June_weather](https://user-images.githubusercontent.com/100163289/167235467-924a13fd-5b03-4c57-9693-2d57579fd307.png)

## Summary:
The analysis shows that weather should not be a limiting factor in the shops success as the weather is conducive to surfing and ice cream eating year-round. I would want to run a query to see how often it rains at different times of the year and how consistent the winds are at different times and in the location where the surf shop will be opened. Frequent rain and strong wind could certainly negatively impact the shops viability. From our analysis, I would say the weather will not be the limiting factor to the shop's economic success.!
