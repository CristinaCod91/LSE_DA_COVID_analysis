# LSE_DA_COVID_analysis
Week 2 
Summarise (>200 words) any insights you've discovered as well as anything you would like to explore further. For example:
a.	Did you notice anything interesting about the data?

b.	Does the DataFrame have a default index? 

c.	What are some of the initial insights you've discovered?

d.	How has the number of vaccinated individuals changed over time? What might these changes indicate? Include reasons to support your rationale.

e.	On which date(s) are there values missing, and from which columns and rows are these values missing? Which states or provinces do the missing values belong to?
f.	Is there anything unusual about the filtered Gilbraltar DataFrame? Include reasons to support your rationale.
a.	Both data csv files have the same number of rows, being 7584. Both data types are object. With regards to the number of missing values, cov_19_uk_vaccinated csv file does not have anu missing values compare to covid_19_uk_cases, which has 2 rows of missing values.
b.	The data frame has been assigned with a default index.
c.	The number of first dose vaccinations starts increasing from January 2021, hitting its peak by March 2021 to 94,000 cases and then massively decreasing around April 2021. It continues to gradually increase, however, the highest number reaches only 34,000 cases in June 2021, which, is down by triple the amount of cases registered in March. Furthermore, cases continue to steadily decrease until October 2021. 

With regards to the second dose vaccinations, it is important to mention that people are more reluctant on getting it as the number of vaccines throughout the period did not have high spikes compare to the first does, meaning that people were taking more time to decide whether it is the right decision to do, being afraid of side effects. However, the percentage difference between the first and second dose was not big, being only 2% down.
d.	There are missing values on dates 2020-09-21, 2020-09-22, Bermuda state. The columns having NaN are  Deaths, Cases, Recovered, Hospitalised.
e.	When looking at the filtered Gibraltar DataFrame, it was identified that the number of hospitalised cases is higher on particular dates that the number of cases.

Week 3
Summarise (150–200 words) any insights you've discovered as well as anything you would like to explore further. For example:

•	Which Province/State has the highest number of individuals who have received a first dose but not a second dose?

•	Which Province/State has the highest percentage of individuals who have received a first dose but not a second dose.

•	How has the number of vaccinated individuals and individuals who have received the first and second doses, changed over time? (Hint: You only need to describe what you observe in the data set at this point. Specify whether you are referring to a specific Province/State (e.g. Gibraltar) or the data set in general.)

When extracting the highest number of individuals who have received the first dose but not the second one, it appears to be Gibraltar, as the number of populations is also higher than the rest. However, when calculating the highest percentage of the missing second doses, the results show a different insight, where Turks and Caicos Islands are the leaders.

By analysing how has the number of vaccinated individuals changed over time, it can be described that from January 2021 to end of March 2021, first dose is surpassing the second dose on a daily number of vaccines. However, it was noticed that from the March 30th, 2021, second dose took over the leadership in total daily numbers and continued to do so until the October 2nd, 2021.

Similar trend can be seen when looking at a particular state/province. On Gibraltar, second dose is surpassing the first dose numbers, starting from March 30th, 2021. However, an unusual sharp drop in vaccines was noticed in June 6th, 2021. Moreover, another decline was detected on dates August 29th -30th, 2021.

Week 4
Summarise (150–200 words) any insights you've discovered as well as anything you would like to explore further. For example:

a.	Is there a consistent trend running across the data? Are there any groups that are skewed and should be removed? 
b.	Did you notice any difference after converting Date into Months?
c.	How are the death rates increasing across regions? Has it reached a peak?
d.	What is the percentage of the first dose to fully vaccinated individuals?
e.	Can you see any trends across groups (Province/State)?
f.	Which region has had the most recoveries, and has this been consistent over time?
g.	Are your visualisation of good quality? How can you improve, for example, the smoothness of the lines?
h.	How will this visualisation be valuable for the government to use in making informed decisions?
By calculating the percentage of first dose to fully vaccinated, Turks and Caicos Islands where the highest in people not fully vaccinated, followed by Isle of Man and Anguilla. The ones having the highest percentage of fully vaccinated were Saint Helena, Ascension and Tristan da Cunha, Others, Bermuda and Gibraltar.
When looking at the trend of the death cases, it can be clearly seen an increase starting from March month, 2020. Channel Islands has a consistent increase throughout the period hitting its highest peak during October month, 2021.It’s important to notice that Gibraltar show as shar increase starting from December month, 2020 and continues having high cases of death throughout. An unclear explanation to the data of Gibraltar is that it starts with higher cases of hospitalised than the registered cases and hence, it’s crucial to look at the source of data provided again and check the numbers. 
Overall, all the states and provinces have a trend of deaths increase around July month, 2021 until October 2021, except for Montserrat and Cayman Islands having a steady low number of cases during all the period provided in the data.
There were also groups of regions that were skewing the data having no cases registered to extremely high numbers e.g “Others”. It was crucial in stripping them out and see a clear picture of deaths across the territories.
After converting the Date into Month, the visualisation looked cleaner and easier to read.
Furthermore, the region having the most recoveries are Channels Islands and Gibraltar. It has not been consistent overtime, on the contrary, it can be noticed a sharp increase starting from November month, 2020, having a steadiness from March, 2021 until June month, 2021 and then followed by a sudden drop in August, 2021. It is also important to note that there is a trend for all regions dropping in recoveries around August, 2021 and reaching its lowest numbers by September 2021.

