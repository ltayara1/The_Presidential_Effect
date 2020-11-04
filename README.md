# **The Presidential Effect**


*Chris Bryant, Lauren Tayara, Raniah Jeanlys, Surafel Gebreyesus*


## **Methodology**

This project plots four indicators as variables of the economy across the span of the Reagan, Bush Sr., Clinton, Bush Jr., Obama, and Trump presidencies. Balance of trade, real gross domestic product (GDP), stock, and unemployment were chosen as indicators of economic health. Team members collected data sets from 1981 until most current in 2020 as CSV files from different sources. 

Balance of trade came from macrotrends.net and was calculated using the export divided by the import. It required removal of the dollar signs and “B” that indicated billions from the “Billions of US $” column. The year column was set as the index, and the “% of GDP” column was dropped due to finding data from another source. Finally, the “Billions of US $” column data was formatted as an integer rounded to the nearest whole number.  

Unemployment rate and real gross domestic product (GDP) data sets were pulled from the Federal Reserve Economic Data (FRED) website. Unemployment is calculated from dividing the total number of unemployed people by the total number of people in the labor force. Real GDP is calculated as total exports minus total imports. The index column for both of these data sets were set to the date column as they were read in. In the Real GDP data, one of the columns was renamed to reflect “Billions of Dollars.” 

The Dow Jones stock dataset also came from macrotrends.net. The index column was set to year as the data was read in. Six of the columns were dropped as they showed in the data but did not contain any values. The data was sorted by year. 

All data sets were spliced using “iloc” on the rows according to the following presidency year ranges:

•	Ronald Reagan 1981 - 1988

•	George Bush 1989 - 1992

•	Bill Clinton 1993 - 2000

•	George W. Bush 2001 - 2008

•	Barak Obama 2009 - 2016

•	Donald Trump 2017 - Current

Unemployment was adjusted using a 12-month step to indicate full years rather than monthly data. Real GDP data was also adjusted to show yearly grouping using a four-step as the data came in quarters. All datasets were added to one notebook and grouped according to the spliced presidency data. Each presidential group was added to two rows stacked in two columns to create a grid of line plots for each president. The tabs were named for each president and as the tabs are clicked, coordinating parts of the line plots show in color to indicate that president’s range of years. The first tab reflects the full range of data. 


## **Final Analysis**

#### Question 1: What economic effect (stock market, Real GDP, unemployment, balance of trade) occurred during each president?
When assessing the president’s impact on the economy this was separated into four sections: stock market, REAL GDP, unemployment, and balance of trades. Firstly, when it comes to stock it’s apparent that the presidents have little impact on the growth and changes in the stock market seeing as how the market line was growing in a general positive direction despite the year and the president. When it comes to Real GDP it seems that it is similar to stock market in the fact that the line trends positively through all years regardless of the president. The few changes in the line are most likely due to external factors likely unrelated to presidential policies. There was a positive general trend on trade during Reagan’s terms, and this seemed like he reached this in the end of his second term. Another presidency that showed an overall positive trade outcome was Obama, which was quite a significant change. Bush Sr. generally showed a positive trade trends during his single term. Clinton showed negative balance of trades in his first and second term. Bush Jr. had a similar impact as Clinton and had a general negative balance of trade during his presidency but increased during his second term. Recently, in the assessment of Trump’s presidency, there was a negative trend on the balance of trade in his first term. When it comes to the unemployment rate the presidents that lowered the unemployment rate were Reagan, Clinton, Obama, and Trump, thus showing a positive trend on this economic indicator. Both Bush Sr. and Bush Jr. had a rise in unemployment, but there was slight decrease in unemployment in Bush Jr.’s second term.


#### Question 2: Are the economic indicators dependent or independent of the president?
Our data showed that for Real GDP and Stocks (Dow Jones) the president was independent of economy performance. For unemployment and Balance of trade economy is dependent of the presidency. We believe there are other factors that are not covered in our research such as National Security, Health Care, Education and Energy, just to name a few, that should also be counted as influencing factors.

#### Question 3: Does the political party of the president influence the economy?
Across trade and unemployment, different presidential parties showed different results. For instance, all Republican presidents, Reagan, Bush Sr., Bush Jr., and Trump, had varying trends in trade and unemployment. The same occurs when comparing Democrat presidents, Clinton and Obama. The two most economically successful presidents in trade and unemployment were Reagan and Obama, from two different political parties. Political party does not show to predict success of trade or unemployment.

#### Question 4: Does the length of presidency influence the length of economic influence?
Reagan, Clinton, Bush Jr. and Obama served two terms each lasting eight years as president. Bush Sr. was the only president to serve one term (4 years). Trump has only had the opportunity to serve one term with the potential to serve another if elected again this month. The data showed improvements from the first to second term for all of the 2-term presidencies. For instance, Bush Jr.’s unemployment was high in his first term, but by the second term, it decreased below the first term. The same thing occurred during Obama’s presidency with the balance of trade improving in the second term. None of the indicators got worse from the first to second term.

#### Question 5: How will past economic results help forecast for future elections?
Despite people’s personal biases to one president or political party, the research does not show an easy forecast for future elections.

*Other Factors*

◦We believe there are other factors that are not covered in our research such as National Security, Health Care, Education and Energy, just to name a few, that should also be counted as indicators.
◦Policies and regulations by each president

◦“The hangover effect” - results after a president’s term

◦Uncontrollable events - COVID, 9/11, Recession, etc.


## **Implications**
*What do the findings mean?*

Neither the president nor political party necessarily influence the economy. Two-term presidencies show more opportunity for economic success than one term.

*How do they impact finance?*

According to the indicators analyzed in this research, these results show that the president has little to no influence on finance and the economy. Therefore, promises of economic success made during presidential campaigns do not show throughout the different presidencies. Economic success traditionally associated with certain political parties also does not prove valid from this research. 
