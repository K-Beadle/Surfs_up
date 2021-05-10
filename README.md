# Surfs_up

## Analysis Overview
To analyze weather data on the Hawaiian island of O'ahu for a client who wants to open a Surf &amp; Shake shop.


## Results
Three major points that should be highlighted:

- During the month of June the average temperature was 74.9 degrees fahrenheit. The total number of weather observations during the month was 1700.

![June_statistics](https://user-images.githubusercontent.com/78178900/117601880-f69eda00-b114-11eb-9399-68a8e1ac9f3f.png)

- During the month of December the average temperature was 71 degrees fahrenheit. The total number of weather observations during the month was 1517.

![December_statistics](https://user-images.githubusercontent.com/78178900/117601896-ff8fab80-b114-11eb-9bcd-7b9293a4534d.png)

- Excluding the total count and std.dev. the largest delta between any two measurements is only 8 degrees between the minimum value. The next largest is only 4 degrees between the 25 percentiles and the smallest is only 2 degrees between the maximum temeratures.


# Summary
Based on the results of the summary statistics it appears that the two months are not very different in temperature. However, people in warmer areas could be more sensitive to temperature changes even if it is not that drastic. So, although the avg difference in temperature between the two months is 4 degrees it may be just enough to keep people inside because they want the warmer weather. 

Moreover, the maximum temperature for both months is above 80 degrees. This could be a good indication that during both times of the year you will have similar weather and could also be a good indication that you will have people craving ice cream even if they don't want to surf.

I'd like to see the amount of rain and its statistics. Based on the following chart, it appears it is worth looking into. I recommend writing a query for the rain statistics for both months as well.

![percipitation](https://user-images.githubusercontent.com/78178900/117602373-1aaeeb00-b116-11eb-9621-e3b7ba13a321.png)

With querys for both months that gather temperature statistics and the rain statistics, I recommend writing and additional query for the weather station that is closest to the location of the Surf & Shake shop so the client can have the potentially most accurate temperature and rain statistics.
