# #pint21 YouTube Statistics

### background and why
The Pint of Science is an annual festival born in 2013 in UK and now present is 30 countries (more info)[www.pintofscience.com].
in 2021, the Pint of Science festival #pint21 was run in 25 countries and a few of them (based on my analysis) decided to stream it to YouTube while other were using Zoom and others plateforms. 
I found the Pint of Science Norway end of 2019 and we have been running 2 editions (#pint20 and #pint21). Unfortunately all our events has been hosted and streamed online on Youtube - 3 hybrid event in Trondheim for #pint21). As the director since its creation I wanted to know how well we have been doing. 

It was the occasion to practive Python, Pandas and learn more about REST API and Tableau

### objetives:
-  How well we have done this year compare to last year
-  How well do we do compare to the others countries hosting #pint21. 

### methods and limits
1. I manually retrieved the id of each Pint of Science channel I could find on Youtube. I did not include the non-pint of Science channels hosting some Pint of Science events.

##### retrieve the #pint21 videos
With the Youtube data API and using the channelId of each country, I retrieved the videos published from 16.05.21 til 31.05.
*Luxury: I choose the 16.05 to not have to deal with the time zone of each country and why not 17-19.05, cause some countries have different dates for instance Norway hosted #pint21 19-21.05 and Australia had some events planned for week 21.*

Only 12 countries were streaming to Youtube.

##### retrieve the views:
With the list of video and their videoId, I could then fetch the statistics (viewcount) for each and so the number of views by country.



##### Plotting of the data
The collected data was plotted using Tableau.

### Results
on the 31.05.21,  PoSNO published 14 videos for #pint21 and we got a bit less than 1700 views in less than one week which is comparable to the views we cumulated for the 3  videos we did for #pint20 (plot to be done). 

Compare to the other countries of the PoS network it is not that bad, we are ranked in the middle for each metrics so I am kind of happy.

Our growing is shown through more volunteers and more collaboration.


The dashboard is available  [online](https://public.tableau.com/views/pint21YouTube-dashboard/Dashboard1?:language=en-GB&:display_count=y&:origin=viz_share_link)

with an update up to [31.05.21](https://public.tableau.com/views/pint21YouTube-dashboard/Dashboard1?:language=en-GB&:display_count=n&:origin=viz_share_link)