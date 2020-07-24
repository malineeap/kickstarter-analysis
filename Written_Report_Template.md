# Kickstarting with Excel

## Overview of Project

### Purpose
  The purpose of this analysis is to better understand what factors influence Kickstarter Theater campaign outcomes. We will specifically evaluate how the Launch Date and Funding Goals of prior Theater campaigns have contributed to their success or failure. Knowing this information provides guidance for similar future projects and creates a comparison baseline for the recently completed Fever campaign. 

## Analysis and Challenges
  This analysis was completed in Excel using a Kickstarter data set of all campaigns initiated between May 2009-March 2017. Pivot tables and charting methods were applied to the data set to identify key learnings. The analysis focuses specifically on the Theatrical category and on the Plays sub-category.
### Analysis of Outcomes Based on Launch Date

![chart1](https://github.com/malineeap/kickstarter-analysis/blob/master/Resources/Theater_Outcomes_vs_Launch.png)

  Looking at the chart, we see that the best months to launch a theatrical campaign are May-July, or the summer season. We also see that the worst month to launch a campaign is December.  Interestingly, in every month except December the success rate for a Theater campaign is >50%, meaning in most cases over half of the Theater campaigns will be successful regardless of the launch month.  However, the likelihood of success is maximized in the May-July summer months where the lowest success rate is 87 successes out of 138 campaigns in July, or 63%, and the highest success rate is May with 111 successes out of 166 campaigns, or 67%.

### Analysis of Outcomes Based on Goals

![chart2](https://github.com/malineeap/kickstarter-analysis/blob/master/Resources/Outcomes_vs_Goal.png)

  Comparing outcomes in relation to their funding goals reveals that it is best to aim for a goal of under $5,000 for plays.  73% of the plays in this funding range were successful in their outcomes, which is 529 campaigns out of 720 in our data set.  When the goal exceeds $5,000, the number of successful campaigns drops to 50%, or 165 campaigns out of 327.  At $20K and above we see that failures generally overtake successes as the more likely outcome.  However, we do see a return to a favorable 67% success rate for campaigns with a goal between $35-45K.  This is something to research further, keeping in mind that currently less than 1% of all campaigns for plays fall into this range.  This could be an unexplored area of opportunity, but we need to explore further to understand the contributing factors and possible risks.  Lastly, it is worth noting that 68% of all plays already fall in the optimal <$5K target range.

### Challenges and Difficulties Encountered

  There are a few limitations to consider when consulting this data set for our analysis.  One limitation is the age of the data.  The most recent campaign in the data set was a Theater campaign from March 2017, or over 3 years ago.  To feel more confident about current campaign trends, it would be best if we could get a more recent extract of Kickstarter data.  Another limitation is the depth of information available about how the campaign was presented on Kickstarter.  We have basic information such as Category/Sub Category and a brief blurb, but a look at the Kickstarter website reveals there are many ways a campaign can differentiate itself to attract backers.  Some Theater campaigns offer incentives, such as preferred seating, while others have links to supporting media (videos, websites) that give more detail about the project and its creators.  This can be very influential in someone’s decision to support a campaign and would be extremely relevant to the analysis.

Some other tables/graphs that could be created:
-	Level of failure: Do we have a number of campaigns that came very close to their funding goal?  Can we determine what could be changed about the campaign to boost its outcome to success?

-	Spotlight and Staff Pick: How do these variables influence campaign outcome?  A quick pivot shows a 100% success outcome for Theater campaigns with Spotlight = TRUE.
Challenges encountered were mostly related to formatting of the dates and working with them within the pivot tables.  The Campaign dates are an important part of this analysis and it took a little extra time to ensure they were pulling into the analysis correctly.


## Results
To re-cap, final results indicate the following:
-	Best months to launch a Theater campaign are May-July, worst month is December.
-	For plays, it is preferred to keep the Funding Goal under $5K, however there is some potential opportunity at $35-45K that could be explored further.
-	We should look further into getting a fresher data set, and examining how promotions such as special marketing features or promotions influence outcomes.
