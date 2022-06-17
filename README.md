# **Kickstarter_Analysis**
## **Overview**
My team and I have been combing through Kickstarter project data to evaluate an optimal time to launch a project for a client of ours
## **Analysis and Challenges**
Some of the main challenges we encountered had to deal syntax. We have some new members on the team that are just getting their feet wet with some of the various conditionals, especially when it came to the =COUNTIFS formula. When looking over the data I found my new comers forgot to add a 3rd line of criteria to our data pertaining to the outcomes based on goals they were doing =COUNTIFS(Kickstarter!D:D,">=10000",Kickstarter!D:D,"<14999")               
instead of =COUNTIFS(Kickstarter!D:D,">=10000",Kickstarter!D:D,"<14999", Kickstarter!F:F,"Successful") completly skewing the data. Luckily a quick chat with their supervisor cleared things up and we were able to get the results we needed.
## **Outcomes Based on Goals**
Based on the goals we can determine that the best range for success is between $20,000 to $30,000. Any higher amount results in a higher volatility which could add some additional stresses to the project.
