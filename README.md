## Project 1 Presentation Outline 
•	Title Slide
* Include the name of the project and group members.

•	Proposed Title: Travel, Happiness, and COVID

### •	Motivation & Summary Slide
* Define the core message or hypothesis of your project:
            We believe that there is a positive correlation between a country’s happiness score and how often it was travelled too. If there is a correlation between a country’s happiness score and how often it was travelled to, then a country’s score may have decreased because of COVID and lockdown. The market was negatively affect by COVID, and the travel industry and subsectors were impacted greatly, what one subsector impacted more than another? 

*	Describe the questions you asked, and why you asked them.
How are travel trend’s correlated with a country’s happiness score?
	Was a country’s happiness score impacted by the COVID shut down of 2020?
	How were benchmark travel sector names impacted by COVID? Was one sub-sector impacted more then another?
	We were curious to see if there was an unconscious bias between travel destinations and a country’s happiness score (I,e, if a score is high, then is that traveled to more then if a score is low?)
	
*	Describe whether you were able to answer these questions to your satisfaction, and briefly summarize your findings.

### •	Questions & Data
*   Elaborate on the questions you asked, describing what kinds of data you needed to answer them and where you found it.
* We used several data sets:
     * Monthly air passenger data set: this identifies travel into and out of the US on a monthly basis over the span of several years. A negative about this data is that it is not complete, however it offers a decent sample size. This data set was found on Kaggle
    * World Happiness Index – historical and current: This data set ranks a country’s happiness and well-being levels as calculated on: Real GDP per capital, social support, healthy life expectancy, freedom to make life choices, generosity, perceptions of corruption, etc. The historical data was found on Kaggle and the 2021 data was found on the World Happiness website
    * Alpaca Stock API: This was to capture trade data on different tickers that are benchmark names to their subsector for the travel industry. 

•	Data Cleanup & Exploration
•	Describe the exploration and cleanup process.
*    First thing we identified which columns we needed from each data set. Example; From the monthly air passenger log, we wanted to have the US as our starting point for our analysis, so we kept all outgoing flights
*    We joined our data sets to better run our analysis for travel trends + happiness

*  Stocks:
    *    Created a data frame to house all the stock data
    *   Filtered data from the original, main data frame based on sub-sector to better analyze stock movement for that sector
*	Discuss insights you had while exploring the data that you didn't anticipate.
    *	We didn’t anticipate plotly not working.Also, lots of system issues
*  Discuss any problems that arose after exploring the data, and how you resolved them.
    * Data was straightforward, most of our issues were with the systems. 
*	Present and discuss interesting figures developed during exploration, ideally with the help of Jupyter Notebook.



### •	Data Analysis
* 	Discuss the steps you took to analyze the data and answer each question you asked in your proposal:
    *   Having the data presented visually was very helpful in identifying trends	
*	Present and discuss interesting figures developed during analysis, ideally with the help of Jupyter Notebook.
### •	Discussion
*	Discuss your findings. Did you find what you expected to find? If not, why not? What inferences or general conclusions can you draw from your analysis?
    * Correlation: No – based on our data, it does not look like a country’s happiness score affects travel into that country. 
    *   COVID & Country’s happiness score + Travel – No correlation
    * Stocks:
        * Hotels:
	Marriot is the outperformer for hotels within this travel sub-sector and levels have recovered to prepandemic levels
        * Restaurants:
	McDonalds is the clear outperformer, they did not have as big of a decrease in their stock price. It appears that they have surpassed their prepandemic stock valuation. 
        * Travel Services:
	Services that individuals can book their vacations/travel plans, etc. Such as Travel Search Engines
        * Travel search engines
	Booking -> owns Kayak, OpenTable and a few other
	Expedia is showing that it was not impacted much due to the pandemic, this chart is a little misleading since the scale of expedia is so much smaller then Booking. Booking clearly shows the dip during the pandemic and has since recovered and exceeded pre-pandemic levels. 
        * Cruise lines
	Cruise lines were negatively impacted by COVID, and it appears that the drop for cruise lines was quite a lot. Even though we are reopening, cruise lines still have not recovered to prepandemic levels. 
### •	Postmortem
*	Discuss any difficulties that arose, and how you dealt with them.
•	Discuss any additional questions that came up, but which you didn't have time to answer: What would you research next, if you had two more weeks?
*	Questions
•	Open-floor Q&A with the audience

