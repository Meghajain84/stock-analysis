# stock-analysis
Module 2 Challenge


## Overview of Project: Explain the purpose of this analysis.
Steve recently graduated in finanace concentration. His parents are interested in investing in green stocks, particularly in DAQ0 stock. They asked Steve to analyze the market so that they can invest in right green stock. 
Steve gathered two years data on about 12 green stocks to analyze the profitable stocks 
With refactored code, Steve would be able to expand the dataset to include entire stock market over couple of years as it's more robust.

## Results: 

### Comparison of stock analysis results for years 2017 and 2018

![Stock_Analysis_Numbers_2017_2018](Image link)

We can clearly see that stock market was doing really good in 2017 with all the green stocks showing upward trend except 'TERP'. 'DQ' was at the top that year in returns.

In 2018, all green stocks are showing downward trend with the exception of 'ENPH' and 'RUN'


### Refactored script vs non-refactored 

![green_stocks_2017](Image link)
![green_stocks_2018](Image link)
![VBA_Challenge_2017](Image link)
![VBA_Challenge_2018](Image link)

We can clearly see that refactored script ran faster, thus saving time and is expandable for anlayzing entire stock market over couple of years.
Refcatoring was achieved using arrays. Maintaining arrays for all tickers' volumes, starting prices and ending prices is very useful as these can be used for any other use in future (including arrays code snippet screenshot below). We won't be needed to go over all the rows of data again to gather same information as we saved in arrays.
Arrays added structure to code, and readability improved with comments as well.

![Code_Snippet](Image link)

In my opoinion best time to buy stock is when market is bit down in order to get good rate to buy; but should be convinced that market will go up for green stocks. That confidence can only come after looking at trend for couple of years and be informed about green energy's direction in the country.

## Summary: 

### Advantages of refactoring code are as follows:
1) Restructuring code without changing the functionality makes code better organized
2) Extendibility is easier with refactored code
3) Refactoring adds better readability thus saving time in extending the code later in future or debug

### Disadvantages of refactoring code are as follows:
1) Changing working code sometimes add bugs and that takes up programmer's time to debug and make the code working again

### How do these pros and cons apply to refactoring the original VBA script?
1) Pro: Extendibility of the code improved due to arrays introduction in refactored code. The data in arrays would be available for any other use in future, we won't have to go over the same dataset again to gather same information
2) Pro: The code has been structed in a way that it is easily readbale, thus can be reused in future easily
3) Pro: The proper comments are helpful in understanding the code
4) Con: I added a bug "out of bound" while I was working on refactored code.I eventually was able to fix the array size. That took some time.
