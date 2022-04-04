# LSE_DA_COVID_analysis
a. Did you notice anything interesting about the data?

Data: 22/01/2020 – 14/10/2021 ~631 rows of data for each country.
The UK data set for cases and vaccination has a lot less missing data vs. the global data set. 

b. Does the DataFrame have a default index? 

The DataFrame has a default index. 

c. What are some of the initial insights you've discovered?

The data is sequential. It’s cumulative.

d. How has the number of vaccinated individuals changed over time? What might these changes indicate? Include reasons to support you rationale.

There is no vaccinated individuals, and then it suddenly starts. It appears as though they don’t have enough data on the date of when individuals were vaccinated, so they just added them in a lump and started records from there. Then from there, the data increased. 

e. On which date(s) are there values missing and from which columns and rows are these values missing? Which states or provinces do the missing values belong to?

Cases: Bermuda only has two rows of missing data with Nan on the 21 and 22 of September, 2021
Vaccinations: Nil
Global: 194 rows of data with Nan for lots of different countries. 
Twitter: 15 rows of missing data.

f. Is there anything unusual about the filtered Gilbraltar DataFrame? Include reasons to support your rationale.

There is some missing data at the end under the recovered section and also two in the hospitalised section. But on the whole – the Gibraltar DataFrame has very little missing data. 

In regards to the data. The total death tally is very low. 
