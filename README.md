# School_District_Analysis

#Purpose
#The investigation initially served to show what schools tend to have the best test results and why, comparing the reading and math scores, then factoring in their total budget, budget per student, total student size, and whether they're a charter or district school. While there's too little data to make bold conclusions, it appears the biggest deciding factor is whether the school is charter or district. All of the top five are charter, while the bottom five are district. There also appears to be a small correlation for class size, as all the top five have less than 2,500, but all the bottom five have over 2,500, but these are not numerically sound.

#The challenge serves to isolate one group, Thomas high 9th graders, some of whom have been accused of cheating, and run the analysis again to see the impact of dropping them.

#for the class, it serves as an introduction to pandas and numpy, which allowed us to manipulate the data within the spreadsheets instead of just reading it like we did with the previous python exercise, as well as an intro to jupyter.

#Analysis

#The overall takeaway was that dropping the 9th grade class had minimal effect on the analysis as a whole, but to get into specifics, the district has not changed. Adjusted_Top.png and Normal_Top.png demonstrate that Thomas high school is still the second highest school. District_Stats_Adjusted.png and District_Stats_Original.png show there is very little change in the overall stats, with the original numbers having a slightly higher math passing rate.

#Removing the 9th Grade naturally only impacts the 9th grade stats, with Adjusted_Ninth.png and Original_Ninth.png showing it slightly drops the average by less than 1% each. The school size stats in Original_School_Size.png and Adjusted_School_Size.png are identical, as are the stats for Original_School_Spending.png, Adjusted_School_Spending.png, Original_School_Type.png and Adjusted_School_Type.png. Overall, this seemed to be a minor changes that did not throw off the averages.

#Summary

#The major changes appear to be in the 9th grade statistics with a minor drop. Overall, this drops all stats, including Math and Reading raw numbers and percents. This doesn't seem to drop the actual in the overall statistics, making it appear as if the cheating was minor in terms of being widespread. Although it's possible any students that cheating are still cheating significantly as outliers, but it doesn't appear to be widespread.
