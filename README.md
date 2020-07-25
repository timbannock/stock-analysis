# Stock Analysis

## Overview of Project
Steve's stock analysis project.
### Purpose
Steve wants to analyze the stocks to see what recommendations he can make to his parents regarding their investment into DQ and other stocks.
## Analysis and Challenges
While most of the stocks did well in 2017, only two of them were in the green by 2018: ENPH and RUN. ENPH especially had extremely good returns in both years, so that seems like a stock that is trending very strong. Meanwhile, DQ -- their choice stock -- suffered fairly massive losses in 2018 compared to excellent growth in 2017; it's impossible to say what this means in the long-term, but it's not a good trend.
As for the analysis itself, refactoring the subroutines led to significant changes for the better in how quickly the macros ran. While overall, these are rather small analysis in terms of how much information they are dealing with, it's clear that the refactoring had a significant impact, perhaps in part by removing more complex actions like nested loops.
### Challenges and Difficulties Encountered
The first issue I ran into was understanding how to refer back to the different arrays. Initializing arrays inside of for loops didn't entirely make sense to me, and I didn't recall that in our lessons. Furthermore, after looking into roughly half of the activities, I found none of them seemed to provide examples anything close to what we were doing in the challenge; in fact, half of those didn't have any instructions in them whatsoever, so they were useless. Combined with the focus of both Tue and Thu classes being more on getting folks setup with Git access, I don't feel like we covered anything that prepared me for the actions needed in the Challenge. Perhaps that's not an issue of Challenge itself, nor the data we are analyzing within it, but it really undermined my confidence in tackling this Challenge from the start.
- *What are some limitations of this dataset?*
- - Only looking at 2 years of data on 12 stocks really doesn't provide much in the way of understanding a long-term investment in any of these individual stocks. While it's fairly obvious that analyzing even more stocks would be great, I think it's possibly more important to understand the long-term trends for these individual stocks, so we'd want to go back many more years.
- *What are some other possible tables and/or graphs that we could create?*
- - I think a bar chart showing the 2017 and 2018 return analysis of each stock would be a great visual tool to show us how big the change was from one year to the next. This would help reveal which stocks had huge swings versus which ones might be more of a steady change (or increase).
- - A bar or line chart by month for any stocks that look like good choices after doing the above might help illuminate a better sense of trends over time, rather than focusing on just the change in a year.
