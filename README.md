Report/Summary (as per the weekly activity course content/assignment template)

Week: 1
•	GitHub is an open-source website for developers and programmers to collaboratively work on code. The main benefit of GitHub is its version control system, which allows for collaboration without compromising the integrity of the original project. 
•	It adds value to organisations; by facilitating team collaboration and coherence, leads to increased productivity and team satisfaction, and helps to prevent workplace silo issues.

Week: 2
8a. Did you notice anything interesting about the data?
c. What are some of the initial insights you've discovered?
	Cases:	Deaths:	Recovered:	Hospitalised:
Date range: 	22/01/2020 – 14/10/2021	22/01/2020 – 14/10/2021	22/01/2020 -  04/08/2021 only*	22/01/2020 - 12/10/2021 – missing last two rows
Data set: 	632 rows
Missing values/errors:	Very few errors/NaN across across the data – quite clean on the whole. See e. below
Data type:	Cumulative	Cumulative	Cumulative*	Appears to be daily count
Data sense check:	Numbers appear appropriate for real world populations	Numbers appear appropriate for real world populations**	Numbers appear appropriate for real world populations. However* - makes the data difficult to use as it is incomplete.	Don’t make real world sense***

*There are sections where zero is entered – both at the start and later on the in data. For cases and deaths – it appears that the zeros at the start are indeed zero and then increase naturally. However, in the “Recovered” data – for “Others/Great Britain” and “St Helena’s”, it starts at zero, then increases and then drops off to zero – it appears that there was no more data collection – so it isn’t a zero. Maybe ‘no data’ would have been more appropriate. Due to this – it is difficult to draw conclusions from this data. A real life consideration for this – it would be very difficult to determine when someone has recovered. What is the definition of recovery? Not positive on tests? Feeling  x% better? Out of hospital? Especially with the number of people who had long covid – this is a difficult question to answer. Therefore I think the “Recovered” data is of little use. For the “Cases, Deaths and Recovered” – the data starts out at zero and then builds up cumulatively. Whilst for the ”Hospitalised” data it starts at zero and then suddenly is a number – as if the data collectors weren’t collecting any data and then they all started at the same time when there were a couple of hundred people in hospital. The data for “Hospitalised” appear to be cumulative initially, however – if you look at the data over time – it goes up and down, therefore it cannot be cumulative and appears to be a daily count of people in hospital at that time.

**However data for Falkland Islands (Malvinas) and Saint Helena, Ascension and Tristan da Cunha is zero. The population is low in these places – 3,480 and 6,077 respectively, and the number of cases was also low in these places – 69 and 4 respectively. So it is difficult to know if these indeed zero or no data. Furthermore, Montserrat had 41 cases and 1 death – so it does make sense that they are indeed accurate and that there were no deaths. 

***Falkland Islands (Malvinas) has a population of: 3,480 and at one stage a daily count of those “Hospitalised” was: 3,140 – which doesn’t make real world sense. Similarly, Montserrat has a population of: 4,992 and at one stage a daily count of those “Hospitalised” was: 4,514 – which also doesn’t make real world sense. 90.23% and 90.42% of the population being in hospital at one time isn’t believable/comparable to any COVID situations seen throughout the world in the COVID pandemic. Furthermore, Others/Great Britain has a population of: 67,886,011 and the highest daily count of those “Hospitalised” was: 2,159 – which doesn’t make real world sense. Nor does it make sense compared to the “Cases and Deaths” across Great Britain and comparatively to other countries. 

	Vaccinations:	First dose:	Second dose:
Date range: 	22/01/2020 – 12/10/2021 (13-14/10/2021 – entries zero). 
Zero until 11/01/2021****	22/01/2020 – 12/10/2021. (13-14/10/2021 – entries zero).
Zero until 11/01/2021****	22/01/2020 – 12/10/2021. (13-14/10/2021 – entries zero).
Zero until 11/01/2021****
Data set: 	632 rows
Missing values/errors:	Very few errors/NaN across across the data – quite clean on the whole. 
Data type:	Not cumulative, as the data numbers go up and down, so it appears like they are a daily count. 
Data sense check:	The data doesn’t make real world sense. Mainly in comparison to the countries population (see below), as well as comparing between the different countries (eg. Montserrat with a population of 4,992 and 64,049 people fully vaccinated (highest number) and Great Britain with a population of 67,886,011 and only 30,632 people fully vaccinated (highest number)?? – this doesn’t make sense*****
****However, it’s a little strange that the data started in all of the countries on the same day. In a real world sense – this did not happen, as different countries started vaccinating at different times, different logistics and country regulations, as well as access. So maybe the vaccinations could have started a little earlier than this but the data wasn’t documented until this date? Furthermore, there is data recorded for the “Second dose” on this date – therefore first doses must have started earlier. It also doesn’t make sense that the “First dose” starts on the 11/01/2021 on the same day that people also became “Vaccinated” 11/01/2021 (both doses). Therefore, it would make more sense, that the “First doses” didn’t start on the 11/01/2021 – but prior to this (however are unrecorded), and this is just the start of data recording. 
***** 
Country:	Population as of 2020:
Anguilla:	15,003
Bermuda:	62,278
British Virgin Islands:	30,231
Cayman Islands:	65,722
Channel Islands:	173,863
Falkland Islands:	3,480
Gibraltar:	33,691
Isle of Man:	85,033
Montserrat:	4,992
Saint Helena:	6,077
Turk and Caicos Islands:	38,717
Others/Great Britain (England/Wales/Scotland/Northern Ireland):	67,886,011
References:
https://data.worldbank.org/indicator/SP.POP.TOTL
https://www.ons.gov.uk/
https://www.worldometers.info/world-population/
Furthermore – I found some data re: country vaccination rates online and the numbers don’t correlate: (https://github.com/owid/covid-19-data/tree/master/public/data/vaccinations).

b. Does the DataFrame have a default index?

•	The DataFrame has a default index.

d. How has the number of vaccinated individuals changed over time? What might these changes indicate? Include reasons to support you rationale.

•	There is no data and then it starts for “Vaccinated, First dose and Second dose” on the 11/01/2021. Following the trends over time: 
-	“Vaccinated” goes up and down and up and down, reaching maximums of 27,848 (Saint Helena, Ascension and Tristan da Cunha) to 69,619 (Gibraltar).
-	“First dose” goes up and down and then slowly declines, reaching maximums of 37,615 (Saint Helena, Ascension and Tristan da Cunha) to 94,038 (Gibraltar).
-	“Second dose” – is exactly the same as “Vaccinated”.

e. On which date(s) are there values missing and from which columns and rows are these values missing? Which states or provinces do the missing values belong to?

•	“Cases/Deaths/Recovered/Hospitalised”: Bermuda only has two rows of missing data with zero for these rows on the 21 + 22/09/2021 
•	“Vaccinations/First dose/Second dose”: Nil. 
•	It's not missing, but the value “Others” for GBR - refers to Great Britain and therefore I changed it to this to make the data and visualisations more readable. 

f. Is there anything unusual about the filtered Gibraltar DataFrame? Include reasons to support your rationale.

•	Low cases: 5727
•	Low deaths: 97
•	High hospitalised in comparison to cases: (4907 peak hospitalised count: 5727 cases). Brings to question how accurate the hospitalised data is, or potentially how accurate the cases data is?

Template: Can we make decisions based on total numbers only, or do trends over time offer additional insights?
•	Depending on the type of data:
-	Cumulative: more appropriate to look at total numbers, 
-	Daily count: not appropriate to look at trends over time.
-	However – still useful to look at both for both types, as it also helps one get a sense of the data initially.
•	Furthermore, since the data has huge implications for people’s lives and risk of death – there are high stakes, and analysis should be rigorous. 

Template: Why it is important to explore the data, what are the typical mistakes made in this phase?
•	It is so important to explore the data initially:
-	To understand it
-	Prevent assumptions
-	Ensure the correct functions/summaries are applied in the correct way
-	Check for errors and clean the data
-	Help formulate a plan
•	Typical mistakes made in this phase:
-	Assumptions about data types based on others (eg. that because some of the data is cumulative, that all the data is)
-	Not cleaning the data early – which can lead to issues and errors down the line
-	Not understanding the data fully – which can lead to issues and errors down the line
-	Not being able to formulate a plan because the you don’t understand the data – leading to time being wasted

Week:3
3. Determine the number of cases across the UK.
Province/State:	Cases:
Great Britain(Others)	8,317,439
Channel Islands	12,135
Isle of Man	8,434
Gibraltar	5,727
Bermuda	5,548
Turks and Caicos Islands	2,910
British Virgin Islands	2,725
Cayman Islands	1,011
Anguilla	644
Falkland Islands (Malvinas)	69
Montserrat	41
Saint Helena, Ascension and Tristan da Cunha	4

4.a. Which Province/State has the highest number of individuals who have received a first dose but not a second dose?
Gibraltar: 264,745

b. Which Province/State has the highest percentage of individuals who have received a first dose but not a second dose?
Turks and Caicos Islands: 4.510122%

c. How has the number of vaccinated individuals and individuals who have received the first and second doses, changed over time?
(see Python Notebook so % change over time)
For Anguilla:
-	The data starts out at First Dose Only: 85.68% and Second Dose: 14.32% on the 11/01/2021, it increases to reach a peak for First Dose Only: 98.86% to Second Dose: 1.14% on the 13/02/2021, and then the ratio slowly decreases for First Dose Only: 4.43% and inversely slowly increases for Second Dose: 95.57% on the 03/10/2021 (with occasional flattened/stable areas at times, then slightly increases to finish for First Dose Only: 4.51% and for Second Dose: 95.49% on 12/10/2022.
This pattern is quite similar for all of the Province/State’s.

Template: We use similar calculations and representations as we had in activity 2, but now expand to look at all provinces. Assignment 3 is concerned with exploring data in the context of a specific business question (as opposed to general exploration in assignment 2). What insights can be gained from the data? (Description of all regions, assumptions and concerns, trends or patterns you have observed.)


Template: Are there limitations or assumptions that needs to be considered?
Limitations: 
-	That we can only base our decision re: marketing aiming to increase second doses at this point in time. People’s opinions re: the vaccinations have fluctuated over time.
-	It is unlikely that all “Cases” and “Recovered” numbers are the full total. For “Cases”: people may have been symptomatic and not tested/not registered it. For “Recovered”: there is no definition of this – what qualifies for recovered?
-	Where do the Booster Jabs come into the picture? Were they recorded? Were they added to the first dose data? Or the second dose?
Assumptions:
-	That the data collected is indeed correction/accurate.
-	That the original vaccinations/first dose/second dose was indeed a daily count, therefore the calculated fields of cumulations and percentages are also correct.
-	That one person isn’t getting vaccinated more than the once and twice dose (eg. like the case in Australia where someone got vaccinated for other people and got 9 vaccinations in one day for other people).
-	That all the vaccination numbers are just of citizens in the countries and not people from other countries. It is likely that due to border closures, that were would be non-citizen’s and visitors to the country. 
-	That definitions of “Cases”, “Deaths”, “Recovered”, “Hospitalised” are standardised across the “Province/States”. There is likely to be errors in this also within “Province/States” due to medical opinion differences between those diagnosed. 

Template: Make sure to provide a brief overview of the data and typical considerations at this phase of analysis
Brief overview:
-	(see Week:2 8a.c. above)
-	Cases and deaths data looks accurate and reasonable for population sizes. 
-	Recovered data looks reasonable for population sizes, however isn’t collected for all countries.
-	Hospitalised data doesn’t look reasonable for population sizes.
-	Vaccinations and second dose numbers are the same.
-	First dose only and second dose counts (cumulative and percentage) are very similar and follow a similar pattern across the different countries. This is quite unusual and raises some alarm bells given the different sizes of the populations. Logistically it also seems unusual for them to be similar. The only thing that makes sense, is that they are all UK province’s and therefore maybe due to this, vaccine program rolled out at similar times. It also appears a bit odd that vaccination rates for first dose only and second dose were similar – I would think that across different countries/opinions/demographics that this would be a bit more varied. 
Typical considerations:
-	Double check/sense check calculated columns to make sure that the python code doesn’t have any errors. (I looked over the data after each change and also double checked some manual calculations).
-	Make sure that the original data has been changed/corrupted. 
-	It is sometimes difficult to understand the data before visualising – so some questions may need to wait until the visualisation section. 
![image](https://user-images.githubusercontent.com/98591821/166119564-7b5dbf8f-d61e-40d4-b032-897702305fa7.png)
