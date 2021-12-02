
# stock-analysis
Overview of Project
The purpose of this project was to help Steve with financial analysis for green stocks. We did this by exploring how often a stock is traded, as in the case of DAQO, for example. The financial analysis included yearly volumes for 2017 and 2018 as well as returns for each year to assess the performance of each stock. The project was aimed at facilitating the analysis through the use of VBA macros, which in turn helped to  quicken the analysis process with user-friendly buttons, for instance. Additionally, the code was refactored in order to make the process as seamless and quick as possible for Steve. The analysis structure was also made to capture future needs entailing the use of larger stock datasets. 

Results based on the Refactored Code
As it can be observed in 2017, DQ had the highest returns at 199.4% although it was not the most traded stock. The most traded green stock was SPWR with a positive return of only 23.1%. This highlights the reality that the most traded stock is not the most profitable in retrospect. In fact DQ was the least traded by volume, confirming this assertion. 

As of 2018, DQ plummeted considerably at -62.6%. RUN, however, was at the top at 84.0% increasing drastically from its positive return of 5.5% from the previous year. The second runner-up was ENPH at 81.9. Although ENPH fared better in the previous year, it maintained a positive outlook for 2018 unlike most of the other tickers. Overall, 2018 was an unprofitable year for green stocks with one two profitable bets. Further insights into why 2018 was dramatically grim for green investors would shed great light on the reasons for the losses incurred.  

In terms of speed it took 0.59 seconds in the orginal code to process 2017 data and 0.58 for 2018. On the other hand, the refactored code let to 0.10 seconds processing for 2017 and 0.11 for 2018. 

Refactored
![alt text](https://github.com/BBright07/stock-analysis/blob/main/Resources/VBA_Challenge_2017.png.PNG)
![alt text](https://github.com/BBright07/stock-analysis/blob/main/Resources/VBA_Challenge_2018.png.PNG)

Original
![alt text](https://github.com/BBright07/stock-analysis/blob/main/Resources/Original2017.PNG)
![alt text](https://github.com/BBright07/stock-analysis/blob/main/Resources/Orignal2018.PNG)

Summary
Refactoring the code ultimately  quickened the processing time and improved the efficiency and effectiveness of this financial analysis. However, refactoring came with a fare share of bugs that led to more costs in terms of initial time invested in its drafting. But in the longterm the refactored code will save time.
The original code was more intuitive to proceed with in the back-end but took more time to execute. In the long-term and with the use of larger data sets the additional processing time will ultimately be magnified and result in a negative experience for Steve. Thus, refactoring is a proactive way forward. 