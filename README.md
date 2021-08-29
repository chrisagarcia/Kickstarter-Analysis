# Kickstarter Analysis

### Introduction
  Louise created a Kickstarter for her play, *Fever*, that met its funding goal in a short 
time. Now she wants an analysis of some relevant data to explain some of the trends that 
might have played a part in that success. An insight into these trends could allow her to 
replicate her experience in a new venture. For this analysis, I proccessed a dataset of 
just over 4,000 Kickstarter projects. My goal was to extract a few common variables of 
successful and unsuccessful campaigns.

### Methods of Analysis and Challenges
In order to best advise Louise, I analyzed funding trends with regard to each
project's launch date, looking closely at the success rates of each month independent
of the year. I also tried to uncover funding trends as a function of the projects goal. 
This was accomplished using Excel and some of Excel's in-built data tools. I was able to
filter, sort, and recombine the data into relevant pools which I then displayed with graphs
to show pertinent trends. The challenges of processing this data were mostly to do with
organizing and finding applicable data. This was easily solved with Excel functions like
VLOOKUP, and COUNTIFS as well as with Excel's filter and pivot chart functionality. Another
challenge might have been determining the validity of any trend with only 4000 data points.
I might solve this with more data from Kickstarter if available, and, if not, data from 
other crowdfunding sites like GoFundMe would work just as well.

Now, onto some trends derived from the Kickstarter data.

### Results and Conclusions
This line chart, titled "Theater Outcomes Based on Launch Date",
![Theater Outcomes Based on Launch Date](https://github.com/chrisagarcia/Kickstarter-Analysis/blob/main/Theater_Outcomes_vs_Launch.png)
shows a clear spike in successful theater campaigns launched at the border of spring and summer.
It is worth mentioning that this graph shows the number of successful(blue), failed(orange), 
and canceled(grey) campaigns for each month *independent* of the year. However, if you filter
through each year to investigate further, you can see that the trend doesn't seem to be random.
Each year, including a few years with insufficient data for individual analysis, follows this trend.
Between April and August, successful campaigns remain mostly above 60% of the total. This trend 
tops out in May at ~67% successful campaigns, declining thereafter. The data show that, historically,
December has been the worst month to start a theater campaign on Kickstarter. This could be
due to consumers tightening their budgets for the holiday season as excess money begins to flow
to holiday activities, although this is purely conjecture as the data do not contain any
information that could confirm this.

In this chart, "Kickstarter Outcomes for Goal Ranges",
![Kickstarter outcomes for Goal Ranges](https://github.com/chrisagarcia/Kickstarter-Analysis/blob/main/Outcomes_Goal_Ranges.png)
I show that, within the dataset, the success of a Kickstarter campaign for a play correlates
to its goal amount. Assuming that this data is representative of the whole, it can be said that 
a new Kickstarter with a lower funding goal is more likely to be successful than one with a
higher goal. Specifically, the data show that campaigns with a goal between $1,000 and $4,999
have the highest success rates at 100%. This category, $1,000-$4,999, contains 43% of the total
data for this subcategory, so, I am willing to treat it as significant. On the other end of the
spectrum, the lowest success rate for groupings of funding goals can be found at the $4,500-$4,999
range. Though, it only contains one data point, so we should ultimately disregard it. In fact, 
the $15,000-$19,999 range makes up only %3 of the overall play data and everything past that range
makes up even less. It would make much more sense to look individually at any play asking for
$20,000 or more in order to form a qualitative analysis on their successes and failures rather
than a quantitative one. Conclusively, I think this dataset shows us that lower campaign goals
more frequently receive pledge amounts that match or exceed those goals. This seems intuitive, 
but it rules out any notion that a more ambitious approach is necessary. It also provides some
good insight into Louise's successful $10,000 campaign. Since it's clearly outside the range of
goal amounts that seem to be more easily funded, she is clearly doing something right promoting
her play.

### Limitations and Solutions
This analysis will provide useful general knowledge of kickstarter play campaigns for Louise's
retrospective, and presumed future campaign planning. However, their remain some limitations. 
For one, I would say that while the dataset is large enough to see soem trends in these projects, 
it is hard to say with confidence that these trends would carry over to a larger dataset. The
"Outcomes for Goal Ranges", for instance, has a few ranges with less than 10 datapoints. It seems
that a larger dataset would greatly benefit this analysis. Another potential limitation of this
analysis is the lack of specific data for each point. It might be useful to analyze the effectiveness
of theater-related projects as a function of their location. Maybe Louise could use that information
to weed out some high earning outliers with a common location. If a city like New York, with its 
history of popular theater, is artificially raising the average earnings of these projects, it could
help to filter out New York based projects.
