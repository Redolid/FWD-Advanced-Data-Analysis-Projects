# Flights Data Exploration

## Dataset

The data consists of information regarding 14 Million flight records divided on two years 2004 and 2008, including
Flight numbers, Arrival/Department Delay and other flight Attributes. The dataset can be found in the
Following drive Links [Here](https://drive.google.com/file/d/1pNCcmKZIKfuN1QMTM-pzbOzwwo1b0RF9/view?usp=sharing),



## Summary of Findings

In the exploration, I found that there was a strong relationship between the
Department Delay and Arrival Delays, also there is a weak relation between arrival delay and Weather delays the relationship is almost linear but with weak correlation. The Best time to travel is in fall/spring seasons on a saturday with the carrier being OO or US. for better service and much fewer delays

Log transformation helped me notice much information in distance/weeks/months variety over the years.

Outside of the main variables of interest, The Heatmap for numeric variables showed there is a strong relationship between CRSArrTime and DepTime/ArrTime, Actual and CRSElapsed time had a stunning correlation of .980

it's interesting to notice that some unique carriers have almost no weather delays also specific months have much fewer department delays

Distribution of carriers over months/days/years is almost the same except for years there is a visible difference in distribution of carrier over the years. we can investigate further about the Unique carriers and see if they help also check which has the most delays

Weather Affected flights much more in 2008 than 2004 which is clearly visible on the prev graph. also combined dataset shows a small correlation weather has a great factor on delays and it is to be considered when to fly!

Another interesting thing i found that some carriers have low Arrival Delays while having high WeatherDelays/Dep Delays. Which shows that some carriers handle delays better than others.

## Key Insights for Presentation

For the presentation, I focus on just the influence of the Weather Delay, Arrival/Department Delay, carriers, Seasons and days to travel on for fewer wait time and delays.

and leave out most of the intermediate derivations. I start by introducing the Distances in my dataset, followed by the distribution of Months, Then show the best day to travel comparing the two years and a graph with both of them combined.

Afterwards i added a scatter showing the positive correlation between weather delay and arrival delay, with a graph showing each year's delay per month which shows that 2008 delays are much higher than the ones in 2004.

At last i added 3 graphs showing number of flights per carrier, Department delays per carrier and Arrival delay per carrier which helped me choose 2 carries to be the best to fly with in an easy way for the user to understand and Decide for himself which is the best carrier.
