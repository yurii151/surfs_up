## Overview of the Analysis

### Purpose

The purpose of this analysis is to try and convince investors that an ice cream shop is valuable year round operation to invest in. We do this by getting using a data base contaning weather information in Hawaii and queringing to find the average temperature in June and December and describing the statistics to come to our conclusion.

## Results

### June

The first month that was queried was June. After putting the queried in a dataframe, the results look like this:


<img width="153" alt="Screen Shot 2022-01-05 at 2 35 09 PM" src="https://user-images.githubusercontent.com/92888170/148299334-6d2a517a-f489-4483-99b1-b261d0e01f05.png">

Now in this form, the data isn't of much use to us. Luckily, we can use the .describe() function on the June dataframe and it gives much more workable information:

<img width="153" alt="Screen Shot 2022-01-05 at 2 38 01 PM" src="https://user-images.githubusercontent.com/92888170/148299590-c30bbb15-64cc-48e2-a8f7-b5b1d097ac51.png">


Now this screenshot gives a much better picture of whats going on in the Dataframe. Some key take aways:

  - There were 1,700 recorded June temperatures, with an average temperature of 74.9 degrees.
  - The min temperature is 64 degrees, while the max temperature is 85 degrees.
  - The lower quartile is 73 degrees, while the upper is 77 degrees, so thee interquartile range is 4 degrees. 

### December

The second month that was queried was December. After putting the queried in a dataframe, the results look like this:

<img width="153" alt="Screen Shot 2022-01-05 at 2 46 30 PM" src="https://user-images.githubusercontent.com/92888170/148300493-fcd3bfbc-f4db-491b-bb33-fdfee90a7199.png">


Much like with the June data, we need to use .describe() on the December dataframe. After doing that we get:

<img width="153" alt="Screen Shot 2022-01-05 at 2 48 33 PM" src="https://user-images.githubusercontent.com/92888170/148300703-b72c7c8d-a23a-4873-95bc-69611cc9a937.png">

We can see:

  - There were 1,517 recorded December temperatures, with an average temperature of 71.0 degrees.
  - The min temperature is 56 degrees, while the max temperature is 83 degrees.
  - The lower quartile is 69 degrees, while the upper is 74 degrees, so thee interquartile range is 5 degrees. 


### Comparing the Results

Even though there were more June temperatures than December temperatures, there is enough of both to confidently compare the results of each month:

  - The average temperature of June was 3.9 degrees higher than in December.
  - December was an all around colder month than June, with the min in December being lower than June's and the max in December being lower than June's.
  - The weather was also more variable in December compared to June. The IQR for December was larger than for June.


## Summary

Based on the information that I analzyed in on temperatures in June and December, I would say that there isn't much of a difference in the climate in June vs the climate in December. December is an overall colder month, but the weather in December isn't cold enough to be an issue for the shop in the colder months.  

One query I would use on the data would be to sort the temperature from highest to lowest to see if there are any immediate things that are intersting in the timning of the hottest days of the months (if they occur on or around the same days). Another query I would do would be to group the results by date to see what day is the hottest of the month of June to plan a promotion around that time. 
