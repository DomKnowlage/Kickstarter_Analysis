# **Kickstarter_Analysis**
## **Overview**
My team and I have been combing through Kickstarter project data to evaluate an optimal time to launch a project for a client of ours
## **Analysis and Challenges**
Some of the main challenges we encountered had to deal syntax. We have some new members on the team that are just getting their feet wet with some of the various conditionals, especially when it came to the =COUNTIFS formula. When looking over the data I found my new comers forgot to add a 3rd line of criteria to our data pertaining to the outcomes based on goals they were doing =COUNTIFS(Kickstarter!D:D,">=10000",Kickstarter!D:D,"<14999")               
instead of =COUNTIFS(Kickstarter!D:D,">=10000",Kickstarter!D:D,"<14999", Kickstarter!F:F,"Successful") completly skewing the data. Luckily a quick chat with their supervisor cleared things up and we were able to get the results we needed.
## **Outcomes Based on Goals**
Based on the goals we can determine that the best range for success is between $20,000 to $30,000. Any higher amount results in a higher volatility which could add some additional stresses to the project. This analysis can be viewed here https://github.com/DomKnowlage/Kickstarter_Analysis/commit/47eddb5550eaed4d054c15e982cb502a0bb77d6a#diff-cc3f8653d7de4056f03f5c39a5e9b7e7ad2fd86e64fd1f3f38bfacf487b8212e 

##**Theater Outcomes Based on Launch Date**
Our client is interested in setting up a theater Kickstarter, we decided to compile some data that revolved around the success of Kickstarters based on the month that they were launched. We can conclude that the most success that comes in the summer months with May seeing the most success. Failures tend to stay stagnant throuhghout the year but there's a slight uptick in October we can conclude that we should steer clear from the fall/winter and we should get everything squared away for a May launch. The results can be reviewed here: https://github.com/DomKnowlage/Kickstarter_Analysis/commit/47eddb5550eaed4d054c15e982cb502a0bb77d6a#diff-cc3f8653d7de4056f03f5c39a5e9b7e7ad2fd86e64fd1f3f38bfacf487b8212e


##**Limitations and Possibilities**
Some of the limitations I can see from this data is theres no clear success guaranteed with this analysis, this more or less provideds some guidelines on the best times to launch and the relative success of those launches. We can apply this data for all kinds of Kickstarters; from technology, food trucks, film and housing you can do it all with this kind of analysis. Some other graphs we could create is pie charts based on the amount of projects filed so you know if you are getting into an oversaturated field and try to break into new territory.
