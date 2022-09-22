# PyBer Analysis
## Overview
The purpose of this report is to analyze all of the PyBer rideshare data from January to April of 2019 and create a visualization. This is done through merging two data sets, grouping subsets, retrieving total and average sums and finally charting the results.
## Results
Our first set of results can be seen in the summary dataframe which shows the difference in fares, drivers and avgerages per city type.

![PyBer Summary DataFrame](https://user-images.githubusercontent.com/111290810/191638566-6913d94b-d926-4463-9c0d-8d189806cea7.PNG)

Seen here, there are large but scaling difference in all summary statistics when comparing each city type. Rural cities have the least number of rides and drivers, the smallest total fare and the most expensive average fare per ride and average fare per driver. On the other hand, urban cities have the most rides and drivers, the most total fare and the least expensive average fare per ride and average fare per driver. The most notable comparison in this dataframe, however, is the number of total drivers as a share of the total rides. While both rural and suburban cities had more rides than total drivers, urban cities had more total drivers than rides. Theoretically this means that each driver in rural and suburban cities completed at least one ride, but a significant number of drivers in urban cities did not complete even one ride.

The second set of results can be seen in the graph created by comparing the total fares per week per city type between January and April 2019.

![PyBer Fares per Week per City Type Fig](https://user-images.githubusercontent.com/111290810/191638601-a7ed01f3-56a5-4024-ad3c-3f08cf094a42.png)

With this chart the difference in total fares between each city type is clearly seen. Additionally, looking at the total fares per week per city type shows some clear differences in customer needs depending on the time of year and the type of city. For example, both urban and rural cities see a large spike in total fares at the end of March, where suburban cities have a slight decrease during this time, but a large spike in the middle of April, where urban and rural cities decline.
## Summary
1) The first recommendation would be addressing the disparity between total drivers and total rides in urban cities. Resources here could be better spent because it is the only area where there exists more drivers than number of rides. This can be helped by either decreasing the number of drivers (thereby also increasing the average fare per driver in this area) or increasing marketing expendeture in urban areas to attract more customers, thereby utilizing each employed driver.
2) The second recommendation would be to increase marketing expendature during peak times as seen in the fares per week type, such as during the middle of Februrary and the end of March in order to attract even more customers when, as the data shows, more people are seeking rideshares.
3) The third recommendation would possibly be to raise fares in urban cities. There exists quite a large discrepency between suburban and urban total fares when compared to their relative total drivers. Where suburban cities earned ~$20,000, urban cities earned double that at ~$40,000. However, suburban cities have only ~500 drivers, where urban cities have not double, but four times the number of drivers at ~2400. This disparity is shown more comprehensively in the average fare per drivers column, where suburban drivers earn ~$24 more per fare.
